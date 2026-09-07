# pbaarn.github.io — Personal App Directory & Hub

Een moderne, minimalistische portaalpagina die al je 16 webapplicaties en tools bundelt die gehost worden via GitHub Pages.

## 🚀 Hoe live te zetten op GitHub Pages

Volg deze eenvoudige stappen om dit als je homepage op `https://pbaarn.github.io/` te laten draaien:

### 1. Maak een nieuwe repository aan op GitHub
- Ga naar [github.com/new](https://github.com/new)
- Repository naam: exact **`pbaarn.github.io`** (dit activeert automatisch GitHub User Pages)
- Zorg dat hij op **Public** staat.

### 2. Push deze bestanden
Open je terminal in deze map en voer uit:

```bash
cd /Users/paulbaarn/.gemini/antigravity/scratch/pbaarn.github.io
git init
git add index.html README.md
git commit -m "feat: initial hub page with 16 apps directory"
git branch -M main
git remote add origin https://github.com/pbaarn/pbaarn.github.io.git
git push -u origin main
```

Binnen 1 à 2 minuten is je overzichtspagina live op:
👉 **https://pbaarn.github.io/**

---

## 🛠️ Functionaliteiten van de indexpagina
- **Dark / Editorial aesthetic** (Geïnspireerd op je apps zoals PianoAgenda en Momentum)
- **Live zoekbalk** met sneltoets (`/` om direct te typen, `Esc` om te wissen)
- **Categorie-filters** (Muziek & Piano, Focus & Practice, Sport & Interval, Trello)
- **Directe links** naar zowel de actieve app als de onderliggende GitHub repository
- **Zero build step**: Eén standalone bestand dat direct werkt zonder npm, webpack of builds.
