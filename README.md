# ON TRACK — Progressive Web App

## Cos'è
App mobile installabile su Android (e iOS) per presentare il progetto ON TRACK ai stakeholder, finanziatori e al pubblico.

## Struttura file
```
on-track-pwa/
├── index.html      ← App completa (tutto in un file)
├── manifest.json   ← Configurazione PWA (icona, nome, colori)
├── sw.js           ← Service Worker (funzionamento offline)
└── README.md       ← Questo file
```

## Contenuto dell'app
- **Home** — KPI chiave, mission, finanziamento
- **Progetto** — Fasi operative, timeline, dati chiave
- **Partner** — 7 organizzazioni con ruoli e budget
- **Territorio** — 5 zone operative, obiettivi quantitativi
- **Contatti** — Link portale, sito FPdM, finanziatori

## Come pubblicarla (gratis)

### Opzione 1 — GitHub Pages (consigliata)
1. Crea account su github.com (gratuito)
2. Crea repository pubblico "on-track-pwa"
3. Carica i 3 file (index.html, manifest.json, sw.js)
4. Vai su Settings → Pages → Source: main branch
5. L'app sarà disponibile su: `https://[tuo-username].github.io/on-track-pwa`

### Opzione 2 — Netlify Drop
1. Vai su netlify.com/drop
2. Trascina la cartella on-track-pwa
3. Ottieni URL istantaneo (es: https://on-track-xyz.netlify.app)

### Opzione 3 — Integrazione Google Sites
Incolla l'URL della PWA nel portale ON TRACK esistente come link diretto.
Gli utenti Android vedranno automaticamente il banner "Aggiungi alla schermata home".

## Come installarla su Android
1. Aprire l'URL nel browser Chrome
2. Apparirà il banner in basso: "Aggiungi ON TRACK alla schermata home"
3. Toccare "Installa"
4. L'app appare nella schermata home come un'app nativa

## Icone (da aggiungere)
Per completare la PWA, aggiungere:
- `icon-192.png` — Logo ON TRACK 192×192px
- `icon-512.png` — Logo ON TRACK 512×512px

## Aggiornamento contenuti
Tutti i contenuti sono nell'unico file `index.html`.
Modificare il file e ricaricarlo sul server per aggiornare l'app.
