# 🐸 Rana Laurea — Sito Festa di Laurea Victoria Rozhko

Sito interattivo per la festa di laurea di Victoria "Rana" Rozhko — Economia e Marketing Internazionale, Unimore 2025.

## 📁 Struttura del progetto

```
rana-laurea/
├── index.html          ← Pagina principale
└── games/
    ├── slot.html       ← 🎰 Slot Machine della Laurea
    ├── grafici.html    ← 📊 Grafici Assurdi
    ├── copertina.html  ← 📰 Copertina Vintage
    ├── paese.html      ← 🌍 Marketing Internazionale (quiz)
    ├── oracolo.html    ← 🔮 Oracolo del Mercato
    ├── asta.html       ← 🏦 Asta Alcolica
    └── roulette.html   ← 🎲 Roulette degli Shot
```

---

## 🚀 Come pubblicarlo su GitHub Pages (gratis)

### 1. Crea un account GitHub
Vai su [github.com](https://github.com) e registrati se non ce l'hai.

### 2. Crea un nuovo repository
- Clicca su **"New repository"** (pulsante verde in alto a destra)
- Nome: `rana-laurea` (o quello che vuoi)
- Lascialo **Public**
- **Non** spuntare nulla (niente README, niente .gitignore)
- Clicca **"Create repository"**

### 3. Carica i file
Hai due opzioni:

#### Opzione A — Da browser (più semplice)
1. Nella pagina del repository appena creato, clicca **"uploading an existing file"**
2. Trascina TUTTI i file nella finestra:
   - `index.html`
   - La cartella `games/` con tutti i suoi file HTML dentro
3. Scrivi un messaggio tipo "Prima versione" e clicca **Commit changes**

#### Opzione B — Da terminale (se hai Git installato)
```bash
cd /percorso/della/cartella/rana-laurea
git init
git add .
git commit -m "🐸 Prima versione"
git branch -M main
git remote add origin https://github.com/TUO-USERNAME/rana-laurea.git
git push -u origin main
```

### 4. Attiva GitHub Pages
1. Vai nel repository su GitHub
2. Clicca su **Settings** (in alto, la rotella)
3. Nel menu a sinistra clicca **Pages**
4. Sotto "Source" seleziona **"Deploy from a branch"**
5. Scegli branch: **main**, cartella: **/ (root)**
6. Clicca **Save**

### 5. Aspetta 1-2 minuti e visita il sito!
Il link sarà tipo:
```
https://TUO-USERNAME.github.io/rana-laurea/
```

---

## 🔧 Personalizzare le foto

Nella pagina principale (`index.html`) ci sono 6 riquadri foto cliccabili.
Durante la festa, chiunque può cliccare su un riquadro e caricare una foto dal proprio dispositivo.

Se vuoi mettere foto già pronte prima della festa:
1. Metti le immagini nella cartella del progetto (es. `foto1.jpg`)
2. Nel codice di `index.html`, cerca `img id="img-0"` e cambia `src=""` con `src="foto1.jpg"`

## 💌 Messaggi degli amici

I messaggi aggiunti durante la festa non vengono salvati automaticamente (si resettano al refresh).
Se vuoi messaggi permanenti, aggiungili direttamente nell'HTML di `index.html` nella sezione `messagesGrid`.

---

## 🐸 Buona festa!

*"Tipo… ce l'ho fatta. Tipo."* — Victoria Rozhko, Dott.ssa in Economia e Marketing Internazionale
