# Imc-
IMC


package calcularimc;

import java.util.Scanner;

public class Imc {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner teclado = new Scanner(System.in);
System.out.print("Digite a Altura");
double Altura = teclado.nextDouble();
System.out.print("Digite o Peso");
double Peso = teclado.nextDouble();

double imc = (Peso /(Altura*Altura));

System.out.println("Imc= "+imc);

if(imc<18.5){
	System.out.println ("Você está magro demais com esse Indice!");
}
else{ 
	if(imc>=18.5 && imc<24.9){
		System.out.println("Você está normal com esse Indice!");}
	
}

}

	}
