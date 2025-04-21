
public class Main {
 public static void main(String[] args) {
 Contador cont = new Contador();
 cont.contarAte(10); 
 }


}

class Contador {
 public void contarAte(double limite) {
     
     
int soma = 0;     
 for (int i = 0 ; i <= limite;  i++) {
    soma = soma + i;


 
 } System.out.println("A soma dos números até 10 é: " + soma);
double media;
media = soma / limite ;
 System.out.println("A média dos números somados é:" + media );
 
 }
}


