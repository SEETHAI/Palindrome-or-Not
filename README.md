# Palindrome-or-Not
Java program to check whether the number is Palindrome or Not
import java.util.Scanner;
public class Palindrome 
{ 
      public static void main(String args[]) 
       { 
          int y,number, z=0,temp=0;         
          Scanner sc=new Scanner(System.in);          
          System.out.println ("Enter any number: ");  
         number=sc.nextInt(); 
         Y=number; 
         while(number>0) 
        { 
            Y=number%10; 
            number=number/10;           
            temp=temp*10+y; 
        }
        if(temp==z) 
       { 
           System.out.println("Number is Palindrome"); 
        } 
       else 
       { 
           System.out.println("not Palindrome"); 
        }
      } 
  } ﻿
