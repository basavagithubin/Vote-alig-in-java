# Vote-alig-in-java


import java.io.*;
import java.util.*;
public class Main
{
	public static void main(String[] args) {
		int age;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the number");
		age=sc.nextInt();
		if(age<18){
		System.out.println("A can't vote ");
		}
		else{
		System.out.println("A can vote ");}
		
	}
}
