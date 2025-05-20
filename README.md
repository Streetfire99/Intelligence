# Intelligence

Un'applicazione web per la gestione e la fruizione di contenuti didattici, sviluppata con Python e MkDocs.

## Caratteristiche

- Generazione automatica della struttura di navigazione per la documentazione
- Download e organizzazione di risorse didattiche (PDF, audio, video)
- Interfaccia web responsive e user-friendly
- Supporto per contenuti multilingua

## Requisiti

- Python 3.11 o superiore
- ffmpeg (per la gestione dei file audio/video)
- Dipendenze Python (vedi requirements.txt)

## Installazione

1. Clona il repository:
```bash
git clone https://github.com/giacomocavalcabo/Intelligence.git
cd Intelligence
```

2. Crea e attiva un ambiente virtuale:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# oppure
.\venv\Scripts\activate  # Windows
```

3. Installa le dipendenze:
```bash
pip install -r requirements.txt
```

## Utilizzo

1. Configura le credenziali nel file `config.json`
2. Esegui lo script di download dei contenuti:
```bash
python download_pdfs.py
```

3. Genera la struttura di navigazione:
```bash
python generate_nav.py
```

4. Avvia l'applicazione web:
```bash
cd intelligence-app
mkdocs serve
```

## Struttura del Progetto

- `intelligence-app/`: Directory principale dell'applicazione web
- `downloads_2/`: Directory per i contenuti scaricati
- `scripts/`: Script Python per la gestione dei contenuti

## Contribuire

Le pull request sono benvenute. Per modifiche importanti, apri prima un issue per discutere cosa vorresti cambiare.

## Licenza

[MIT](https://choosealicense.com/licenses/mit/) 