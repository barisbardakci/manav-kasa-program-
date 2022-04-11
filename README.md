# manav-kasa-program-
Java101_6 Alınan ürünlerin kilolarını girerek toplam tutar hesaplayan manav kasa programı

/* Ödev Patika.dev
Manav Kasa Programı
Java ile kullanıcıların manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran programı yazın.

Meyveler ve KG Fiyatları

Armut : 2,14 TL
Elma : 3,67 TL
Domates : 1,11 TL
Muz: 0,95 TL
Patlıcan : 5,00 TL
*/

import java.util.Scanner ;

public class Main {
    public static void main (String[] args) {
        double arm=2.14, el=3.67, dom=1.11, mu=0.95, pa=5.00 ;
    
        Scanner input=new Scanner(System.in);
        
        System.out.print("Armut Kaç Kilo? :");
        double armut=input.nextDouble();
        System.out.print("Elma Kaç Kilo? :");
        double elma=input.nextDouble();
        System.out.print("Domates Kaç Kilo? :");
        double domates=input.nextDouble();
        System.out.print("Muz Kaç Kilo? :");
        double muz=input.nextDouble();
        System.out.print("Patlıcan Kaç Kilo? :");
        double patlıcan=input.nextDouble();
        
        double kasa=(arm*armut)+(el*elma)+(dom*domates)+(mu*muz)+(pa*patlıcan) ;

        System.out.print("Toplam tutar "+ kasa );

    }    
    
    
}
