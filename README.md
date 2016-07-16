package fifteen;

import java.util.Scanner;

public class Prime {

	
	public static void main(String[] args) {
		int flag=0;
		Scanner s=new Scanner(System.in);
		System.out.println("get the value from the user is:");
	    int n=s.nextInt();
	for(int i=2;i<=n/2;i++)
	{
		if(n%i==0)
		{
			flag=1;
		}
	}
		
	 if(flag==0)
		{
				System.out.println("is a prime");
		}
		
		else
		{
				System.out.println("is a not prime");
		}
		}
		
	}

	
