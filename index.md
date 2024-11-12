# <h1>Shinku's first markdown</h1>

Shinku added a header and some content to this markdown file.

![Spirited Away](https://i.pinimg.com/564x/77/7d/53/777d53a417aa60cb3854cf88f14a6f6a.jpg)

Simple Gui:

``` java
import javax.swing.JOptionPane;

public class BasicGui {
    public static void main(String[] args) {
        String name = JOptionPane.showInputDialog("Enter your name");
        JOptionPane.showMessageDialog(null, "Hello"+name);

        int age = Integer.parseInt(JOptionPane.showInputDialog("Enter your age"));
        JOptionPane.showMessageDialog(null, "You are "+age+" years old");

        double height = Double.parseDouble(JOptionPane.showInputDialog("Enter your height"));
        JOptionPane.showMessageDialog(null, "You are "+height+" cm tall");
    }
}
```
