# Simple-Adding-Calc
# This is for educational purposes only


import java.util.Scanner;

class addingCalc {
    Scanner keyPressed= new Scanner(System.in);
		double n1, n2;                                        #declares the first and second number
		System.out.println("Enter first num : ");
		n1 = keyPressed.nextDouble();
		System.out.println("Enter second num : ");
		n2 = keyPressed.nextDouble();
		double answer = n1 + n2;                              #adds nums inputted by user
		System.out.println(n1 + " + " + n2 + " = " + answer); #shows user the problem
}
