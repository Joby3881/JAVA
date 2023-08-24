import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.print("enter the a number");
        int a=input.nextInt();
        System.out.print("enter second number");
        int b=input.nextInt();
        if(a>b)
        {
            System.out.println("ais max :" +a);
        }
        if (b>a)
        {
            System.out.println("b is max :"+b);
        }

    }
}
