# Portfolio 💼

A personal resume page — a single static page covering my background, experience, and education.

## What's on the page

- Intro with profile photo, current role, and location
- Work experience with roles, companies, and dates
- Education and master's thesis focus
- Certifications, languages, and volunteer work

## Running it locally

The page is fully static, so you can open `index.html` directly in a browser.

To serve it over HTTP instead:

```bash
python -m http.server 8123
```

Then visit [localhost:8123](http://localhost:8123).

## Structure

```
index.html        the page itself
css/style.css     layout, theming, and print styles
img/              profile photo
```

## Notes

- The layout is responsive and adapts to light and dark mode via `prefers-color-scheme`.
- Print styles are included, so the page can be saved to PDF straight from the browser.
- This repo is private and not published to GitHub Pages.
