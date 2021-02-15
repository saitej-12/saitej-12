import java.util.InputMismatchException;
import java.util.Scanner;

public class Experiment_13 {
    static int quotient(int numerator,int denominator) throws ArithmeticException{
        return numerator/denominator;
    }
    public static void main (String args[]){


        try{
            Scanner sc = new Scanner(System.in);
            System.out.println("Enter the numerator");
            int numer = sc.nextInt();
            System.out.println("Enter the denominator");
            int denomi = sc.nextInt();

            int n = quotient(numer,denomi);

            System.out.println("output is :"+ n);

        }
        catch (InputMismatchException IME){
            System.out.println("Input is types are wrong following exception raised "+IME);
        }
        catch (ArithmeticException AE){
                System.out.println("Division by Zero error");
        }


    }
}
