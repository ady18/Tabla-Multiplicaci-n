# Tabla-Multiplicaci-n
package com.ejercicio;

import java.util.Scanner;

public class Tabla_Multiplicar_Ejercicio {

	public static void main(String[] args) {
		
		Scanner teclado = new Scanner(System.in);
		
		int num;
		String seguir = "s";
		
		do{
			System.out.print("Introduce un numero entero: ");
			num = teclado.nextInt();
			
			System.out.println("La tabla de multiplicar del " + num + " es: ");
			
			for(int i=0; i<=10; i++){
				System.out.println(num + "*" + i + " = " + (num*i));
				
			}

			System.out.print("Desea ver otra tabla? (s/n)");
			seguir = teclado.next();
			
		}while(seguir!="n");
		
		System.out.println("Fin del programa");
	}

}
