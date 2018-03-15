









import java.awt.*;
import java.awt.event.*;
import javax.swing.*;

class cMario extends JFrame
{
    public cMario()
    {
        Container cp = this.getContentPane();
        JPanel jp1 = new JPanel();
        jp jp2 = new jp();
        JLabel jLab1;

        jLab1 = new JLabel(new ImageIcon("J0301A.gif"));

        jp1.add(jLab1);

        cp.add(jp1, BorderLayout.CENTER);
        cp.add(jp2, BorderLayout.NORTH);

        this.setTitle("Super Mario Paint");
        this.pack();
        //this.setSize(600,400);
        this.setLocationRelativeTo(null);
		this.setVisible(true);
		setDefaultCloseOperation(EXIT_ON_CLOSE);
    }
}
