import java.io.*;
import java.util.*;
public class CopyFile1 {

   public static void main(String args[]) throws IOException {
   Scanner s=new Scanner(System.in);
   int n=s.nextInt();
   int temp=n;
   int rem=0,sum=0,i=1,g=1;
   while(n!=0)
   {
    rem=n%10;
    
       sum=sum+rem*rem*rem; 
     n=n/10;
     }
     if(sum==temp)
     System.out.println(temp+" is amstrong number");
     else
      System.out.println(temp+" is not amstrong number");
      }
      }
