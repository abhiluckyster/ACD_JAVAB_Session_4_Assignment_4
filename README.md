# ACD_JAVAB_Session_4_Assignment_4

import java.util.Scanner;
public class StringReversal {
	public void Reversal(String str)
	{
		String Str1="";
		for(int i=str.length()-1;i>=0;i--)
		{
			Str1=Str1+str.charAt(i);
		}
		System.out.println(Str1);
	}
	public static void main(String[] args) {
		System.out.println(":Enter String");
		Scanner sc=new Scanner(System.in);
		String Str=sc.nextLine();
		StringReversal ob1=new StringReversal();
		ob1.Reversal(Str);
		sc.close();
	}
}
