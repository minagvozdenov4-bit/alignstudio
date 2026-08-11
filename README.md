# ALIGN Aesthetic Dentistry — website export

Two self-contained HTML files, ready to host as-is (e.g. GitHub Pages) — fonts, images, styles and scripts are already embedded inline, so the pages work standalone even without the `assets/` folder.

- `index.html` — Serbian version (default/home)
- `en.html` — English version
- `assets/` — original source images (logo, photos) kept here as raw files for reference/reuse; not required for the pages to work

## Hosting on GitHub Pages

1. Create a repository (or use an existing one).
2. Upload `index.html`, `en.html` and the `assets/` folder together to the **root** of the repository (drag them all into the same upload — GitHub's web upload does not preserve folder structure otherwise, so `index.html`/`en.html` must land directly in root, with `assets/` alongside them).
3. In the repo Settings → Pages, set the source to the branch/root you uploaded to.
4. Your site will be live at `index.html` (Serbian home) with a language switch link to `en.html`.

No build step, no dependencies.
