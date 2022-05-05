# KdvHesaplama
*Java Task*

```java
import java.util.Scanner; //verilerin getirildiği ktphne
public class kdvhesap {
    public static void main(String[] args) {
        double tutar, kdvOran = 0.18, kdvTutar, kdvliTutar;

        Scanner input = new Scanner(System.in); //klavyeden girilen veriyi okumayı sağlar
        System.out.print("Ücret Tutarını Giriniz :");
        tutar = input.nextDouble();

        kdvTutar = tutar * kdvOran;
        kdvliTutar = tutar + kdvTutar;

        System.out.println("KDV'siz Tutar :" + tutar);
        System.out.println("KDV Oranı :" + kdvOran);
        System.out.println("KDV'li Tutarı :" + kdvliTutar);
    }
}   
```

