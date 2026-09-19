# HTML e CSS di base

Tipologia: lezione pratica + esercizi + verifica

## Lezione pratica

Una pagina web è un documento HTML: un insieme di tag che ne descrivono
la struttura (titoli, paragrafi, immagini, tabelle, link), mentre il CSS
ne descrive l'aspetto (colori, font, spaziatura, layout).

Struttura minima di una pagina:

```html
<!DOCTYPE html>
<html lang="it">
  <head>
    <meta charset="utf-8" />
    <title>La mia pagina</title>
    <link rel="stylesheet" href="stile.css" />
  </head>
  <body>
    <h1>Titolo principale</h1>
    <p>Un paragrafo di testo.</p>
  </body>
</html>
```

Il CSS si può collegare in tre modi: inline (attributo `style`), in un
blocco `<style>` nell'head, oppure in un file `.css` collegato con
`<link>` — quest'ultimo è il metodo consigliato per pagine più grandi.

## Esercizi

1. **Pagina personale**: crea una pagina HTML con un titolo (`h1`), una
   breve descrizione (`p`), un elenco puntato di 3 interessi (`ul`/`li`)
   e un'immagine. Collega un file CSS separato che cambi colore di
   sfondo, font e colore del titolo.

2. **Tabella prodotti**: crea una tabella HTML con almeno 4 colonne
   (Prodotto, Prezzo, Disponibilità, Categoria) e 5 righe di dati
   inventati. Usa il CSS per alternare il colore di sfondo delle righe
   pari/dispari e per mettere in grassetto l'intestazione.

## Verifica (traccia di esempio)

Crea una pagina "Chi siamo" per un'attività immaginaria a tua scelta
(es. una libreria, un negozio di sport, uno studio fotografico):

- un'intestazione con nome dell'attività e un breve slogan;
- una sezione con 3 paragrafi che descrivono l'attività;
- una tabella con gli orari di apertura (giorno / orario mattina /
  orario pomeriggio);
- un foglio di stile CSS separato che dia un aspetto coerente alla
  pagina (palette di colori, font, spaziatura).

Tempo indicativo: 1 ora.
