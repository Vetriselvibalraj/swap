# swap
import java.util.Scanner;
public class Swap{
  public static void main(String []args)
   { 
     int x=200,y=300;
     
     System.out.println("Before Swap");
     System.out.println("x="+x);
     System.out.println("y="+y);
    
      int temp=x; 
      x=y; 
      y=temp; 
      
    System.out.println("After Swap");
    System.out.println("x="+x);
    System.out.println("y="+y);
   }
  }
