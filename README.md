# nechcisevzbudit
// 1. Sčítání
function secti(a, b) {
    return a + b;
}

// 2. Odčítání
function odecti(a, b) {
    return a - b;
}

// 3. Násobení
function vynasob(a, b) {
    return a * b;
}

// 4. Dělení
function vydel(a, b) {
    if (b !== 0) {
        return a / b;
    } else {
        console.log("Chyba: Nelze dělit nulou.");
        return 0; // Speciální hodnota pro označení chyby
    }
}

// 5. Umocnění
function umocni(zaklad, exponent) {
    let vysledek = 1;
    for (let i = 0; i < exponent; i++) {
        vysledek *= zaklad;
    }
    return vysledek;
}

// 6. Maximum
function maximum(a, b) {
    return Math.max(a, b);
}

// 7. Minimum
function minimum(a, b) {
    return Math.min(a, b);
}

// 8. Výpis čísel od 1 do 5
let i = 1;

while (i <= 5) {
    console.log("Číslo: " + i);
    i++;
}

// 9. Sudá čísla do 10
let j = 2;

while (j <= 10) {
    console.log("Sudé číslo: " + j);
    j += 2;
}
