## **ESERCIZIO 1**

Data una costante chiamata BUDGET di 1000 euro, scrivere un algoritmo che prenda una cifra espressa in euro.

Gestire:

- Che la cifra non sia superiore a 1000 euro;
- In caso sia inferiore o uguale, dovrete dividere la cifra inserita in 3 RATE di pagamento e stampare in console un messaggio: “Paga in 3 comode rate da: $valore_calcolato Euro";

TIPS: Dopo la divisione vi uscirà un numero float con tutta la parte decimale, per gestirla e limitare a 2 le cifre dopo la virgola, potete utilizzare la built-in function [**round()**](https://www.php.net/manual/en/function.round.php) in questo modo: **round($valore_calcolato, 2);**

---

## **ESERCIZIO 2**

Scrivere un algoritmo che prenda un anno di nascita (numero intero composto da 4 cifre, solo anno senza specificare giorno o mese) e calcolare l’età effettiva con una sottrazione (ad es. : 2022 - 1992 = 30 ) .

Gestire:

- Caso in cui l’età calcolata sia un numero negativo, visualizzare un messaggio di errore “Il numero da te inserito non può essere elaborato";
- Se l’età ha un valore **compreso** tra 0 e 3, voglio visualizzare il messaggio: “Troppo piccolo per scrivere a macchina. ";
- Se l’età ha un valore **di 4 o superiore** , voglio visualizzare il messaggio: “Il nostro sistema ha calcolato che hai: Hai $variabile_eta_calcolata anni";

---

## **ESERCIZIO 3**

Utilizzando il costrutto Switch, scrivere un algoritmo per una pizzeria che prenda in input  una qualsiasi ordinazione (una stringa).

**Stringa da Verificare - Costo**

- Pizza - 6 Euro;
- Birra - 3 Euro;
- Panino - 8 Euro
- Insalata - Non Disponibile;
- Dessert - 3 Euro;

Scrivere tutte le casistiche qui sopra enunciate in cui, dato in input il nome del prodotto da ordinare, venga stampato in output una frase del tipo:

“Hai ordinato Carne con un costo di 10 Euro";

Gestire anche la casistica in cui venga inserita una pietanza non presente nel menu.
