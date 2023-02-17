import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int soma = 0;
        int contadorR = 0;
        int contadorS = 0;
        int contadorC = 0;
        String letra;
        float porcentagemR = 0,porcentagemS = 0, porcentagemC = 0;
        int n = sc.nextInt();
        
        for (int i = 1; i <= n; i++) {
			int x = sc.nextInt();
			letra =sc.next();
			soma += x;
			
			if (letra.equals("C")) {
				contadorC += x;
			}else if(letra.equals("R")){
				contadorR += x;
			}else if(letra.equals("S")){
				contadorS += x;
			}
			
			porcentagemC = (float)((contadorC * 100.00) /soma);
			porcentagemR = (float)((contadorR * 100.00) /soma);
			porcentagemS = (float)((contadorS * 100.00) /soma);
		}
        System.out.println("Total: " + soma + " cobaias");
        System.out.println("Total de coelhos: " +contadorC);
        System.out.println("Total de ratos: " +contadorR);
        System.out.println("Total de sapos: " +contadorS);
		System.out.printf("Percentual de coelhos: %.2f",porcentagemC);
		System.out.print(" %\n");
		System.out.printf("Percentual de ratos: %.2f",porcentagemR);
		System.out.print(" %\n");
		System.out.printf("Percentual de sapos: %.2f",porcentagemS);
		System.out.print(" %\n");

        sc.close();
    }
}
