# eliseantoine.com

Personal academic website, built as plain static HTML/CSS and hosted on GitHub Pages.

## Structure

- `index.html`, `research.html`, `teaching.html`, `policy-engagement.html`, `contact.html` — pages
- `assets/css/style.css` — shared stylesheet
- `assets/images/` — profile photo
- `assets/files/` — CV PDF

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

Served directly by GitHub Pages from the `main` branch. Pushing to `main` publishes automatically.
