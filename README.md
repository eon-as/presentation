# Eon AS — Firmapresentasjon

En offline single-file HTML-presentasjon som fungerer på alle plattformer (iOS, Android, Windows, macOS, Linux).

## Hvordan åpne filen

### iOS (iPhone/iPad)
1. **Best metode**: Lagre `index.html` i **Filer**-appen (iCloud Drive eller "På min iPhone")
2. Trykk på filen → velg **Del** → **Åpne i Safari**
3. Alternativt: Åpne via AirDrop eller e-post, men husk å trykke **Del → Åpne i Safari** (ikke bare åpne direkte)

### Android
1. Last ned `index.html` til telefonen
2. Trykk på filen → velg **Åpne med** → **Chrome**
3. Alternativt: Åpne via Google Drive → **Åpne i nettleser**

### Windows / macOS / Linux
- **Dobbelklikk** `index.html` → åpnes automatisk i standard nettleser
- Eller: Høyreklikk → **Åpne med** → velg nettleser (Chrome, Firefox, Edge, Safari)

## Funksjoner

- ✅ **100% offline** — alt er innebygd (bilder, CSS, JavaScript, fonts)
- ✅ **Dark/Light mode** — automatisk basert på systeminnstillinger
- ✅ **Smooth continuous scrolling** — naturlig scrolling uten snap-effekter
- ✅ **Animasjoner** — reveal-animasjoner når du scroller
- ✅ **Modals** — detaljerte CV-er og prosjektinfo i popups
- ✅ **Mobilvennlig** — responsivt design for alle skjermstørrelser
- ✅ **Accessibility** — keyboard navigation, screen reader support, fokusindikatorer

## Teknisk

- **Hovedfil**: `index.html` inneholder alt (HTML, CSS, JavaScript)
- **Bilder**: Lastes fra `bilder/` mappen (relativ path)
- **Fonts**: Inter-font embeddet direkte i CSS
- **Ingen avhengigheter**: Ingen eksterne lenker eller CDN-er
- **Størrelse**: ~2-3 MB (inkludert bilder i `bilder/` mappen)

## Utvikling

Filen er selvforklarende med kommentarer. For å endre innhold:
- Rediger tekst direkte i `index.html`
- For nye bilder: Legg bilder i `bilder/` mappen og referer til dem med `data-inline` attributt i `INLINE_IMAGES` objektet

## Lisens

Eon AS © 2025

