# ass1.6

1.Write a java code with the class named ‘acad’ and a method ‘main’. Hardcode the program
with two integers and print the sum of those two.
         class Acad
         {
           public static void main(String args[])
             {
              int a=6,b=4,sum;
              sum=a+b;
              System.out.println(sum);
              }
          }
 2.Rewrite the above code, where, inputs are provided by the user at runtime and the output
is printed
import java.util.*;
 class Acad{
 public static void main(String args[]){
 Scanner s=new Scanner(System.in);
 int a=s.nextInt();
 int b=s.nextInt();
 int sum;
 sum=a+b;
 System.out.println(sum);}}
 3.Write a program with method name sum() that accepts two parameters from user and print
the sum two numbers.
import java.util.*;
 class Acad{
 public static void main(String args[]){
 Scanner s=new Scanner(System.in);
 int a=s.nextInt();
 int b=s.nextInt();
 int sum=add(a,b);
 System.out.println(sum);}
 private static int add(int a,int b){
 int ad;
 ad=a+b;
 return ad;
 }
 }
  
