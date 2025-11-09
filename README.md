# Kayak Tourney Stats Dashboard

Lightweight static dashboard site for kayak fishing tournaments.

## What this is
- Pure HTML + CSS, no framework, no build step.
- Embeds Looker Studio dashboards for:
  - Event overviews
  - Angler profiles
  - Season totals
- Unified navigation and consistent dark theme.

## Files
- `index.html` - Landing page with quick links.
- `events.html` - Event overview dashboard.
- `angler.html` - Angler profiles dashboard (+ optional `?angler=Name` deep link).
- `season.html` - Season totals dashboard.
- `site.css` - Shared layout + theme styles.

## Local preview
Because of the `<base href="https://joshgoforth2011.github.io/kayak-tourney-stats/">` tag, links resolve as they do on GitHub Pages.
For best results:
- Open via a local web server (so relative paths behave consistently), or
- Test directly on the deployed GitHub Pages URL.

## Deploying to GitHub
This repo is intended to be served via GitHub Pages from the `main` (or `master`) branch.

Typical flow:

```bash
git status         # See what changed
git add .          # Stage all updates
git commit -m "Improve nav, layout, and accessibility" 
git push           # Push to GitHub
```

After pushing, GitHub Pages (if enabled) will automatically serve the updated site at:
`https://joshgoforth2011.github.io/kayak-tourney-stats/`
