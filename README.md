# chamada-em-looping
import java.util.Scanner;

public class Main {
public static void main(String[] args) {
Scanner sc = new Scanner(System.in);

System.out.print("Quantos alunos? ");
int qtdAlunos = sc.nextInt();

for (int i = 1; i <= qtdAlunos; i++) {
System.out.println("\nAluno " + i);

System.out.print("n 1: ");
double n1 = sc.nextDouble();

System.out.print("n 2: ");
double n2 = sc.nextDouble();

System.out.print("n 3: ");
double n3 = sc.nextDouble();


double media = (n1 + n2 + n3) / 3;

String situacao = media >= 7.0 ? "Aprovado"
: media >= 5.0 ? "Recuperação" : "Reprovado";

System.out.println("Aluno com media " + media + " está em situação de: " + situacao);
}
}
}