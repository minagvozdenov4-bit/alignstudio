# ALIGN Aesthetic Dentistry — Website Export

- `index.html` — English version, self-contained (fonts, images, logic all embedded — nothing else required to run).
- `sr/index.html` — Serbian version, same setup. Linked to/from the English version via the language switcher in the nav.
- `assets/` — the original image files, included for reference/future edits. Neither `index.html` loads from this folder at runtime (their images are embedded), so you don't need to upload it to your host unless you want the source files on hand.

## Host on GitHub Pages

1. Create a new GitHub repository (e.g. `align-dentistry`).
2. Upload `index.html` and the `sr/` folder (keep the same structure) to the root of the repo (via the GitHub web UI: "Add file" → "Upload files"). Uploading `assets/` too is optional.
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", pick the `main` branch and `/ (root)` folder.
5. Save. GitHub will give you a live URL (usually `https://<username>.github.io/<repo-name>/`) within a minute or two — the Serbian version will be at `.../sr/`.
