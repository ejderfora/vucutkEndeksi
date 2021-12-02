```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        Scanner inp = new Scanner(System.in);

        double boy;
        double kg;
        double vki;

        System.out.print("Boyunuzu Girin(Metre Cinsinden): ");
        boy = inp.nextDouble();

        System.out.print("Kilonuzu Girin: ");
        kg = inp.nextDouble();
        vki = kg / (boy * boy);

        System.out.print("Vücut Kitle İndeksiniz: " + vki);


    }
}
```
