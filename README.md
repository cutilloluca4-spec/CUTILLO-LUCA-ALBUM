# L'Album di Luca

Un sito-gioco a forma di album di figurine: si strappa la bustina, si girano le figurine e si attaccano nell'album.
Quattro bustine, sedici figurine, nessun doppione. La olografica arriva sempre per ultima.

## Aprirlo
Apri `index.html` nel browser, oppure in VS Code con l'estensione Live Server.

## Struttura
- `index.html`: tutto il sito (HTML, CSS, JavaScript in un file)
- `assets/luca-cutout.webp`: la foto scontornata usata in tutte le figurine (il bianco e nero lo applica il sito)
- `assets/luca.jpg`: la foto originale ritagliata
- `assets/castelverde.png`: stemma A.C. Castelverde (figurine 01, 04 e 06)

## Dove modificare
- Testi delle figurine: array `DATA` nello script
- Disegni e costumi: oggetto `V` (un elemento per figurina, coordinate SVG 200x224); `face` e `hat` sono gli accessori sul volto
- Trattamento della foto (bianco e nero contrastato): oggetto `PALS` e funzione `head`
- Pagine dell'album: array `SPREADS`
- Colori e font: variabili `:root` in cima al CSS

## Pubblicarlo su GitHub Pages
Carica la cartella in un repository, poi Settings > Pages > Deploy from branch > `main` / root.
