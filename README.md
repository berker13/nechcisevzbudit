# nechcisevzbudit
public class MatematickeKalkulacka {

    // 1. Sčítání
    public static int secti(int a, int b) {
        return a + b;
    }

    // 2. Odčítání
    public static int odecti(int a, int b) {
        return a - b;
    }

    // 3. Násobení
    public static int vynasob(int a, int b) {
        return a * b;
    }

    // 4. Dělení
    public static int vydel(int a, int b) {
        if (b != 0) {
            return a / b;
        } else {
            System.out.println("Chyba: Nelze dělit nulou.");
            return 0; // Speciální hodnota pro označení chyby
        }
    }

    // 5. Umocnění
    public static int umocni(int zaklad, int exponent) {
        int vysledek = 1;
        for (int i = 0; i < exponent; i++) {
            vysledek *= zaklad;
        }
        return vysledek;
    }

    // 6. Maximum
    public static int maximum(int a, int b) {
        return Math.max(a, b);
    }

    // 7. Minimum
    public static int minimum(int a, int b) {
        return Math.min(a, b);
    }

    // 8. Výpis čísel od 1 do 5

    public static void main(String[] args) {
        int i = 1;

        while (i <= 5) {
            System.out.println("Číslo: " + i);
            i++;
        }
    }

    // 9. Sudá čísla do 10

    public static void main(String[] args) {
        int i = 2;

        while (i <= 10) {
            System.out.println("Sudé číslo: " + i);
            i += 2;
        }
    }
}

}


    public static void main(String[] args) {
        // Zde můžete volat jednotlivé metody a vypisovat výsledky
    }
}

