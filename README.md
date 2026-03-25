# Leisure Services Budget Tool

This repository is ready to publish as a **GitHub Pages** static site.

## What's included for GitHub Pages

- `index.html`: the app
- `.nojekyll`: disables Jekyll processing (recommended for plain static apps)
- `manifest.webmanifest`: web app manifest metadata
- `sw.js`: service worker for basic asset caching

## Publish on GitHub Pages

1. Push this branch to GitHub.
2. In your repo, open **Settings → Pages**.
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or your default branch), folder `/ (root)`
4. Save and wait for the first deployment.
5. Open the Pages URL shown in Settings.

## Notes

- The app depends on external CDN scripts for `xlsx` and `jszip`; those require internet access when loading the page.
- If you host at `https://<user>.github.io/<repo>/`, relative paths (`./...`) in this project already work.
