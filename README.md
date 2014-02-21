package primeiro;

import java.util.Scanner;

public class teste {

	public static void main(String[] args) {
		
		int maior = 0, numero = 0; // declara os atributos e inicializa.
		Scanner sc = new Scanner(System.in);
		
		System.out.print("Entre com um valor: ");
		int num = sc.nextInt();
		
		for(int i = 1; i <=num; i++)
		{
			System.out.print("Entre com um valor " + i + ": ");
			numero = sc.nextInt();
			
			if (numero > maior)
			{
				maior = numero;
			}
			
		}
			
		
		System.out.print("Número maior: " + maior);
			
			
	}

}
