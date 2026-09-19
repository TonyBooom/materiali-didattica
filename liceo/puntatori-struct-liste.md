# Puntatori, struct e liste in C++

Tipologia: lezione pratica + esercizi + verifica

## Lezione pratica

Un puntatore è una variabile che contiene l'indirizzo di memoria di
un'altra variabile:

```cpp
int x = 10;
int *p = &x;   // p punta a x
*p = 20;       // modifica x tramite il puntatore (dereferenziazione)
```

Una `struct` raggruppa più campi (anche di tipo diverso) in un'unica
entità:

```cpp
struct Persona {
    string nome;
    int eta;
};
```

Una lista collegata è una sequenza di nodi, ciascuno con un campo dato
e un puntatore al nodo successivo (`next`); è utile quando non si
conosce a priori il numero di elementi.

## Esercizi

1. **Struct**: definisci una struct `Prodotto` (nome, prezzo,
   quantità) e un array di 5 struct di questo tipo. Scrivi una
   funzione che restituisca il prodotto con il prezzo più alto.

2. **Puntatori**: scrivi una funzione che, dato un array e la sua
   dimensione, lo inverta usando due puntatori (uno all'inizio, uno
   alla fine) che si scambiano avvicinandosi.

## Verifica (traccia di esempio)

1. Cosa stampa questo codice? Motiva la risposta.
   ```cpp
   int a = 5;
   int *p = &a;
   *p = *p + 3;
   cout << a;
   ```
2. Definisci una struct `Nodo` con un campo intero e un puntatore al
   nodo successivo, e scrivi una funzione che, data la testa di una
   lista, conti quanti nodi contiene.
3. Spiega a parole la differenza tra un array e una lista collegata,
   citando almeno un vantaggio e uno svantaggio di ciascuno.

Tempo indicativo: 1 ora.
