# Kelsey's Dog Grooming

Static marketing site for Kelsey's Dog Grooming, serving the DMV (Washington DC,
Maryland, and Northern Virginia). Contact: Kelsey Buckley —
<kelsey@kelseysdoggrooming.com>

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | The entire site — one-screen offer panel plus an About section |
| `styles.css` | All styling (no build step, no dependencies) |
| `404.html` | Not-found page |
| `assets/paw.svg` | Logo / favicon |
| `.github/workflows/static.yml` | Deploys the repo root to GitHub Pages on every push to `main` |

## Editing

Everything is plain HTML and CSS, so edits go straight into `index.html`.

The first screen is deliberately sized to hold every essential fact without
scrolling: the free-training-groom offer, what a groom includes, Kelsey's
background, and both ways to book. Keep it that way — anything added there
pushes the call to action below the fold.

Current offer, as reflected in the copy: **full grooms only, free, while Kelsey
trains.** When that changes (paid services, more service types, set hours),
`index.html` is the only file that needs editing.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying

Pushing to `main` triggers the Pages workflow. In the repository under
**Settings → Pages**, set **Source** to **GitHub Actions**.
