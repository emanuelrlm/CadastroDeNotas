package AprendizDeJava;

import java.util.Scanner;

public class Matriz {
	
public static void main(String[] args) {
		
Scanner scan = new Scanner (System.in);

String Aluno; 
System.out.println("Digite o nome do aluno");
Aluno = scan.next();

int[] notasdasprovas = new int[2];
for ( int i = 0; i < notasdasprovas.length; i++){
System.out.println("Digite as notas das provas");
notasdasprovas[i] = scan.nextInt();}

for ( int i = 0; i < notasdasprovas.length; i++){
System.out.println("As notas foram lancadas foram" + notasdasprovas[i]);}

float media = (float)(notasdasprovas[0] + notasdasprovas[1])/2;
System.out.println("A media foi" + media);
if (media > 6) {System.out.println("Aluno aprovado");}
else{System.out.println ("Aluno reprovado");}

}
}


