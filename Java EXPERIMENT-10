import java.util.Scanner;
public class Experiment_10
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
		int a,b;
		System.out.println("Enter the value of a");
		a=sc.nextInt();
	    System.out.println("Enter the value of b");
	    b=sc.nextInt();
	    //to find the gcd of the two numbers
	   int a1=a,b1=b;
	   while(a1!=b1){
	       if(a1>b1)
	        a1-=b1;
	        else
	        b1-=a1;
	   }
	   //gcd of the two numbers is stored in a1
	    System.out.print("value of "+a+"/"+b+" = ");
	    System.out.print(a/a1+"/"+b/a1);//dividing the numbers with gcd(a1) to convert them into fraction
	}
}
