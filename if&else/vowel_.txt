import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.println("enter a letter");
        char x=input.next().charAt(0);

       if(x=='a' || x=='e' || x=='i' || x=='o' || x=='u')
      { System.out.println("vowal");}
       else{ System.out.println("Consonanat");
       }

}
}