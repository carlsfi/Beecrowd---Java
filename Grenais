import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        
        int i = 1;
        int vi = 0;
        int vg = 0;
        int em = 0;
        int qnt = 0;

        while(i == 1){
            int x = sc.nextInt();
            int y = sc.nextInt();
    
            if(x > y){
                vi++;
            }
            else if(x < y){
                vg++;
            }
            else if(x == y){
                em++;
            }
            qnt++;
    
            System.out.println("Novo grenal (1-sim 2-nao)");
            i = sc.nextInt();
        }
        System.out.println(qnt + " grenais");
        System.out.println("Inter:" + vi);
        System.out.println("Gremio:" + vg);
        System.out.println("Empates:" + em);
        if(vi > vg){
            System.out.println("Inter venceu mais");
        }
        else if(vg > vi){
            System.out.println("Gremio venceu mais");
        }
        else if(vi == vg){
            System.out.println("Nao houve vencedor");
        }
        sc.close();
    }
}
