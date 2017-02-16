                                    /*Assignment 2.6*/
				     /* Question 1*/

import java.util.*;
public class acad {

	public static void main(String[] args) {
		
		int a=10;//first number
		int b=15;//second number
		int sum = a+b;//Addition of two numbers
		System.out.println("Addition of two numbers is:"+sum);//print output
		
	}
}


				 /*Question 2*/

import java.util.*;
public class acad {

	public static void main(String[] args) {
		Scanner ss = new Scanner(System.in);
		int a=ss.nextInt();//Input number
		int b=ss.nextInt();//Input number
		int sum = a+b;//addition of two numbers
		System.out.println("Addition of user input two numbers:"+sum);	//output is printed	
		ss.close();

	}
}



				 /*Question 3*/
import java.util.*;
public class acad {

	public static void main(String[] args) {
		
	sum();//method is called
	
	}
	static void sum()
	{
		Scanner ss = new Scanner(System.in);
		int a=ss.nextInt();//Input number
		int b=ss.nextInt();//Input number
		int sum = a+b;//addition of two numbers
		System.out.println("First number is:"+a);//print first number
		System.out.println("Second number is:"+b);//print second number
		System.out.println("Sum is:"+sum);//print sum
		
		ss.close();
	}
}





				 /*Question 4*/

import java.util.ArrayList;
import java.util.Collections;
import java.util.LinkedHashSet;
import java.util.Scanner;
public class acad {

	public static void main(String[] args) {
	
		Scanner ss = new Scanner(System.in);
		int a=ss.nextInt();//Input the first number
		int b=ss.nextInt();//Input the second number
		LinkedHashSet<Integer> even = new LinkedHashSet<Integer>();//to store the even numbers as we don't know the range
		LinkedHashSet<Integer> odd = new LinkedHashSet<Integer>();//to store the odd numbers as we don't no the range
		for(int i=a;i<=b;i++)//for the given range
		{
			if(i%2==0)//condition for even
			{
				even.add(i);
			}
			else
			{
				odd.add(i);
			}
		}
		System.out.println("Even Numbers are:");
		
		System.out.println(even);//display even numbers
		System.out.println("Odd Numbers are:");
		
		System.out.println(odd);//display odd numbers
		ss.close();
	}
}

				 /*Question 5*/
import java.util.ArrayList;
import java.util.Collections;
import java.util.Scanner;
public class acad {

	public static void main(String[] args) {
	
		Scanner ss = new Scanner(System.in);
		int a=ss.nextInt();//Input the number to get the first 10 multiples 
		
		int mul[] = new int[10];//to store result
		
		for(int i=0;i<10;i++)//for the given range
		{
			mul[i] = a*(i+1);
		}
		System.out.println("Multiplication table of "+a);
		for(int j=0;j<10;j++)// to display the first 10 multiples
		{
			int u =j+1;
			System.out.println("3X"+u+"="+mul[j]);
		}
			ss.close();
	}
}


				 /*Question 6*/

import java.util.*;
public class acad {

	public static void main(String[] args) {
		Scanner ss = new Scanner(System.in);
		int a=ss.nextInt();//Input number
		int b=ss.nextInt();//Input number
		int d =ss.nextInt(); //Input number
		sum(a,b);//method called with two variables
		sum(a,b,d);//method called with three variables
		ss.close();
	
	
	}

	static void sum(int a,int b)//method to divide two variables
	{
		
		
		int c;
		c=a/b;
		System.out.println("Method with two variables");
		System.out.println(c);//print the result

		
	}
	
	static void sum(int a,int b,int d)//method to find modulo of two variable and add third variable
	{
		int c;
		c=a%b+d;
		System.out.println("Method with three variables"+"\n"+c);//print the result
	}
}



				 /*Question 7*/
import java.util.*;
public class acad {

	public static void main(String[] args) {
		Scanner ss = new Scanner(System.in);
		int a=ss.nextInt();//Input number
		int b=ss.nextInt();//Input number
		int d =ss.nextInt(); //Input number
		System.out.println(sum(a,b));//method called with two variables
		System.out.println(sum(a,b,d));//method called with three variables
		ss.close();
	
	
	}

	static double sum(int a,int b)//method to divide two variables
	{
		
		
		int c;
		c=a/b;
		return c;
		
	}
	
	static double sum(int a,int b,int d)//method to find modulo of two variable and add third variable
	{
		int c;
		c=a%b+d;
		return c;
	}
}
/*
Method with different argument counts can have a same return type for overloading.
If the arguments are same and the return type is same or different then an error will be thrown.
*/


				 /*Question 8*/

import java.util.*;
public class acad {

	public static void main(String[] args) {
		Scanner ss = new Scanner(System.in);
		System.out.println("Input the size of an array");
		int a=ss.nextInt();//Size of an array
		ArrayList<Integer> d = new ArrayList<Integer>(a);//integer array declared
		System.out.println("Enter the elements of the array");
		for(int i=0;i<a;i++)
		{
			d.add(ss.nextInt()); //elements to be stored in an array
			
			
		}
		Collections.sort(d,Collections.reverseOrder());//for descending order arrangement
		System.out.println("Sorted Array");
		for(int j=0;j<a;j++)//display of the array as a sequence
		{
			System.out.println(d.get(j));
		}
		ss.close();
		
	}
	}

				 /*Question 8*/
import java.util.*;
public class acad {

	public static void main(String[] args) {
		Scanner ss = new Scanner(System.in);
		System.out.println("Input the size of an array");
		int a=ss.nextInt();//Size of an array
		ArrayList<Integer> d = new ArrayList<Integer>(a);//integer array declared
		System.out.println("Enter the elements of the array");
		for(int i=0;i<a;i++)
		{
			d.add(ss.nextInt()); //elements to be stored in an array
			
			
		}
		Collections.sort(d,Collections.reverseOrder());//for descending order arrangement
		System.out.println("Sorted Array");
		for(int j=0;j<a;j++)//display of the array as a sequence
		{
			System.out.println(d.get(j));
		}
		ss.close();
		
	}
	}
