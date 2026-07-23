# Ante Vinum 🍷

A study companion for the WSET Level 2 Award in Wines. Ten chapters of notes, grape profiles, flashcards and a timed mock exam, all in a single HTML file with no accounts, no tracking and no build step.

**Live site:** [joelucadooley.github.io/ante-vinum](https://joelucadooley.github.io/ante-vinum)

[![Sponsor on GitHub](https://img.shields.io/badge/Sponsor%20on-GitHub-black?logo=github&style=for-the-badge)](https://github.com/joelucadooley)
[![Support me on Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/joelucadooley)

---

## How it works

Built around one idea: read first, drill second. Quizzes only tell you what you already know, so the notes come before everything else.

| Step | Section | What it does |
|------|---------|--------------|
| **I** — Read | Study notes | Ten chapters covering the whole syllabus, with structure profiles for every principal grape |
| **II** — Drill | Flashcards | Around 130 cards, tap to flip, grouped by chapter |
| **III** — Check | Quick quiz | Ten random questions, each explained the moment you answer |
| **IV** — Sit | Mock exam | Fifty questions in sixty minutes, marked at the end |
| **V** — Look up | Tasting reference | The systematic tasting vocabulary, and what each wine colour tells you |

---

## The exam it prepares you for

50 multiple-choice questions, 60 minutes, closed book, no negative marking.

| Grade | Mark |
|-------|------|
| **Pass** | 55% |
| **Pass with merit** | 70% |
| **Pass with distinction** | 85% |

Questions are spread across six learning outcomes. The mock exam samples them in exactly the same proportions:

| Learning outcome | Questions |
|------------------|-----------|
| The vineyard: environment and grape growing | 5 |
| The winery: winemaking and bottle ageing | 4 |
| The eight principal grape varieties and their regions | 19 |
| Regionally important grape varieties | 12 |
| Sparkling and fortified wines | 6 |
| Storage, service, faults and food pairing | 4 |

---

## Features

- **Red / white wine mode** — a wine glass toggle that swaps the whole palette between a deep oxblood cellar and a pale straw one. Remembered between visits.
- **Grape profiles** — acidity, tannin, body and alcohol shown on the same low/medium/high scale the SAT uses, so you learn to identify wines by structure rather than by guessing.
- **Interactive colour reference** — tap any wine colour to see what it tells you about age, oak and winemaking.
- **No repeats** — the quiz remembers the last 45 questions it showed you, so consecutive rounds stay fresh.
- **Installable** — add it to a phone home screen and it launches full screen with its own icon.

---

## Tech stack

- **Frontend:** vanilla HTML, CSS and JavaScript in one file. No framework, no bundler
- **Type:** Marcellus, a Roman inscriptional face, served from Google Fonts
- **Graphics:** hand-written SVG for the bottle, the engraved crest and the icons
- **State:** in memory, with `localStorage` used only to remember your wine mode
- **Hosting:** GitHub Pages
- **Cost:** £0

---

## Project structure

```
├── index.html               # The entire site: content, styles, logic
├── og-image.png             # Link preview card (1200x630)
├── apple-touch-icon.png     # iOS home screen icon
├── icon-192.png             # Android / installed app icon
├── icon-512.png             # Android / installed app icon
└── manifest.webmanifest     # Enables "Add to Home Screen"
```

---

## Running locally

No install, no build. Clone it and open the file:

```bash
git clone https://github.com/joelucadooley/ante-vinum.git
cd ante-vinum
open index.html            # macOS
# xdg-open index.html      # Linux
# start index.html         # Windows
```

It works offline apart from the webfont.

---

## Deploying

Settings → Pages → Branch `main`, folder `/ (root)`. Live in about a minute.

> **One edit before sharing.** Four lines near the top of `index.html` contain `ante-vinum`. If the repository is named anything else, change them to match. Social previews need absolute URLs, so a relative path will not work.

Preview looking stale after sharing? Paste the URL into the [Facebook](https://developers.facebook.com/tools/debug/), [X](https://cards-dev.twitter.com/validator) or [LinkedIn](https://www.linkedin.com/post-inspector/) debugger to refresh it.

---

An independent study aid, not affiliated with WSET. The official set text for the course is *Wines: Looking Behind the Label*.

Decanted by [Joe Luca Dooley](https://github.com/joelucadooley)