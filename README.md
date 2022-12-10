# Programacao-de-Solucoes-Computacionais-Ex03-Lista05
Faça um programa, com uma função que necessite de três argumentos, e que forneça a soma desses três argumentos.
import java.util.Scanner;

public class Ex03 {
    public static void main(String[] args) throws Exception {
        Scanner sc = new Scanner(System.in);
        System.out.print("Informe o primeiro número: ");
        double n1 = sc.nextDouble();
        System.out.println("");
        System.out.print("Informe o segundo número: ");
        double n2 = sc.nextDouble();
        System.out.println("");
        System.out.print("Informe o terceiro número: ");
        double n3 = sc.nextDouble();
        System.out.println("");
        sc.close();
        double soma = (n1 + n2 + n3);
        System.out.println("A soma dos numeros é: " + soma);
    }
}
