Import .swing.*;

import .awt.*;

class TesGridLayout {

public static void main(String[] args) {

JFrame f = new JFrame("Tes Swing");

f.setDefaultLookAndFeelDecorated(true);

f.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
JButton b = new JButton("Tombol 1");
JButton b = new JButton("Tombol 2");
JButton b = new JButton("Tombol 3");
JButton b = new JButton("Tombol 4");
JButton b = new JButton("Tombol 5");
JButton b = new JButton("Tombol 6");
JPanel p1 = new JPanel();
p1.setLayout(new GridLayout(4, 2));
p1.add(b1);
p1.add(b2);
p1.add(b3);
p1.add(b4);
p1.add(b5);
p1.add(b6);

f.add("North", p1);
JButton b7 = new JButton("Tombol 7");
JButton b8 = new JButton("Tombol 8");
JButton b9 = new JButton("Tombol 9");
JButton b10 = new JButton("Tombol 10");
JButton b11 = new JButton("Tombol 11");
JButton b12 = new JButton("Tombol 12");
JPanel p2 = new JPanel();
p2.setLayout(new GridLayout(2, 4, 10, 10));
p2.add(b);
p2.add(b);
p2.add(b);
p2.add(b);
p2.add(b);

p2.add(b);
f.add("South", p2);
f.pack();
f.setVisible(true);
}
}
