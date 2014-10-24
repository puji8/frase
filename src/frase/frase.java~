package frase;
import java.util.Scanner;
import java.util.ArrayList;
public class frase {
	public static void main(String[] args) {
		Scanner lector = new Scanner(System.in);
		System.out.println("Posa una frase");
		String frase = lector.nextLine();
		char[] lletra = {'a','b','c','d','e','f','g','h','i','j','k','l'
				,'m','n','o','p','q','r','s','t','u','v','w','x','y','z',' '};
		int[] quantitat = {0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0};
		int contador =0;

		for(int i = 0; i < frase.length(); i++) {
			for(int j = 0 ; j < lletra.length ; j++) {
				if(lletra[j]==frase.charAt(i)){
					quantitat[j]++;
				}
				if(lletra[j]>27){
					contador++;
				}
			}
		}
		for(int i = 0; i < lletra.length ; i++) {
			System.out.print( lletra[i] + " " + quantitat[i]);
			System.out.println();
		}
		System.out.println("hi han " + contador + " numeros");
	}
}