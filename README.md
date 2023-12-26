# java101
java
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        //degiskenler olustur
        int mat,fizik,kim,turkce,tarih,muzik;
        //scanner sınıfı tanımlandı
        Scanner imp = new Scanner(System.in);
        //kulllanıcı değerlerni al
        System.out.println("Matematik notunuzu girin :");
        mat = imp.nextInt();


        System.out.println("Fizik notunuzu girin :");
        fizik = imp.nextInt();


        System.out.println("Kimya notunuzu girin ;");
        kim = imp.nextInt();

        System.out.println("Türkçe notunuzu girin ;");
        turkce = imp.nextInt();

        System.out.println("Tarih notunuzu gitin ;");
        tarih = imp.nextInt();

        System.out.println("Müzik notunuzu gitin ;");
        muzik = imp.nextInt();

        int toplam = (mat + kim + fizik + tarih + turkce + muzik);
        double sonuc = toplam/6.0;
        System.out.println("Ortalamanız :" + sonuc);
    }
}
