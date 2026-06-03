# Portfolio premium argento — sfondo pulito + blocco immagine

Versione modificata:
- rimossi i quadrati/griglia dallo sfondo;
- aggiunto un blocco immagine accanto al nome nella homepage;
- mantenuta la grafica premium nero + argento/cromo.

## Come inserire la tua immagine
Nel file `index.html` cerca:

<div class="image-placeholder">

Puoi sostituire tutto il blocco con:

<img class="hero-photo" src="assets/img/foto.jpg" alt="Foto profilo">

Poi crea la cartella:
assets/img/

e inserisci dentro la tua immagine chiamandola:
foto.jpg

Se vuoi che l'immagine riempia bene il blocco, aggiungi nel CSS:

.hero-photo{
  width:100%;
  height:560px;
  object-fit:cover;
}
