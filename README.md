import java.util.Scanner;
public class main{
    public static void main(String[]args){
        System.out.println("   SIMPLE CALCULCTOR   ");
        Scanner scanner=new Scanner(System.in);
        System.out.println("number1");
        int num1=scanner.nextInt();
        System.out.println("number2"); 
        int num2=scanner.nextInt();
        System.out.println("CHOOSE YOUR OPERATOR(1-4)");
        String operator="";
        int oper = scanner.nextInt(); 
        switch(oper){
            case 1:
                operator="Addition";
                System.out.println(num1+num2);
                break;
            case 2:
                operator="Subtraction";
                System.out.println(num1-num2);
                break;
            case 3:
                operator="Multiplication";
                System.out.println(num1*num2);
                break;
            case 4:
                operator="Divition";
                System.out.println(num1/num2);
                break;

        }
        scanner.close();

    }
}
