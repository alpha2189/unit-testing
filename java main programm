# unit-testing
an example of a simple program adding two positive numbers and getting the average

package intrasofttest;

import java.util.Scanner;

public class main {


    public static void main(String[] args) {
        // TODO Auto-generated method stub
        double number1;
        double number2;
        Scanner scan = new Scanner(System.in);
        System.out.print("Enter the first number you want to check:");
        number1 = scan.nextDouble();
        System.out.print("Enter the  second number you want to check:");
        number2 = scan.nextDouble();
        scan.close();
        System.out.println(countAverage(number1, number2));


    }

    public static double countAverage(double number1, double number2) {
        double ans = -1; // if number inputs are not valid(zero or negative) the programm returns -1.
        if((number1 > 0) && (number2 >0))
        {
            double Sum = number1 + number2;

            //System.out.println("The total sum of the numbers is " + Sum);
             ans = Sum / 2;
            //System.out.println("The Average of the numbers is " + AVG);
          
        }
       


        return ans;
    }
}
