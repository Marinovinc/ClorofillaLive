# Clorofilla Live

App web (single-file, client-side) per visualizzare la clorofilla del mare da satellite.

**Live:** https://marinovinc.github.io/ClorofillaLive/

## Funzioni
- Overlay clorofilla satellitare (Copernicus Marine / NASA PACE) + SST + fondale EMODnet.
- **Interpretazione biologica**: finestra foraggio 0,20–0,50 mg/m³, rilevamento fronti
  (gradiente ≥ 0,20 mg/m³) e hot-spot per grandi pelagici.
- Lettura puntuale al click, calcolo fronte (color line), percorso animato, export CSV/KML/GPX.

## Uso su cellulare
Aprire il link in Safari/Chrome → "Aggiungi a Home". Richiede connessione dati
(le sorgenti satellitari sono live).

## Note
- Tutto client-side: nessun server, nessuna credenziale nel codice.
- Cartella `images/`: icone standard Leaflet (controllo layer + marker).
