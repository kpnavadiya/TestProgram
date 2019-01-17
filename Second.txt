import java.util.Scanner;

public class Swap
{
	public static void main(String[]args){
		System.out.println("Enter two Numbers");
			
			Scanner sc = new Scanner(System.in);
			int n1 = sc.nextInt();
			int n2 = sc.nextInt();
			
		System.out.println("n1 = "+n1 + "\t"+ "n2 = "+n2);	
		int temp;
		temp = n1;
		n1 = n2;
		n2 = temp;
		System.out.println("After Swaping");
		System.out.println("n1 = "+n1 + "\t"+ "n2 = "+n2);
	}
}
