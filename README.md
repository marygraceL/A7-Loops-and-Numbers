# A7-Loops-and-Numbers

Create a program that will ask the user to enter a positive number and counts. The program will
end the loop once the user enters a non-positive value and then display the sum of the numbers. (use
do-while statement).


package pnc;
import java.util.Scanner;
public class pnc {


	public static void main(String[] args) {
		Scanner sc = new Scanner (System.in);
		
		int num = 1;
		int sum = 0;
		int num1 = 0;
		
		do{
		 sum += num1;
		 
	System.out.print("Enter number " +num++ +": ");
	 num1 = sc.nextInt();

		
	
		 
		 } while(num1>=5);	System.out.println("You enter " +( num-2) +"numbers");
		 System.out.println("The sum of the number s is  " + sum);
  	 		 
		
		 
	}
}
