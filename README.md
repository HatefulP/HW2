// 1

#import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	     
	      Scanner sc = new Scanner(System.in);
	           
	      System.out.println("Введите пятизначное число: ");
	     
	      int num = sc.nextInt();
	      String text = Integer.toString(num);
	      int i = 0;
	      int length = Integer.toString(num).length();
	     
	      while(i < length){
	         char result = text.charAt(i++);
	         System.out.println(result);   
	      }
	      sc.close();
	   }
	}

//2

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	     
	      Scanner sc = new Scanner(System.in);     
	     
	      System.out.println("Введите значение первой стороны треугольника:");
	      int firstside = sc.nextInt();     
	     
	      System.out.println("Введите значение второй стороны треугольника:");
	      int secondside = sc.nextInt();
	     
	      System.out.println("Введите значение третей стороны треугольника:");
	      int thirddside = sc.nextInt();
	     
	      double s = (firstside + secondside + thirddside) / 2.0;
	      double result = Math.sqrt(s * (s - firstside) * (s - secondside) * (s - thirddside));
	           
	      System.out.println(result);     
	     
	      sc.close();
	   }
	}
	
//3

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
	     
	      Scanner sc = new Scanner(System.in);     
	     
	      System.out.println("Введите радиус окружности:");
	      double radius = sc.nextDouble();
	         
	      double result = 2 * Math.PI * radius;
	      System.out.println("Длина окружности = " + result);
	     
	      sc.close();
	   }
	}
