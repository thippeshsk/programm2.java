# programm2.java
programm2.java
import java.util.Scanner;
public class Launch
{

	public static void main(String[] args) 
	{
		int a;
				Scanner scan = new Scanner(System.in);
		System.out.println("enter the number");
		   a=scan.nextInt();
		 for(int i=1; i<=a; ++i)
		 {
			  
			  if(i%2!=0)
			  {
				  System.out.println(i);
			  }
			  else if(i%2==0)
			 {
			  ++a;
			 }
			  
			  
			 
		 }
	}

}
