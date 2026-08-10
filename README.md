# ALIGN Aesthetic Dentistry — Website Export

- `index.html` — the full site, self-contained (fonts, images, logic all embedded inside it — nothing else is required for it to run).
- `assets/` — the original image files, included for reference/future edits. `index.html` does not load from this folder at runtime (its images are embedded), so you don't need to upload it to your host unless you want the source files on hand.

## Host on GitHub Pages

1. Create a new GitHub repository (e.g. `align-dentistry`).
2. Upload `index.html` to the root of the repo (via the GitHub web UI: "Add file" → "Upload files"). Uploading `assets/` too is optional.
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", pick the `main` branch and `/ (root)` folder.
5. Save. GitHub will give you a live URL (usually `https://<username>.github.io/<repo-name>/`) within a minute or two.
