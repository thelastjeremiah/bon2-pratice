<h3>Example 1</h3>

<p>Mau ni na code ang mu accept ug user inputs na naka string</p>

```java
/* mau ning ang reason nganu ka maka gamit ug JOption page ang tawag ani `import statement` ga tawag ni siya ug mga ready made na mga na code na code na mu create sa JOptionPage  */
import javax.swing.JOptionPane;

public class UserInputs {
  public static void main(String[] args) {
    String firstName = JOptionPane.showInputDialog("Enter your first name:");
    String middleName = JOptionPane.showInputDialog("Enter your middle name:");
    String lastName = JOptionPane.showInputDialog("Enter your last name:");

    String fullName = firstName + " " + middleName + " " + lastName;

    JOptionPane.showMessageDialog(null, "Full Name: " + fullName);
  }
}

```



<h3>Example 2</h3>

<p>Kani diri example pud sa array ug imu tanawun makita nimu na gi display ra naku 
ang Anilo ug Panaw</p>

```java
import javax.swing.JOptionPane;

public class NameArray {
  public static void main(String[] args) {
    String[] names = {"Anilo", "Panaw"};

    StringBuilder message = new StringBuilder();
    for (String name : names) {
      message.append(name).append(" ");
    }

    JOptionPane.showMessageDialog(null, message.toString(), "", JOptionPane.INFORMATION_MESSAGE);
  }
}

```


<h1 style="margin-top:5rem;">Challenge </h1>

<p>Gusto ko mag buhat ka ug code na mu accept ug FIRST NAME , MIDDLE NAME , LAST NAME
Dapat ang mga gi input nimu kay ma sulod ni siya sa array ug dapat mapa output pud na nimu gikan sa array</p>

<p>Oh naa nawung ni Odin para ma inspire ka</p>


<img src=image/odin.jpg style="margin-top:5rem;">
