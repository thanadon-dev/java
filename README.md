# java
อาจารย์ให้จดลงสมุด !!

```java
package thanadon;

import java.util.Scanner;  // Import the Scanner class

public class Thanadon {

    public static void main(String[] args) {
      
    int x,y;
    
    Scanner c = new Scanner(System.in);
    System.out.print("input Number 1 : ");
    x = c.nextInt();
    System.out.print("inout Number 2 : ");
    y = c.nextInt();
    int a = x + y ;
    System.out.println("Calculator is :" + " " + a);
    
}

}
```

# Java งานตาหนุ่มอะ

```java


// ธนดล คงคะนันท์ จ้าา
package thanadon;

import java.util.Scanner;  

public class Thanadon {

    public static void main(String[] args) {
      
    int x,y;
    
    Scanner c = new Scanner(System.in);
    System.out.print("กี่ชวั่โมง/สัปดาห์ : ");
    x = c.nextInt();
    System.out.print("กี่บาท/ชั่วโมง : ");
    y = c.nextInt();
    
    int a = x * y ; 
    
    System.out.println("ผลลัพธ์ :" + " " + a);
    System.out.println("ผู้คำนวนคือ : ธนดล คงคะนันท์");

}

}

```
# Java งานตาหนุ่มอะ 23/12/2020
```java

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

