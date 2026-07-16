# Sapia Bio landing page

A lightweight static landing page for GitHub Pages deployment.

## Files

- `index.html` — page structure
- `styles.css` — visual styling and responsive layout
- `script.js` — mobile nav toggle
- `.github/workflows/deploy-pages.yml` — GitHub Actions workflow for Pages deployment

## Local preview

From the repository root:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages setup

1. Push this repository to GitHub.
2. In the repository settings, enable GitHub Pages.
3. Choose the GitHub Actions deployment source.
4. The included workflow will publish the site automatically when changes are pushed to `main`.
