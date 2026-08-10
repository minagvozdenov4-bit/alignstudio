# ALIGN Aesthetic Dentistry — Website Export

- `index.html` — English version, self-contained (fonts, images, logic all embedded — nothing else required to run).
- `sr.html` — Serbian version, same setup, sitting next to `index.html` (no subfolder). Linked to/from the English version via the language switcher in the nav.
- `assets/` — the original image files, included for reference/future edits. Neither HTML file loads from this folder at runtime (their images are embedded), so you don't need to upload it to your host unless you want the source files on hand.

## Host on GitHub Pages

1. Create a new GitHub repository (e.g. `align-dentistry`).
2. Upload `index.html` AND `sr.html` together to the root of the repo — drag both files in at once (GitHub web UI: "Add file" → "Upload files"). Uploading `assets/` too is optional.
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", pick the `main` branch and `/ (root)` folder.
5. Save. GitHub will give you a live URL (usually `https://<username>.github.io/<repo-name>/`) within a minute or two — the Serbian version will be at `.../sr.html`.

If the language switch still 404s after this, double-check both `index.html` and `sr.html` show up side by side in the repo's file list at the root — if `sr.html` is missing, the upload didn't include it and it needs to be re-added.
