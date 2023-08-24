import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Enter your name");
        String name = input.nextLine();
        System.out.println("enter your roll number");
        long roll = input.nextLong();
        System.out.println("enter your five subject marks");
        int eng = input.nextInt();
        int hindi = input.nextInt();
        int phy = input.nextInt();
        int chem = input.nextInt();
        int math = input.nextInt();

        long total;
        long percentage;

        total = eng + hindi + phy + chem + math;
        percentage = (total *100)/500;
        System.out.println("Toalal marks : " +total);
        System.out.println("Percentage : " +percentage );

        if(percentage>=90 && percentage<=100)
        {
            System.out.println("Grad A+");
        }
        else if(percentage>=80 && percentage<=89)
        {
            System.out.println("Grad A");
        }
        else if(percentage>=70 && percentage<=79)
        {
            System.out.println("Grade B");
        }
        else if(percentage>=60 && percentage<=69)
        {
            System.out.println("Grad C");
        }
        else if(percentage>=50 && percentage<=59)
        {
            System.out.println("Grad D");
        }
        else if(percentage>=40 && percentage<=49)
        {
            System.out.println("Grade E");
        }
        else
        {
            System.out.println("Fail");
        }
    }
}
