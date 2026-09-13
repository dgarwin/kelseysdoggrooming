# Kelsey's Dog Grooming

Static marketing site for Kelsey's Dog Grooming, serving the DMV (Washington DC,
Maryland, and Northern Virginia). Contact: Kelsey Buckley —
<kelsey@kelseysdoggrooming.com>

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The entire site — hero, services, about, contact |
| `styles.css` | All styling (no build step, no dependencies) |
| `404.html` | Not-found page |
| `assets/paw.svg` | Logo / favicon |
| `.github/workflows/static.yml` | Deploys the repo root to GitHub Pages on every push to `main` |

## Editing

Everything is plain HTML and CSS, so edits go straight into `index.html`. The
service descriptions are starting copy — replace them with Kelsey's real
service list, pricing, and hours.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying

Pushing to `main` triggers the Pages workflow. In the repository under
**Settings → Pages**, set **Source** to **GitHub Actions**.
