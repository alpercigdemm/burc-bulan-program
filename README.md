# Burç Bulan Program

* Koç Burcu : 21 Mart - 20 Nisan

* Boğa Burcu : 21 Nisan - 21 Mayıs

* İkizler Burcu : 22 Mayıs - 22 Haziran

* Yengeç Burcu : 23 Haziran - 22 Temmuz

* Aslan Burcu : 23 Temmuz - 22 Ağustos

* Başak Burcu : 23 Ağustos - 22 Eylül

* Terazi Burcu : 23 Eylül - 22 Ekim

* Akrep Burcu : 23 Ekim - 21 Kasım

* Yay Burcu : 22 Kasım - 21 Aralık

* Oğlak Burcu : 22 Aralık - 21 Ocak

* Kova Burcu : 22 Ocak - 19 Şubat

* Balık Burcu : 20 Şubat - 20 Mart

**ÖDEV**
* Aynı örneği switch-case kullanmadan yapınız.

**CEVAP:**

```
import java.util.Scanner;

public class BurcBulanProgram {
    public static void main(String[] args) {

        int month,day;

        Scanner inp = new Scanner(System.in);

        System.out.print("Dogdugunuz Ay : ");
        month = inp.nextInt();

        System.out.print("Dogdugunuz Gun : ");
        day = inp.nextInt();

        if(month == 1){
            if (day <22){
                System.out.println("Burcunuz : Oglak");
            }
            else {
                System.out.println("Burcunuz : Kova");
            }
        }
        if (month ==2){
            if (day < 20){
                System.out.println("Burcunuz : Kova");
            }
            else {
                System.out.println("Burcunuz : Balik");
            }
        }
        if (month == 3){
            if (day < 21){
                System.out.println("Burcunuz : Balik");
            }
            else {
                System.out.println("Burcunuz : Koc");
            }
        }
        if (month == 4){
            if (day < 21){
                System.out.println("Burcunuz : Koc");
            }
            else {
                System.out.println("Burcunuz : Boga");
            }
        }
        if (month == 5){
            if (day < 22){
                System.out.println("Burcunuz : Boga");
            }
            else {
                System.out.println("Burcunuz : Ikizler");
            }
        }
        if (month == 6){
            if (day < 23){
                System.out.println("Burcunuz : Ikızler");
            }
            else {
                System.out.println("Burcunuz : Yengec");
            }
        }
        if (month == 7){
            if (day < 23){
                System.out.println("Burcunuz : Yengec");
            }
            else {
                System.out.println("Burcunuz : Aslan");
            }
        }
        if (month == 8){
            if (day < 23){
                System.out.println("Burcunuz : Aslan");
            }
            else {
                System.out.println("Burcunuz : Basak");
            }
        }
        if (month == 9){
            if (day < 23){
                System.out.println("Burcunuz : Basak");
            }
            else {
                System.out.println("Burcunuz : Terazi");
            }
        }
        if (month == 10){
            if (day < 23){
                System.out.println("Burcunuz : Terazi");
            }
            else {
                System.out.println("Burcunuz : Akrep");
            }
        }
        if (month == 11){
            if (day < 22){
                System.out.println("Burcunuz : Akrep");
            }
            else {
                System.out.println("Burcunuz : Yay");
            }
        }
        if (month == 12){
            if (day < 22) {
                System.out.println("Burcunuz : Yay");
            }
            else {
                System.out.println("Burcunuz : Oglak");
            }
        }
    }
}

```
www.patika.dev
