# the scanner — URL Security Scanner

A responsive, frontend-only phishing URL analysis dashboard. No build step or dependencies are required.

## Run

Open `index.html` in a modern browser. For a local web server from this folder, run:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Features

- URL structure and phishing-pattern analysis with explainable signals and a risk score
- Scan history with search, risk filters, deletion, and CSV export
- Downloadable per-scan text report
- Editable local watchlist
- Responsive overview, scanner, history, watchlist, and methodology screens
- Scan and watchlist data persisted in browser local storage

## Scope

This is a browser-only demonstration. The analyzer uses local URL heuristics; it does not visit a site, verify TLS certificates, inspect page content, contact reputation feeds, or provide a safety guarantee. All saved data remains in the browser's local storage.
