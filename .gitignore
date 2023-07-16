import java.util.Scanner;

public class HesapMakinesi {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        double sayi1, sayi2, sonuc;
        String operator;

        System.out.print("Birinci sayıyı girin: ");
        sayi1 = scanner.nextDouble();

        System.out.print("İkinci sayıyı girin: ");
        sayi2 = scanner.nextDouble();

        System.out.print("İşlemi seçin (+, -, *, /): ");
        operator = scanner.next();

        switch (operator) {
            case "+":
                sonuc = sayi1 + sayi2;
                System.out.println("Sonuç: " + sonuc);
                break;
            case "-":
                sonuc = sayi1 - sayi2;
                System.out.println("Sonuç: " + sonuc);
                break;
            case "*":
                sonuc = sayi1 * sayi2;
                System.out.println("Sonuç: " + sonuc);
                break;
            case "/":
                if (sayi2 != 0) {
                    sonuc = sayi1 / sayi2;
                    System.out.println("Sonuç: " + sonuc);
                } else {
                    System.out.println("Hata: Sıfıra bölme hatası!");
                }
                break;
            default:
                System.out.println("Hatalı operatör girdiniz.");
                break;
        }
    }
}
