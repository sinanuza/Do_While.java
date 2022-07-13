# Do_While.java
www.patika.dev Do While Odev


        import java.util.Scanner;

        public class Donguler {
        public static void main(String[] args) {
        int k,i,sum;
        sum=0;
        Scanner input= new Scanner(System.in);
        do {
            System.out.println("Lutfen sayi giriniz:");
            k = input.nextInt();
            if (k%4==0) {
                sum=sum+k;
            }
        }while (k % 2 == 0);
            System.out.println("Toplam:"+sum);
    }
}
