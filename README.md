# Jagged-array
I have a done a program in JAGGED ARRAY using java programming language.

import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int n=sc.nextInt();
	    int a[][]=new int[n][];
	    for(int i=0;i<n;i++)
	    {
	           a[i]=new int[sc.nextInt()];}
	          for(int i=0;i<a.length;i++){
	        for(int j=0;j<a[i].length;j++)
	        {
	        a[i][j]=sc.nextInt();
	    }
	}
	for(int i=0;i<a.length;i++){
	    for(int j=0;j<a[i].length;j++){
	        System.out.print(a[i][j]+" ");
	    }
	    System.out.println();
	}
	}
}

