# simple-calculator-in-java
// Source code is decompiled from a .class file using FernFlower decompiler.
import java.util.Scanner;

public class main {
   public main() {
   }

   public static void main(String[] var0) {
      System.out.println("   SIMPLE CALCULCTOR   ");
      Scanner var1 = new Scanner(System.in);
      System.out.println("number1");
      int var2 = var1.nextInt();
      System.out.println("number2");
      int var3 = var1.nextInt();
      System.out.println("CHOOSE YOUR OPERATOR(1-4)");
      String var4 = "";
      int var5 = var1.nextInt();
      switch (var5) {
         case 1:
            var4 = "Addition";
            System.out.println(var2 + var3);
            break;
         case 2:
            var4 = "Subtraction";
            System.out.println(var2 - var3);
            break;
         case 3:
            var4 = "Multiplication";
            System.out.println(var2 * var3);
            break;
         case 4:
            var4 = "Divition";
            System.out.println(var2 / var3);
      }

      var1.close();
   }
}
