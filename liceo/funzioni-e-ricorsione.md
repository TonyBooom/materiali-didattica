# Funzioni e ricorsione in C++

Tipologia: lezione pratica + esercizi + verifica

## Lezione pratica

Una funzione è un blocco di codice riutilizzabile, con un nome, un
tipo di ritorno e parametri:

```cpp
int quadrato(int n) {
    return n * n;
}
```

I parametri possono essere passati per valore (la funzione lavora su
una copia) o per riferimento (`&`, la funzione modifica direttamente
la variabile originale).

Una funzione **ricorsiva** è una funzione che chiama se stessa, fino a
raggiungere un **caso base** che ferma le chiamate:

```cpp
int fattoriale(int n) {
    if (n <= 1) return 1;       // caso base
    return n * fattoriale(n - 1); // passo ricorsivo
}
```

## Esercizi

1. **Funzioni di base**: scrivi tre funzioni: una che restituisce il
   maggiore tra due numeri, una che verifica se un numero è primo, una
   che scambia il contenuto di due variabili passate per riferimento.

2. **Ricorsione**: scrivi in versione ricorsiva una funzione che
   calcola la somma dei primi n numeri naturali e una che calcola
   l'n-esimo termine della sequenza di Fibonacci.

## Verifica (traccia di esempio)

1. Scrivi una funzione ricorsiva `contaCifre(int n)` che restituisce
   quante cifre ha un numero intero positivo.
2. Scrivi la versione iterativa della stessa funzione e spiega a
   parole una differenza pratica tra le due versioni (es. uso della
   memoria, leggibilità).
3. Scrivi una funzione (non ricorsiva) che riceve un array e un valore
   per riferimento, e mette in quella variabile la posizione del primo
   elemento negativo trovato (o -1 se non esiste).

Tempo indicativo: 1 ora.
