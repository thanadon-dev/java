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
        
        //งานที่ 1
        import java.util.Scanner;
        public class MyClass {
            public static void main(String args[]) {

            //Thanadon Kongaknun
            Scanner mark = new Scanner(System.in); 
            System.out.println("ระบุช่วงเวลาของคุณ :");
            int time = mark.nextInt();

             if(time < 18){
                 System.out.println("Good Day");
             }else {
                 System.out.println("Good Evening");
             }

             System.out.println("นาย ธนดล  คงคะนันท์ เลขที่ 10");
     
             }
            } 
            //งานที่1ก็อปถึงตรงนี้
            
            //======================================================================================================================
            //======================================================================================================================
            

            //การบ้าน อันนี้เขียนใน NetBeans IDE 8.2 จะใช้ก็เอาไปแปลงกันเองหล่ะ
            //เริ่ม !!
            
            package thanadon;

                import javax.swing.JOptionPane;
                import java.util.Scanner;

                public class Thanadon {

                    public static void main(String[] args) {

                // CR Thanadon Kongkanun
                //    ชื่อจริง
                        Scanner markFn = new Scanner(System.in);
                        System.out.println("กรุณากรอกชื่อ :");
                        String markFirstName = markFn.nextLine();
                //    นามสกุล
                        Scanner markLn = new Scanner(System.in);
                        System.out.println("กรุณากรอกนามสกุล :");
                        String markLastName = markLn.nextLine();

                //    ห้อง
                        Scanner markRm = new Scanner(System.in);
                        System.out.println("กรุณากรอกห้อง :");
                        String markRoom = markRm.nextLine();

                //    ชื่อวิชา
                        Scanner markSj = new Scanner(System.in);
                        System.out.println("กรุณากรอกชื่อวิชา :");
                        String markSubject = markSj.nextLine();

                //    คะแนน
                        Scanner markSc = new Scanner(System.in);
                        System.out.println("กรุณากรอกคะแนน :");
                        float markScore = markSc.nextFloat();

                //        แสดงข้อมูลทั้งหมด
                        System.out.println("========== : แสดงข้อมูลทั้งหมด : ==========");
                        System.out.println("คุณชื่อ : " + markFirstName + " นามสกุล " + markLastName);
                        System.out.println("ห้องเรียน : " + markRoom);
                        System.out.println("เรียนวิชา : " + markSubject);

                //        if & else (เงื่อนไขต่างๆ)
                        if (markScore >= 80) {
                            System.out.println("คะแนนของคุณคือ :" + markScore);
                            System.out.println("คุณได้เกรด 4");
                        } else if (markScore >= 75) {
                            System.out.println("คะแนนของคุณคือ :" + markScore);
                            System.out.println("คุณได้เกรด 3.5");
                        } else if (markScore >= 70) {
                            System.out.println("คะแนนของคุณคือ :" + markScore);
                            System.out.println("คุณได้เกรด 3");
                        } else if (markScore >= 65) {
                            System.out.println("คะแนนของคุณคือ :" + markScore);
                            System.out.println("คุณได้เกรด 2.5");
                        } else if (markScore >= 55) {
                            System.out.println("คะแนนของคุณคือ :" + markScore);
                            System.out.println("คุณได้เกรด 1.5");
                        } else if (markScore >= 50) {
                            System.out.println("คะแนนของคุณคือ :" + markScore);
                            System.out.println("คุณได้เกรด 1");
                        } else {
                            System.out.println("คะแนนของคุณคือ :" + markScore);
                            System.out.println("คุณสอบตก");
                        }

                    }


                }
                
                
             
            //======================================================================================================================
            //======================================================================================================================
            
            // เป็นโค้ดที่ก็อปเอาไปทั้งหมดแล้วไปวางรันบนเว็บนี้ได้เลย : https://www.jdoodle.com/online-java-compile
             //อันนี้การบ้านสำหรับโค้ดที่ขนาดย่อส่วนลง มันจะอ่านง่ายกว่าเดิมเยอะมากๆ
             
             import java.util.Scanner;

                public class MyClass {
                    public static void main(String args[]) {
                         Scanner scanw = new Scanner(System.in);
                        System.out.println("กรุณากรอกชื่อ :");
                        String markFirstName = scanw.nextLine();
                        System.out.println("กรุณากรอกนามสกุล :");
                        String markLastName = scanw.nextLine();
                        System.out.println("กรุณากรอกห้อง :");
                        String markRoom = scanw.nextLine();
                        System.out.println("กรุณากรอกชื่อวิชา :");
                        String markSubject = scanw.nextLine();
                        System.out.println("กรุณากรอกคะแนน :");
                        float markScore = scanw.nextFloat();
                        double grade = 1.1;

                // CR. Thanadon Kongkanun

                //        แสดงข้อมูลทั้งหมด
                        System.out.println("========== : แสดงข้อมูลทั้งหมด : ==========");
                        System.out.println("คุณชื่อ : " + markFirstName + " นามสกุล " + markLastName);
                        System.out.println("ห้องเรียน : " + markRoom);
                        System.out.println("เรียนวิชา : " + markSubject);

                //        if & else (เงื่อนไขต่างๆ)
                        if (markScore >= 80) {
                            grade = 4;
                        } else if (markScore >= 75) {
                            grade = 3.5;
                        } else if (markScore >= 70) {
                            grade = 3;
                        } else if (markScore >= 65) {
                            grade = 2.5;
                        } else if (markScore >= 55) {
                            grade = 1.5;
                        } else if (markScore >= 50) {
                            grade = 1;
                        } else {
                            grade = 0;
                        }

                        System.out.println("คะแนนของคุณคือ :" + markScore);
                        System.out.println("คุณได้เกรด  " + grade);

                    }
                }


```ข้อสอบตาหนุ่ม มั้ง
```java
import java.util.Scanner;

public class MyClass {
        public static void main(String args[])
              {
                int num;
                System.out.println("กรุณากรอกเลข :");
            
                Scanner input = new Scanner(System.in);
                num = input.nextInt();
            
                if ( num % 2 == 0 )
                    System.out.println(num + " เป็นเลขคู่");
                 else
                    System.out.println(num + " เป็นเลขคี่");
              }
}
```

```java
// ถ้าจะมาก็อปแล้วนินทาด่ากูก็หัดเขียนเองนะไอโง่
// เข้าไปที่เว็บนี้ https://www.jdoodle.com/online-java-compiler/

import java.util.Scanner;

public class MyClass {
    public static void main(String args[]) {
      
    //Thanadon Kongkanun
    Scanner MaRkzAA = new Scanner(System.in);
    System.out.println("เวลาของคุณคือ ?  :  ");
	int markk = MaRkzAA.nextInt(); 
	
    	switch (markk) {
          case 1:
            System.out.println("Monday");
            break;
          case 2:
            System.out.println("Tuesday");
            break;
          case 3:
            System.out.println("Wednesday");
            break;
          case 4:
            System.out.println("Thursday");
            break;
          case 5:
            System.out.println("Friday");
            break;
          case 6:
            System.out.println("Saturday");
            break;
          case 7:
            System.out.println("Sunday");
            break;
        }
      
    }
}
```

