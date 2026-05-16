# 2048 Spill

En klassisk 2048 puslespill-implementasjon bygget med vanilla JavaScript. Skyv nummererte fliser på et rutenett for å kombinere dem og lage en flis med tallet 2048.

## 🎮 Om Spillet

Dette er en nettleserbasert implementasjon av det populære 2048-spillet. Målet er å skyve nummererte fliser på et 4×4 rutenett for å kombinere dem og lage en flis med tallet 2048. Når to fliser med samme nummer berører hverandre, smelter de sammen til én med summen deres.

## ✨ Funksjoner

- **Ren Vanilla JavaScript** — Ingen rammeverk eller biblioteker
- **Flissammenslåingslogikk** — Jevn fliskombinasjonmekanikk
- **Rutenettbasert Tilstandshåndtering** — Ren tilstandshåndtering og oppdateringer
- **Tastaturkontroller** — Piltaster for flisbevegelse
- **Responsivt Design** — Fungerer på forskjellige skjermstørrelser
- **Poengsporing** — Hold oversikt over poengsummen din
- **Game Over-deteksjon** — Automatisk deteksjon når ingen trekk er tilgjengelige

## 🛠️ Teknologi

- **HTML5** — Semantisk markup
- **CSS3 / SCSS** — Styling med preprosessor
- **Vanilla JavaScript** — Spilllogikk og DOM-manipulering
- **ES6 Moduler** — Modulær kodestruktur

## 📁 Prosjektstruktur

```
2048/
├── css/           # Kompilerte CSS-filer
├── scss/          # SCSS kildefiler
├── js/            # JavaScript-moduler
├── img/           # Bilder og favicon
├── index.html     # Hoved HTML-fil
└── README.md      # Dokumentasjon
```

## 🚀 Kom i Gang

### Forutsetninger

- En moderne nettleser (Chrome, Firefox, Safari, Edge)
- (Valgfritt) En lokal webserver for utvikling

### Installasjon

1. Klon repositoriet:
```bash
git clone <repository-url>
cd 2048
```

2. Åpne `index.html` i nettleseren din eller bruk en lokal server:
```bash
# Med Python
python -m http.server 8000

# Med Node.js http-server
npx http-server
```

3. Naviger til `http://localhost:8000` i nettleseren din

## 🎯 Hvordan Spille

1. Bruk **piltaster** (↑ ↓ ← →) for å flytte fliser
2. Når to fliser med samme nummer berører hverandre, **smelter de sammen til én**
3. Etter hvert trekk dukker en ny flis opp tilfeldig
4. Målet er å lage en flis med tallet **2048**
5. Spillet slutter når ingen flere trekk er mulige

## 🎓 Læringsmål

Dette prosjektet ble bygget for å øve på:

- **Spilllogikk-implementasjon** — Tilstandshåndtering og spillregler
- **DOM-manipulering** — Dynamiske UI-oppdateringer uten rammeverk
- **Hendelseshåndtering** — Tastaturinput-prosessering
- **Ren Kodearkitektur** — Separasjon av bekymringer
- **Vanilla JavaScript** — Bygge komplekse interaksjoner uten biblioteker

## 📝 Kodehøydepunkter

- **Modulær Struktur** — Spilllogikk separert fra UI-rendering
- **Tilstandshåndtering** — Rene rutenett-tilstandsoppdateringer
- **Kollisjonsdeteksjon** — Flissammenslåingsalgoritme
- **Animasjon** — Jevne flisbevegelser

## 🔧 Utvikling

### SCSS Kompilering

Hvis du endrer SCSS-filer, kompiler dem til CSS:

```bash
# Med sass CLI
sass scss/style.scss css/style.css

# Watch-modus
sass --watch scss:css
```

## 📄 Lisens

Dette prosjektet er lisensiert under vilkårene spesifisert i `LICENSE.txt`.

## 🙏 Anerkjennelser

- Original 2048-spill av Gabriele Cirulli
- Bygget som et læringsprosjekt for å forstå spillmekanikk og vanilla JavaScript

---

**Merk:** Dette er et porteføljeprosjekt som demonstrerer vanilla JavaScript-ferdigheter og grunnleggende spillutvikling.
