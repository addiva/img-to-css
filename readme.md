# Image to CSS Converter

Image to CSS Converter è un semplice strumento web che permette di convertire qualsiasi immagine in un mosaico composto da elementi HTML e CSS. Ogni pixel dell'immagine originale viene trasformato in un `<div>` posizionato assolutamente e colorato con il valore RGBA corrispondente, ricreando così l'immagine senza utilizzare tag `<img>` o proprietà `background-image`.

## Funzionalità principali

- Caricamento di immagini in formato PNG, JPG, WEBP e altri formati comuni
- Conversione automatica dei pixel in elementi HTML con stile CSS
- Ridimensionamento dell'immagine mantenendo le proporzioni
- Anteprima in tempo reale del mosaico generato direttamente nel browser
- Possibilità di copiare il frammento HTML e il CSS di base generati
- Download del file HTML completo pronto per l'uso
- Pulsanti integrati per azioni rapide come reset o caricamento di una nuova immagine
- Sviluppato interamente in HTML, CSS e JavaScript puro, senza librerie esterne

## Come funziona

Il tool utilizza un elemento `<canvas>` invisibile per leggere i dati di ogni pixel dell'immagine caricata. Successivamente, genera dinamicamente un insieme di `<div>` assolutamente posizionati e colorati per ricreare fedelmente l'immagine originale. Il risultato finale è un mosaico costruito unicamente con HTML e CSS, completamente indipendente da risorse esterne.

## Vantaggi e utilizzi

Image to CSS Converter è utile per esperimenti creativi, arte digitale, studi sulla rappresentazione visiva tramite codice e progetti di CSS art. È particolarmente adatto per immagini di piccole dimensioni (fino a 200x200 pixel) e può essere utilizzato per comprendere meglio il funzionamento dei layout assoluti e della manipolazione dei colori in CSS.

## Licenza

Il progetto è distribuito sotto licenza MIT e può essere utilizzato, modificato e condiviso liberamente.
