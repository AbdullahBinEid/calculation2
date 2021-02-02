# calculation2
package alculation;

import java.util.Scanner;

public class calculation2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.print("enter a number:");
		Scanner input = new Scanner(System.in); 
		
		  int a = input.nextInt();
		  int b = input.nextInt();
		  	
		  
		 System.out.println("enter the calculation:");
		 Scanner number = new Scanner(System.in);
		 char calculation = number.next().charAt(0);
		 if (calculation == '+')
		 {
			  System.out.print(a+b);
		 }
		 if (calculation == '-')
		 {
			 System.out.print(a-b);
		 }
		 if (calculation == '*')
		 {
			 System.out.print(a*b);
		 }
		 if (calculation == '÷')
		 {
			 System.out.print(a/b);
		 }
	}

}
