# Taksimetre
Taksimetre

import java.util.Scanner;

public class taksimetre {
    public static void main(String[] args) {

        int km;
        double perkm=2.20,total,startPrice=10;


        Scanner input=new Scanner(System.in);
        System.out.println("Mesafeyi Km Cinsinden Giriniz : ");
        km=input.nextInt();

        total=  (km*perkm);
        total+=startPrice;

        total=(total <20)? 20 :total;

        System.out.println("Toplam Turar " + total);



    }
}
