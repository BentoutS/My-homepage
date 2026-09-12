# Soufiane Bentout — Personal Academic Homepage

Personal website built from your CV: profile, career timeline, full publication list (44), teaching record, thesis supervision, conferences, and academic service — all in one self-contained page.

## Contents
- `index.html` — the site (no external dependencies besides Google Fonts, which load automatically once live)
- `assets/profile.jpg` — your photo, extracted from the CV PDF

## Publish on GitHub Pages
This can go in its own repository (e.g. `bentouts.github.io` for your main personal domain, or any other repo name with Pages enabled):

1. Create a new GitHub repository.
2. Upload `index.html` and the `assets/` folder to the root (drag-and-drop via "Add file → Upload files" on GitHub — no need to paste any code).
3. Settings → Pages → Branch: `main` → folder `/root` → Save.
4. Live in 1–2 minutes at `https://<your-username>.github.io/<repo-name>/`.

## Editing later
- **Publications**: the `publications` array near the bottom of the `<script>` block — one object per paper (`a` = authors, `y` = year, `t` = title, `j` = journal, `vol` = volume/pages, `doi` = optional link).
- **Teaching table, thesis list, conferences, service**: plain HTML rows/list items in their respective `<section>` blocks — easy to add or edit directly.
- **Sections that expand/collapse** (Publications, Teaching, Supervision): click the header to open — this keeps the page from feeling overwhelming despite the long CV.

## Note
The Master's thesis supervision list follows your CV exactly, including the two 2026 entries (Manel Bakhti, Malik Belhadri) which are now marked with completion dates rather than "Ongoing" — if those are still in progress, let me know and I'll revert those two to "Ongoing."
