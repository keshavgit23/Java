# Java
Age calculator using Java

import java.util.Scanner;
class AgeCalculator
{
	public static void main (String[] args) 
	{
	    Scanner scanner = new Scanner(System.in);
	
	System.out.println("Enter Your BirthYear:");
	int birthYear=scanner.nextInt();
	
	System.out.println("Enter The Current Year:");
    int currentYear=scanner.nextInt();
    
    System.out.println("Your Age = " + (currentYear-birthYear));
    
    scanner.close();
	}
}
