import java.util.Scanner;
public class Experiment_8
{
	public static void main(String[] args) {
	    String user_name,user_id,user_mobilenumber;
	    String name_regex="[a-z]+",int_regex="[0-9]+",mobile_regex="[0-9]{10}";
	    Scanner sc =new Scanner(System.in);

			//user name

		System.out.println("Enter the user Name");
		user_name= sc.next();
		if(user_name.matches(name_regex))
		    System.out.println(user_name+" is valid user name");
		else
		    System.out.println(user_name+" is invalid user name,user name should have only letters");

		       //user id

		System.out.println("Enter the user id");
		user_id= sc.next();
		if(user_id.matches(int_regex))
		    System.out.println(user_id+" is valid user id");
		else
		    System.out.println(user_id+" is invalid user id,user id should have only numbers");
		    

			//user mobile number

		System.out.println("Enter the user mobile number");
		user_mobilenumber= sc.next();
		if(user_mobilenumber.matches(mobile_regex))
		    System.out.println(user_mobilenumber+" is valid mobile number");
		  
		else
		    System.out.println(user_mobilenumber+" is invalid mobile number,mobile number should have only integers and length should be 10");
	}
}
