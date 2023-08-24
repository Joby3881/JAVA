import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.println("enter a number");
        int a=input.nextInt();
        if(a%5==0 && a%11==0)
        {
            System.out.println("is divisible");
        }
        else
        {
            System.out.println("is not divisible");
        }



    }
}