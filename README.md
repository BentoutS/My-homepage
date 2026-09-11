# Soufiane Bentout — Personal Academic Homepage

A curated personal page (not a full CV dump): profile, a handful of selected publications, a "Mathematicians Who Shaped the Field" section, and academic service — all in one self-contained page.

## Contents
- `index.html` — the site
- `assets/profile.jpg` — your photo, extracted from the CV PDF

## Publish on GitHub Pages
1. Create a new GitHub repository (or reuse one you already have for your personal page).
2. Upload `index.html` and the `assets/` folder to the root ("Add file → Upload files" on GitHub — drag and drop, no pasting).
3. Settings → Pages → Branch: `main` → folder `/root` → Save.
4. Live in 1–2 minutes at `https://<your-username>.github.io/<repo-name>/`.

## What's on the page
- **Hero** — photo, name, "Professor of Applied Mathematics" only (no full position/education timeline, no numeric stats)
- **Academic Profile** — one paragraph
- **Selected Publications** — 7 representative papers (2016–2026) rather than the full list, with a link out to Google Scholar / ResearchGate for everything else
- **Mathematicians Who Shaped the Field** — short bios + quotes: Évariste Galois, Henri Poincaré, Carl Friedrich Gauss, Emmy Noether
- **Academic Service** — condensed to two short paragraphs (editorial roles, current research directions)
- **Contact**

## Editing later
- **Selected publications**: edit the `<ul class="pub-list">` items directly in the Publications section.
- **Mathematicians**: each is a `.math-card` block in the Mathematicians section — copy one to add another, or edit the bio/quote text directly. All quotes used are historically documented and public domain.

## Note on sourcing
The four quotes are all real, well-documented historical quotes (verified, not invented):
- Galois — from his actual last letter before his fatal duel (1832)
- Poincaré — a commonly cited quote from his own writing
- Gauss — his famous characterization of mathematics
- Noether — from Einstein's 1935 letter to *The New York Times* about her
