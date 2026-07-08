# Smite 2 Codex

A personal **Smite 2 companion** — installable web app (PWA) for phone or desktop.

**Live app:** https://rc7676.github.io/smite2-codex/

## Features
- All **88 gods**, grouped by role (Mid / Carry / Support / Solo / Jungle), with real portraits and class emblems.
- **Full ability data** (description, per-level stats, notes) for 86 gods — sourced from the Smite 2 wiki — and editable in-app.
- **Complete item catalog** with passives, filterable by category and by stat (Strength / Intelligence / Defense / Utility).
- Personal **tracking** saved on your device: mark gods **owned**, **played**, set **familiarity** (Untried → Mastered), and keep notes.
- **Practice picker**, per-god reset, and a backup/restore code.
- Works **offline** and installs to your home screen (service worker + web manifest).

## Install
Open the live link in Chrome (Android) or Safari (iOS) → menu → **Install app / Add to Home Screen**.

## Structure
- `index.html` — the entire self-contained app (data + UI + embedded portraits).
- `manifest.webmanifest` — PWA manifest.
- `sw.js` — service worker (offline caching).
- `icon-*.png`, `apple-touch-icon.png` — app icons.

Hosted free on GitHub Pages.
