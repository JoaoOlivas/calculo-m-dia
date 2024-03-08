import java.util.Scanner;
public class teste {

    public static void main(String []args)
    {
    try (Scanner teclado = new Scanner (System.in)) {
        Double A;
        Double B;
        Double C;
        Double N;
        double soma;
        double media;

        System.out.println("Digite o valor de A");
         A = teclado.nextDouble();
         System.out.println("Digite o valor de B");
         B = teclado.nextDouble();
         System.out.println("Digite o valor de C");
         C = teclado.nextDouble();
         System.out.println("Digite o numero 3 ");
         N = teclado.nextDouble();

         media= (N/(1/A)+(1/B)+(1/C));

         soma= A+B+C/3;

         System.out.println("A media aritimetica da:"+soma);
         System.out.println("A media Harmonica:"+media);
    }
   
    }
