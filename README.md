# Fanta Sanremo

## English

A web app for tracking a "Fantasy Sanremo" competition among friends. Each participant picks singers from the Sanremo Music Festival roster; the app fetches live scores from the official FantaSanremo API and calculates each participant's total points based on their chosen artists.

### Features
- Fetches real-time artist scores from the FantaSanremo API
- Loads participant data and their chosen singers from a local JSON file
- Calculates total points per participant (regular + captain bonus)
- Displays a ranked leaderboard with gold/silver/bronze trophies
- Optional file-upload mode for updating participant data via URL parameter (`?file=1`)

### Tech Stack
- HTML5, CSS3, JavaScript (vanilla)
- jQuery 3.7.1
- SheetJS (xlsx.js) for Excel file parsing
- JSZip

### Data files
- `database/partecipanti.json` — participants and their chosen singers
- `database/punteggi.json` — cached scores (optional)

### How to run
Open `index.html` in a browser (requires a local server or CORS-permissive environment to fetch the FantaSanremo API and local JSON files).

---

## Italiano

Web app per seguire una competizione di "Fanta Sanremo" tra amici. Ogni partecipante sceglie dei cantanti dal roster del Festival di Sanremo; l'app recupera i punteggi live dall'API ufficiale di FantaSanremo e calcola il totale di punti di ciascun partecipante in base agli artisti scelti.

### Funzionalità
- Recupera i punteggi degli artisti in tempo reale dall'API FantaSanremo
- Carica i dati dei partecipanti e i loro cantanti scelti da un file JSON locale
- Calcola il totale punti per partecipante (normali + bonus capitano)
- Mostra una classifica con trofei oro/argento/bronzo
- Modalità upload opzionale per aggiornare i dati dei partecipanti tramite parametro URL (`?file=1`)

### Stack tecnologico
- HTML5, CSS3, JavaScript (vanilla)
- jQuery 3.7.1
- SheetJS (xlsx.js) per il parsing di file Excel
- JSZip

### File di dati
- `database/partecipanti.json` — partecipanti e i loro cantanti scelti
- `database/punteggi.json` — punteggi in cache (opzionale)

### Come eseguire
Apri `index.html` in un browser (richiede un server locale o un ambiente che permetta CORS per recuperare l'API FantaSanremo e i file JSON locali).

---

*Author: Giovanni Romeo*
