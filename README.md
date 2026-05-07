# AI Marketing Technology Landscape Dashboard

GitHub Pages-ready interactive dashboard.

## Files
- `index.html` — dashboard application
- `data.json` — AI marketing tools dataset

## How to publish on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `data.json` to the root folder.
3. Go to Settings > Pages.
4. Under Build and deployment, select `Deploy from a branch`.
5. Select `main` branch and `/root`.
6. Open the GitHub Pages URL after deployment.

## Local preview
Because `index.html` loads `data.json`, some browsers block it when opened directly from the filesystem.
Use a local server:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```
