# 漫画 Manga Tracker - Inventario Libreria

Tabella interattiva per gestire l'inventario manga e fumetti della libreria.

## Come pubblicare su GitHub Pages (5 minuti)

### Passo 1: Crea il repository
1. Vai su **github.com** e fai login
2. Clicca il **+** in alto a destra → **New repository**
3. Nome: `manga-tracker` (o quello che preferisci)
4. Metti **Public** 
5. Clicca **Create repository**

### Passo 2: Carica il file
1. Nella pagina del repository vuoto, clicca **"uploading an existing file"**
2. Trascina il file `index.html` nella pagina
3. Clicca **Commit changes**

### Passo 3: Attiva GitHub Pages
1. Vai in **Settings** (icona ingranaggio in alto)
2. Nel menu a sinistra clicca **Pages**
3. Sotto "Source" seleziona **Deploy from a branch**
4. Sotto "Branch" seleziona **main** e cartella **/ (root)**
5. Clicca **Save**
6. Aspetta 1-2 minuti

### Passo 4: Il tuo sito è online!
Il tuo tracker sarà disponibile su:
```
https://TUO-USERNAME.github.io/manga-tracker/
```

## Come funziona

- **I dati si salvano automaticamente** nel localStorage del tuo browser
- Ogni modifica viene salvata istantaneamente
- I dati restano anche se chiudi il browser o spegni il PC
- **Scarica un backup JSON** periodicamente per sicurezza (pulsante verde)
- **Carica un backup** per ripristinare i dati (pulsante blu)

## Funzionalità

- 267 serie/titoli dal tuo inventario
- Griglia visuale volumi posseduti/mancanti
- Clicca un volume per cambiare stato
- Aggiorna "Tot. usciti" quando escono nuovi numeri
- Aggiungi nuove serie
- Filtra per editore, stato (complete/incomplete)
- Esporta CSV per Excel
- Sistema backup/ripristino JSON

## Aggiornare il file

Se ti do una versione aggiornata del file:
1. Vai nel tuo repository su GitHub
2. Clicca su `index.html`
3. Clicca l'icona matita (Edit)
4. Sostituisci tutto il contenuto
5. Clicca **Commit changes**
6. I tuoi dati nel browser NON si perdono (sono salvati a parte nel localStorage)
