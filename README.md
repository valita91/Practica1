# Practica1
Practica 1 con Java
# 1- Solicite un número y muestre en consola si es positivo o negativo.
package Ejercicio;
import java.util.Scanner;
public class Ejercicio1 {
		public static void main(String[] args) {
			Scanner entrada = new Scanner (System.in);
			System.out.println("Ingrese un número");
			int numero = entrada.nextInt();
			if (numero>=0) {
				System.out.print("El número ingresado es positivo");
			    } else {
			    	System.out.print("El número ingresado es negativo");
			    }
			entrada.close();
			}
	}
	
# 2- Solicite dos números y muestre en consola si son iguales o distintos.

package Ejercicio;
import java.util.Scanner;
public class Ejercicio2 {
	public static void main(String[] args) {
	Scanner entrada = new Scanner (System.in);
	System.out.println("Ingrese un número");
	int numero1 = entrada.nextInt();
	System.out.println("Ingrese otro número");
	int numero2 = entrada.nextInt();
	  if (numero1==numero2) {
		 System.out.print("Los números ingresados son iguales");
	     } else {
		 System.out.print("Los números ingresados son distintos");
	     }
	entrada.close();
 }
}

# 3- Solicite dos números y muestre en consola el resultado de la suma de ellos.

package Ejercicio;
import java.util.Scanner;
public class Ejercicio3 {
	public static void main(String[] args) {	
		Scanner entrada = new Scanner (System.in);
		System.out.println("Ingrese el primer número");
		int numero1 = entrada.nextInt();
		System.out.println("Ingrese el segundo número");
		int numero2 = entrada.nextInt();
		System.out.print("La suma de los numeros es: " + (numero1 + numero2));
		entrada.close();
		 }
	}
	
# 4- Solicite dos números y muestre en consola el resultado de la división entre ellos.

package Ejercicio;
import java.util.Scanner;
public class Ejercicio4 {
	public static void main(String[] args) {	
		Scanner entrada = new Scanner (System.in);
		System.out.println("Ingrese el primero número");
		float numero1 = entrada.nextInt();
		System.out.println("Ingrese el segundo número");
		float numero2 = entrada.nextInt();
		System.out.print("La division entre ambos números es: " + (numero1 / numero2));
		entrada.close();
	}
}

# 5- Solicite dos números y muestre en consola si el resultado de la resta entre ellos es positivo o negativo.

package Ejercicio;
import java.util.Scanner;
public class Ejercicio5 {
	public static void main(String[] args) {	
		Scanner entrada = new Scanner (System.in);
		System.out.println("Ingrese el primer número");
		int numero1 = entrada.nextInt();
		System.out.println("Ingrese el segundo número");
		int numero2 = entrada.nextInt();
		if ((numero1- numero2)>0) {
			System.out.print(">> La resta es un número POSITIVO. Resultado: " + (numero1 - numero2));
		    } else {
		    	System.out.print(">> La resta es un número NEGATIVO. Resultado: " + (numero1 - numero2) );
		    }
		entrada.close();
		}
}

# 6- Solicite dos números y muestre en consola al mayor de ellos.

package Ejercicio;
import java.util.Scanner;
public class Ejercicio6 {
	public static void main(String[] args) {	
		Scanner entrada = new Scanner (System.in);
		System.out.println("Ingrese el primero número");
		int numero1 = entrada.nextInt();
		System.out.println("Ingrese el segundo número");
		int numero2 = entrada.nextInt();
		if (numero1> numero2) {
			System.out.print(">> El mayor es el primer número: " + numero1);
		    } else {
		    	System.out.print(">> El mayor es el segundo número: " + numero2);
	        }
		entrada.close();
		}
}

# 7- Solicite tres números y muestre en consola si se han ingresado en orden creciente.

package Ejercicio;
import java.util.Scanner;
public class Ejercicio7 {
	public static void main(String[] args) {	
		Scanner entrada = new Scanner (System.in);
		System.out.println("Ingrese el primero número");
		int numero1 = entrada.nextInt();
		System.out.println("Ingrese el segundo número");
		int numero2 = entrada.nextInt();
		System.out.println("Ingrese el tercer número");
		int numero3 = entrada.nextInt();
		if (numero1<numero2 && numero2<numero3){
			System.out.print(">> Los números están ordenados en orden creciente");
		    } else {
		    	System.out.print(">> Los números NO están ordenados en orden creciente");
		    }
		entrada.close();
	}
}

# 8- Solicite tres números y los muestre en consola ordenados de manera creciente.

package Ejercicio;
import java.util.Scanner;

public class Ejercicio8 {
	public static void main(String[] args) {	
		int a,b,c;
      Scanner Entrada = new Scanner(System.in);
      System.out.println("Introduzca el primer número: ");
      a=Entrada.nextInt();
      System.out.println("Introduzca el segundo número: ");
      b=Entrada.nextInt();
      System.out.println("Introduzca el tercer número: ");
      c=Entrada.nextInt();
      if(a>b && b>c) {
          System.out.println(c + "; " + b + "; " + a);
      }else{
          if(a>c && c>b) {
              System.out.println(b + "; " + c + "; " + a);
      }else{
             if(b>a && a>c) {
                 System.out.println(c + "; " + a + "; " + b);
      }else{
                if(b>c && c>a) {
                    System.out.println(a + "; " + c + "; " + b);
      }else{
                    if(c>a && a>b) {
                       System.out.println(b + "; " + a + "; " + c);
      }else{
      	System.out.println(a + "; " + b + "; " + c);
      } 
        }
      }
     }
   } 
 }  
}

# 9- Solicite un número y muestre en consola si es par o impar.

package Ejercicio;
import java.util.Scanner;
public class Ejercicio9 {
	public static void main(String[] args) {	
		Scanner entrada = new Scanner (System.in);
		System.out.println("Ingrese un número");
		int numero = entrada.nextInt();
		if (numero % 2 == 0 ) {
			System.out.print("El número ingresado es PAR");
		    } else {
		    	System.out.print("El número ingresado es IMPAR");
		    }
		entrada.close();
		}
}

# 10- Solicite un número del 1 al 7 y muestre en consola el día de la semana 

package Ejercicio;
import java.util.Scanner;
public class Ejercicio10{
	public static void main(String[] args) {	
  Scanner entrada = new Scanner (System.in);
  System.out.println("Ingresa un número");
  int numero = entrada.nextInt();
  if(numero == 1) {
      System.out.println("Hoy es LUNES");
  }else{
      if(numero == 2) {           
      System.out.println("Hoy es MARTES");
  }else{
   	     if(numero == 3) {           
      	 System.out.println("Hoy es MIERCOLES");
  }else{
            if(numero == 4) {
            System.out.println("Hoy es JUEVES");
  }else{
               if(numero == 5) {
               System.out.println("Hoy es VIERNES");
  }else{
                   if(numero == 6) {
                   System.out.println("Hoy es SABADO");
  }else{
  	                  if(numero == 7) {
                      System.out.println("Hoy es DOMINGO");
  }else{
      	System.out.println("El número ingresado no es día de la semana");
      	System.out.println("Ingrese un número del 1 al 7");
                } 
              }
            }
          }
        } 
      }  
    }
  }
}
