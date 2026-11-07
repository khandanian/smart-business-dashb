# BizPulse — Smart Business Dashboard

A Persian-first, RTL, responsive business dashboard demo for GitHub Pages.

## Live demo
https://khandanian.github.io/smart-business-dashb/

## Features
- Interactive revenue KPIs and sales chart for 7, 30, and 90 days
- Order table with search and status updates
- Add a demo order, reset demo data, and export CSV
- Browser-local storage: no backend or cloud database
- Fully static HTML, CSS and JavaScript
- GitHub Actions deployment workflow

**All sample customer names and order figures are fictional.** Data stays in the visitor's browser. This is a portfolio demo, not production accounting software.

## Run locally
Open `index.html` or serve this folder with `python -m http.server 8080`.

## Deploy
Go to **Settings → Pages → Build and deployment → Source → GitHub Actions**. The workflow in `.github/workflows/deploy.yml` runs on pushes to `main` or manually.

## Files
- `index.html` — interface
- `assets/style.css` — responsive design
- `assets/app.js` — sample data, KPIs, charts, orders and CSV export
- `.github/workflows/deploy.yml` — GitHub Pages deployment
