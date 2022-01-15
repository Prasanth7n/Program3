# Program3

package JavaTest;

import java.util.Scanner;

public class Program3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the range");
		int num = sc.nextInt();
		if (num%2!=0) 
		{
			for (int i=1;i<2*num;i++) 
			{
				System.out.println(i);
				i=i+1;
			}
		}else 
		{
			for(int i=1;i<(num*2)-1;i++) {
				System.out.println(i);
				i=i+1;
			}
		}
	}

}
Program 2

package JavaTest;
import java.util.*;
public class Program2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the range");
		int num = sc.nextInt();
       for (int i=1;i<=2*num;i++) {
    	   if(i%2!=0)
    	   System.out.println("the numbers are"+" "+i);
    	   i=i+1;
       }
	}

}

Program 1;

package JavaTest{
public class Calci
{
	void add(double a,double b) 
	{
		System.out.println(a+b);
	}
	void sub(double a,double b) 
	{
		System.out.println(a-b);
	}
	void multiple(double a,double b) 
	{
		System.out.println(a*b);
	}
	void division(double a, double b) 
	{
		System.out.println(a%b);
	}
	
}

public class Program1 {

	public static void main(String[] args) 
	{
		Calci ca = new Calci();
		ca.add(6.5, 5.5);
		ca.sub(6.5, 5.5);
		ca.multiple(6.5, 5.5);
		ca.division(6.5, 5.5);

	}

}
}
