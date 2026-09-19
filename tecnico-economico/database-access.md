# Database relazionali e MS Access

Tipologia: lezione pratica + esercizi + verifica

## Lezione pratica

Un database relazionale organizza i dati in tabelle collegate tra loro
tramite chiavi. Ogni tabella rappresenta un'entità (es. Clienti,
Ordini, Prodotti); le righe sono i record, le colonne sono i campi.

Concetti chiave:

- **Chiave primaria**: campo che identifica in modo univoco ogni record
  (es. CodiceCliente).
- **Chiave esterna**: campo che, in una tabella, fa riferimento alla
  chiave primaria di un'altra tabella, creando la relazione.
- **Query**: interrogazione che estrae dati da una o più tabelle,
  eventualmente con condizioni (query con criteri) o parametri
  (query parametriche).
- **Maschera**: interfaccia per inserire o consultare i dati senza
  aprire direttamente le tabelle.

## Esercizi

1. **Progettazione tabelle**: progetta un piccolo database per la
   gestione di una biblioteca, con almeno due tabelle collegate
   (es. Libri e Prestiti). Individua per ciascuna tabella i campi, la
   chiave primaria e, dove serve, la chiave esterna.

2. **Query con criteri**: partendo dal database progettato al punto 1,
   scrivi (anche solo a parole o in pseudocodice SQL) una query che
   estragga tutti i libri attualmente in prestito e una query
   parametrica che, dato il nome di un utente, restituisca tutti i
   libri che ha in prestito.

## Verifica (traccia di esempio)

1. Spiega la differenza tra chiave primaria e chiave esterna, con un
   esempio che non sia quello della biblioteca.
2. Dato uno scenario di un negozio con le tabelle `Prodotti` (CodiceProdotto,
   Nome, Prezzo) e `Vendite` (CodiceVendita, CodiceProdotto, Quantità,
   Data), scrivi la query che calcola il totale venduto per ogni
   prodotto.
3. A cosa serve una maschera in un database, e perché non si dà
   normalmente accesso diretto alle tabelle agli utenti finali?

Tempo indicativo: 1 ora.
