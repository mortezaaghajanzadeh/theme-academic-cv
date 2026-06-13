# mortezaaghajanzadeh.com

Personal academic website of Morteza Aghajanzadeh — a plain static site (HTML + CSS, no framework, no build step).

## Structure

- `index.html` — homepage
- `research/` — one page per paper
- `styles.css` — all styling
- `img/` — photo and figures
- `files/` — CV and slides (PDFs)

## Edit

Open the files in any text editor. To add a paper: duplicate an `<article class="card">` block in `index.html` and add a matching page in `research/`.

## Preview

Double-click `index.html`, or run a local server:

```
python3 -m http.server
```

## Deploy

Hosted on Netlify. No build command — `netlify.toml` publishes the repo root as-is. Push to `main` and Netlify deploys.

The previous Hugo version is archived locally in `legacy-hugo/` (ignored by git) and remains in the git history.
