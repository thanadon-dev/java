# Java งานตาหนุ่มอะ 23/12/2020
```java

        //อย่าลืม Import ตัวนี้ก่อนใช้ JOptionPane ด้วยหละ
        import javax.swing.JOptionPane;

        // งานที่ 1
       JOptionPane.showMessageDialog(null, "รักเมียรักเมียรักเมีย", "เทสเทส", JOptionPane.ERROR_MESSAGE);
       JOptionPane.showMessageDialog(null, "รักเมียรักเมียรักเมีย", "เทสเทส", JOptionPane.INFORMATION_MESSAGE);
       JOptionPane.showMessageDialog(null, "รักเมียรักเมียรักเมีย", "เทสเทส", JOptionPane.PLAIN_MESSAGE);
       JOptionPane.showMessageDialog(null, "รักเมียรักเมียรักเมีย", "เทสเทส", JOptionPane.QUESTION_MESSAGE);
       JOptionPane.showMessageDialog(null, "รักเมียรักเมียรักเมีย", "เทสเทส", JOptionPane.WARNING_MESSAGE);
       
        // งานที่ 2
        String m = JOptionPane.showInputDialog("What is you name?");
       JOptionPane.showMessageDialog(null, "ชื่อของคุณคือ :" + m, "หัวข้อ", JOptionPane.WARNING_MESSAGE);
       
       //การบ้าน
        String markname = JOptionPane.showInputDialog("คุณชื่ออะไร ?");
        String markmoney = JOptionPane.showInputDialog("เงินรายวัน ?");
        String markhour = JOptionPane.showInputDialog("เงินเรทค่าแรง ?");
        System.out.println("ชื่อของคุณคือ : " + markname);
        System.out.println("เงินรายวัน : " + markmoney);
        System.out.println("เงินเรทค่าแรง : " + markhour);
        int total = Integer.parseInt(markmoney) * Integer.parseInt(markhour);
        System.out.println("จำนวนเงินผลลัพธ์ : " + total);
       
```

# Java งานตาหนุ่มอะ 24/12/2020

```java
        //แปลงจาก String
        Integer.parseInt        //แปลงจาก String เป็น Int
        Short.parseShort       
        Long.parseLong
        Float.parseFloat
        Double.parseDouble

        //แปลงเป็น String
        Integer.ToString
        Integer.ToHexString
        Integer.ToOctalString
        Integer.ToBinaryString

```

# Java งานตาหนุ่มอะ 25/12/2020

```java
        // ก็อปวางบนเว็บ https://www.jdoodle.com/online-java-compiler 
        // ก็ใช้ได้เลย
        
        //งานที่ 1 import java.util.Scanner;
        public class MyClass {
            public static void main(String args[]) {

            //Thanadon Kongaknun
            Scanner mark = new Scanner(System.in); 
            System.out.println("กรอกมาสิสาส");
            int time = mark.nextInt();

             if(time < 18){
                 System.out.println("Good Day");
             }else {
                 System.out.println("Good Evening");
             }

             System.out.println("นาย ธนดล  คงคะนันท์ เลขที่ 10");

            }
        }

```

