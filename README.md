# Aditya Geda — Portfolio

A personal portfolio site. Builder, Analyst, Owner: 3.5 years across enterprise risk analytics and venture building, two funded brands, national case-competition finals, and self-started product ideas.

**Live:** _add your URL here once deployed_

---

## What's inside

A single self-contained `index.html`. No build step, no framework, no dependencies. Fonts and the portrait image are embedded directly in the file, so it works offline and deploys anywhere that can serve a static page.

Sections:

- **Above the fold** — intro, status, and headline metrics
- **Thesis** — how I actually work
- **Roles** — Builder / Analyst / Owner
- **Receipts** — a bento grid of 11 metrics; click any tile for the full story
- **Selected work & Ventures** — Onlyfeet.in, Doodle by Canvas
- **Competitions** — Project Falcon, AI x Behavioural Finance, Em.Donna, Quenzy, ShadiGhar, Ubon Growth Labs, Practo (each opens an inline deck preview)
- **Ideas created** — self-started products, starting with Stitch
- **Wins** — recognition and credentials
- **Journey** — chronological timeline
- **How I operate** — principles and stack
- **Contact**

Every project card opens a modal with the case study and an embedded deck / prototype preview (Google Slides and Drive), plus an "open in new tab" fallback.

---

## Run locally

It's a static file, so just open it:

```bash
# simplest: double-click index.html, or
open index.html
```

Or serve it with any static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

> The deck/prototype previews load live from Google Slides and Google Drive, so an internet connection is needed to see those embeds.

---

## Deploy

### Vercel
1. Push this repo to GitHub, then **vercel.com → Add New → Project → Import**.
2. No build settings needed (it's static). Deploy.
3. You get a `*.vercel.app` URL; add a custom domain in project settings.

### GitHub Pages
1. Push to a repo (e.g. `portfolio`).
2. **Settings → Pages → Source: `main` branch / root → Save.**
3. Live at `https://<username>.github.io/portfolio`.

### Netlify
- Drag the folder onto **app.netlify.com/drop** for an instant URL, or connect the repo for auto-deploys on push.

---

## Editing

All content lives in `index.html`:

- **Copy & sections** — plain HTML in the `<body>`.
- **Case studies & deck links** — the `caseStudies` and `caseLinks` objects in the `<script>` at the bottom. To swap a deck, update the `href` and `embed` URLs (Slides use `/embed`, Drive files use `/preview`).
- **Styling** — the `<style>` block in the `<head>`; design tokens (colors, fonts, spacing) are CSS variables under `:root`.

---

## Tech

- Hand-written HTML, CSS, and vanilla JavaScript
- Type: Archivo, Instrument Serif, JetBrains Mono
- Embedded deck/prototype previews via Google Slides & Drive
- Zero dependencies, single file

---

## Contact

- **Email:** aditya.25005@ssb.scaler.com
- **LinkedIn:** [aditya-geda](https://linkedin.com/in/aditya-geda-536b33198)
- **GitHub:** [Data-Avid-Aditya-04](https://github.com/Data-Avid-Aditya-04)

---

_Built by Aditya Geda._
