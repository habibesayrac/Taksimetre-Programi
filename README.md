# Taksimetre-Programi
import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

   int uzaklık,acmaUcreti;
   acmaUcreti =10;
   double tutar;
   Scanner input = new Scanner(System.in);
        System.out.println("Kaç km yol alındığını Giriniz: ");
        uzaklık = input.nextInt();
       tutar = acmaUcreti+ uzaklık*2.20;
        if(tutar<20) {
            System.out.println("Ödeyeceğiniz Tutar : " + 20);
        } else{
            System.out.println("Ödeyeceğiniz Tutar: " + tutar);
            }
        }
}
