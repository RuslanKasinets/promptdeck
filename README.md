# 🎛️ PromptDeck

**A mixing-console style prompt builder for [Suno AI](https://suno.com).**

Mix genres like a DJ, roll endless prompt variants, and paste a ready style prompt straight into Suno's style box. No build step, no backend, no dependencies — a single HTML file.

**Live demo:** [https://ruslankasinets.github.io/promptdeck/](https://ruslankasinets.github.io/promptdeck/)

---

## ✨ Features

- **Genre Mixer** — blend up to 3 genres (A/B/C channels) with weight faders across 22 genres
- **Genre search & category chips** — live filtering: electronic / urban / live / orchestral / chill
- **Variant generator** — reroll with intensity levels, repeat-avoidance history, per-slot locks
- **5 content slots** — bass, harmony, rhythm, atmosphere, texture, distributed by channel weight
- **VOX Engine** — 10 vocal palettes with SUBTLE / FORWARD / DOMINANT amounts
- **MOOD Engine** — 10 emotional palettes with the same intensity control
- **ARR Engine** — 7 arrangement structure palettes
- **Exclude styles** — preset chips + custom negative styles
- **Deck Memory** — presets (up to 12), prompt history, JSON export/import, persisted in localStorage
- **BPM control, copy button with character counter, Surprise button**
- **Fully responsive** — mobile layout with sticky copy bar

## 🚀 Usage

1. Open the app
2. Pick a genre on channel **A** (add **B**/**C** for a blend) and set the faders
3. Dial in **VOX**, **MOOD** and **ARR** engines to taste
4. Hit **GENERATE** / reroll until the prompt feels right — lock slots you like
5. **COPY** and paste into Suno's *Style of Music* field

## 🛠️ Running locally

Just open `index.html` in any modern browser. That's it.

## 📦 Deploying your own copy

**GitHub Pages:** fork/clone this repo → Settings → Pages → Deploy from branch `main`, folder `/ (root)`.

**Netlify:** drag & drop the folder at [app.netlify.com/drop](https://app.netlify.com/drop) — done in 10 seconds.

## 🧱 Tech

- Vanilla HTML / CSS / JS — zero dependencies, zero build
- Fonts: Inter + JetBrains Mono (Google Fonts)
- Data persistence via `localStorage`

## 📄 License

MIT — do whatever you want, attribution appreciated.
