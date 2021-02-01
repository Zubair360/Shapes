# Shapes
import java.util.*;
public class Main1{
  public static void main(String[]args){
    Scanner sc=new Scanner(System.in);
   double a=sc.nextDouble();
   double b=sc.nextDouble();
   double c=sc.nextDouble();
   double triangle=0.5*a*c;
   double circle=3.14159*c*c;
   double trapezium=0.5*(a+b)*c;
   double square=b*b;
   double rectangle=a*b;
   
   
    System.out.println("NUMBER = "+a);
  
    System.out.printf("TRIANGULO: %.3f\n",triangle);
       System.out.printf("CIRCULO: %.3f\n",circle);
       System.out.printf("TRAPEZIO: %.3f\n",trapezium);
       System.out.printf("QUADRADO: %.3f\n",square);
        System.out.printf("RETANGULO: %.3f\n",rectangle);
  }
}
