# pbaarn.github.io — Personal App Directory & Hub

Een moderne, minimalistische portaalpagina die al je 17 webapplicaties en tools bundelt die gehost worden via GitHub Pages.

### Overzicht van actieve applicaties:
1. **Piano Oefenagenda** (`/pianoagenda/`) — Deliberate Practice & Lessenaar Planner
2. **AetherMidi** (`/orbit/`) — Visual MIDI Music Generator
3. **Experilife // Protocol Studio** (`/experilife/`) — Empirical Sandbox & Life Design
4. **MOMENTUM // Frogeater** (`/momentum/`) — Anti-uitstel Canvas
5. **Brainstorm Manager** (`/brainstorm/`) — Concept Decomposition & Gist Sync
6. **Harmonic Canvas** (`/harmonic/`) — Harmonic & Chord Explorer
7. **20 Hours to Mastery** (`/twentyhours/`) — Deliberate Practice Ledger
8. **Harmonic Circle** (`/circle/`) — Chord Progression Studio
9. **Progressions Engine** (`/progressions/`) — Piano Progression Drill Engine
10. **Cadence** (`/chordtrainer/`) — Piano Chord Recall Trainer
11. **Piano Chord Practice Grid** (`/chord-recall/`) — 12-Key Boring Chord Trainer
12. **SONUS** (`/ear-training/`) — Premium Ear Training
13. **Crosstrainer Canvas** (`/crosstrainer/`) — Interval & Schema Timer
14. **AI 365** (`/ai365/`) — Dagelijkse AI Integratie Tracker
15. **Checklist Manager** (`/checklist-manager/`) — Editorial Execution Protocols
16. **Checklist Estimator** (`/checklist-estimator/`) — Trello Power-Up Connector
17. **Checklist+ Power-Up** (`/powerup/`) — Trello Power-Up Suite

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
