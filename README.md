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
