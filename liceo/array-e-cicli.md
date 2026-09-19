# Array e cicli in C++

Tipologia: lezione pratica + esercizi + verifica

## Lezione pratica

Un array è una sequenza di elementi dello stesso tipo, memorizzati in
posizioni contigue e accessibili tramite un indice numerico che parte
da 0:

```cpp
int voti[5] = {7, 8, 6, 9, 5};
for (int i = 0; i < 5; i++) {
    cout << voti[i] << endl;
}
```

Operazioni tipiche sugli array: scorrerlo con un ciclo `for`, cercare
un elemento, trovare il massimo/minimo, contare quanti elementi
soddisfano una condizione, confrontare due array.

## Esercizi

1. **Ricerca e conteggio**: dato un array di 10 interi inseriti da
   tastiera, scrivi un programma che stampi il valore massimo, il
   valore minimo e quanti elementi sono maggiori della media
   dell'array.

2. **Elementi in comune**: dati due array di interi di dimensione
   diversa, scrivi un programma che stampi tutti i valori presenti in
   entrambi gli array (senza ripetizioni).

## Verifica (traccia di esempio)

Scrivi un programma C++ che:

1. Legga da tastiera un array di 8 numeri interi.
2. Stampi l'array invertito (dall'ultimo al primo elemento), senza
   usare un secondo array.
3. Calcoli e stampi quante coppie di elementi adiacenti hanno somma
   pari.

Tempo indicativo: 1 ora.
