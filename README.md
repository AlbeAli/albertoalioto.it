# albertoalioto.it - Portfolio Professionale

Portfolio personale di Alberto Alioto - Senior RPA Analyst & Developer specializzato in automazione intelligente e AI orchestration.

## 📋 Contenuti

- **index.html** - Homepage con hero section e highlights
- **about.html** - Profilo professionale dettagliato
- **experience.html** - Timeline delle esperienze lavorative
- **skills.html** - Competenze tecniche, soft skills, lingue e certificazioni
- **css/style.css** - Foglio di stile responsivo e moderno

## 🎨 Design

- **Colore primario:** Azzurro (#1e5ba8)
- **Colore secondario:** Giallo (#f4c430)
- **Fully Responsive:** Mobile-first approach
- **Performance:** Nessuna dipendenza esterna, HTML/CSS puro
- **SEO Optimized:** Meta tags e structured markup

## 🚀 Deployment

### GitHub Pages (Gratuito)

1. Crea un repository pubblico su GitHub chiamato `albertoalioto.it` (o il nome che preferisci)
2. Carica i file del progetto
3. Vai su Settings → Pages → Seleziona "Deploy from branch" → main
4. Il sito sarà disponibile su `https://username.github.io/albertoalioto.it`

### Con Dominio Personalizzato

1. Acquista il dominio `albertoalioto.it`
2. Configura i DNS del registrar:
   - Punta i nameserver a GitHub Pages
   - Oppure configura i record A e CNAME
3. Nel file `CNAME` del repository, aggiungi:
   ```
   albertoalioto.it
   ```

## 📁 Struttura Progetto

```
albertoalioto.it/
├── index.html
├── about.html
├── experience.html
├── skills.html
├── css/
│   └── style.css
├── assets/
│   └── cv-alberto-alioto.pdf (da aggiungere)
├── .gitignore
├── README.md
└── CNAME (aggiungere quando dominio è configurato)
```

## 🔧 Setup Locale

1. **Clona il repository:**
   ```bash
   git clone https://github.com/username/albertoalioto.it.git
   cd albertoalioto.it
   ```

2. **Apri il sito localmente:**
   - Doppio click su `index.html`
   - Oppure usa un server HTTP locale:
     ```bash
     python3 -m http.server 8000
     # Accedi a http://localhost:8000
     ```

## 📝 Modifiche Comuni

### Aggiornare il CV

1. Sostituisci il file `assets/cv-alberto-alioto.pdf` con la versione aggiornata
2. Commit e push

### Modifica Colori

Nel file `css/style.css`, modifica le variabili CSS:
```css
:root {
    --primary-color: #1e5ba8;    /* Azzurro */
    --secondary-color: #f4c430;  /* Giallo */
}
```

### Aggiungere Sezioni

Crea un nuovo file HTML (es. `projects.html`) e aggiungi il link nel `navbar` di tutte le pagine.

## ✉️ Contatti nel Footer

Modifica il file `.html` per aggiornare:
- Email: `alberto.alioto@gmail.com`
- Telefono: `+39 340 983 1949`
- LinkedIn: `linkedin.com/in/alberto-alioto/`

## 🔍 SEO

Ogni pagina include:
- Meta description
- Open Graph tags (per social sharing)
- Canonical URLs
- Responsive viewport

## 📱 Responsività

- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

Tutte le breakpoint sono gestite via media queries in `css/style.css`.

## 📦 Nessuna Dipendenza

Questo progetto non richiede:
- Node.js
- npm
- Build tools
- Framework

È completamente autosufficiente con HTML, CSS e JavaScript vanilla.

## 📜 Licenza

© 2025 Alberto Alioto. Tutti i diritti riservati.

## 💡 Tip

Usa GitHub Copilot o Claude per eventualmente automatizzare:
- Aggiornamenti batch di contenuti
- Generazione di nuove pagine
- Ottimizzazione SEO
