# snippet-launcher-web

A live demo: [https://kareembullard.github.io/snippet-launcher-web/](https://kareembullard.github.io/snippet-launcher-web/)

Instant fuzzy-search launcher for regex patterns, Python snippets, and keyboard shortcuts — type to filter, click (or press Enter) to copy.

## What it is

A static, single-file web app version of [snippet-launcher](https://github.com/kareembullard/snippet-launcher) (the original tkinter desktop app). This public version:

- Ships with a **generic, publicly-useful sample dataset** (common regex patterns, Python snippets, and keyboard shortcuts) instead of any personal data
- Has **no Airtable dependency** and makes no network calls — everything is bundled in `index.html`
- Runs entirely client-side; nothing is stored anywhere (there's no capture/save feature in this app, so no localStorage is needed)

## Run locally

Just open `index.html` in a browser — no build step, no server required. Or serve it:

```powershell
python -m http.server
```

## Deploy

This repo is served via GitHub Pages directly from the default branch root — no build step.

## Screenshot

_(placeholder)_
