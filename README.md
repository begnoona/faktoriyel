import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
    
   /*N elemanlı bir kümenin elemanları ile oluşturulacak
   r elemanlı farklı grupların sayısı
   n’in r’li kombinasyonu olarak adlandırılır.
    N’in r’li kombinasyonu C(n,r) şeklinde gösterilir.
    Java ile kombinasyon hesaplayan program yazınız.
    */
    
        int n,r,c,toplam=1,toplam1=1;
        
    Scanner input= new Scanner(System.in);
    
    System.out.print("n elemanını giriniz: ");
    n=input.nextInt();
    
    System.out.print("r elemanını giriniz: ");
    r=input.nextInt();
    
    for(int i=1;i<=n;i++){
        toplam=toplam*i;


    }
    System.out.println(toplam);
    
    for(int k=1;k<=r;k++){
        toplam1=toplam1*k;
    }
    
    System.out.println(toplam1);
    
 c=toplam/toplam1;
 
 System.out.print(c);












    }
}
