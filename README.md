# snippet-launcher-web

Live: [https://kareembullard.github.io/snippet-launcher-web/](https://kareembullard.github.io/snippet-launcher-web/)

Search my real hotkeys, AI prompts, regex tokens, Python utilities, and text-expansion shortcuts — type to filter, arrow keys to move, Enter to copy.

## What it is

A static, single-file web app version of [snippet-launcher](https://github.com/kareembullard/snippet-launcher) (the original tkinter desktop app). This public version:

- Shows my **actual reference catalog** — 564 entries across 5 categories, published deliberately
- Runs entirely client-side, no build step, no network calls — everything is bundled in `index.html`
- Tiered fuzzy search (title-prefix > title-substring > tagged fields > body > last-resort subsequence match), same scoring shape as the desktop app
- `↑`/`↓` to move selection, `Enter` or double-click to copy, `Esc` to clear the search

## What's in the catalog

| Category | Count | Source |
|---|---|---|
| Hotkeys | 286 | `data/hotkeys.md` — keyboard shortcuts across ~20 apps (Amplenote, Arc, TickTick, Gmail, Linux, Windows, Text Blaze, SwiftKey, PowerToys, and more) |
| AI Prompts | 100 | `data/ai-prompts.md` — reusable prompt templates and text-expansion triggers, organized by prompt group |
| Regex | 53 | `data/regex-syntax.md` — regex syntax reference tokens |
| Python Utilities | 96 | `data/python-utilities.md` — documented functions across my `csv_utils`/`data_utils`/`file_utils`/`text_utils`/`word_utils` modules |
| Airtable Shortcuts | 29 | `data/airtable-shortcuts.json` — deduplicated export from my Index-Shortcuts Airtable base |

A handful of AI Prompt entries have content that's truncated in my own source notes (ending in `...`); those are shown as-is rather than filled in with invented text, and flagged in the preview panel.

## Run locally

Just open `index.html` in a browser — no build step, no server required.

## Screenshot

_(placeholder)_
