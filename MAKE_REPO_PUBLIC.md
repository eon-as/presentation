# Gjør repoet public for GitHub Pages

## Hvorfor?
GitHub Pages krever at repoet er **public** (gratis) eller at du har **GitHub Enterprise** (betalt).

Siden `index.html` allerede er en offentlig presentasjon (ingen sensitiv kode), er det trygt å gjøre repoet public.

## Steg-for-steg:

1. Gå til repoet: `https://github.com/eon-as/html-presentation`
2. Klikk på **Settings** (innstillinger)
3. Scroll helt ned til **Danger Zone**
4. Klikk på **Change visibility** → **Change to public**
5. Bekreft ved å skrive repo-navnet: `eon-as/html-presentation`
6. Klikk **I understand, change repository visibility**

## Etter at repoet er public:

1. Gå tilbake til **Settings** → **Pages**
2. Under **Source**: velg branch `main` og folder `/ (root)`
3. Klikk **Save**
4. Vent 1-2 minutter
5. Presentasjonen er live på: `https://eon-as.github.io/html-presentation/`

## Hva er synlig?
- ✅ `index.html` (presentasjonen) - dette er meningen
- ✅ `.gitignore`, `README.md` - ingen sensitiv info
- ❌ `bilder/` og `cv/` er ikke i repoet lenger (ignorert via .gitignore)

**Alt er trygt!** 🎉

