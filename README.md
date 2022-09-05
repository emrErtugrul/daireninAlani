# daireninAlani

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        double r1,pi = 3.14,alan,cevre,alfa,r2,sonuc;

        Scanner inp = new Scanner(System.in);

        System.out.println("Lütfen Dairenin Yarı Çapını Giriniz: ");

        r1= inp.nextDouble();

        alan= pi * r1 * r1;

        cevre= 2 * pi * r1;

        System.out.println("Dairenin Alanı: "+alan);

        System.out.println("Dairenin Çevresi: "+cevre);

        System.out.println("Lütfen Dairenin Yarı Çapını Giriniz: ");

        r2= inp.nextDouble();

        System.out.println("Lütfen Dairenin Merkez Açı Ölçüsünü Giriniz: ");

        alfa= inp.nextDouble();

        sonuc=(pi * (r2*r2) * alfa) / 360;

        System.out.println("Dairenin Alanı: "+sonuc);

    }
}