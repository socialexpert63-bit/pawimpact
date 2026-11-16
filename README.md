# PawImpact (demo concept)

- `index.html` – public website
- `app.html` – interactive platform demo (brands, campaigns, shelters, content, impact, journey, AI assistant, automation)

All data is fictional. Pure static files: no build step.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server`.

## Host on GitHub Pages
Push these files to a repo, then Settings > Pages > deploy from the main branch (root).

## Notes
- The AI assistant uses Claude's in-page capability, which only works inside claude.ai. On GitHub Pages it shows a notice. To make it live, add your own backend that calls an AI API (never put an API key in front-end code).
- Automations are simulated. Nothing is emailed or posted.
