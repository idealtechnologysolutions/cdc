# Coolant Data Capture — Prototype

Clickable prototype for the TNGA coolant round. Prepared by Ideal Technology Solutions.

## Files
- `index.html` — start page with links
- `Coolant Data Capture.dc.html` — the prototype
- `Coolant Data Capture - Functional Overview.dc.html` — walkthrough with screenshots
- `Coolant Data Capture - Requirements Sign-off.dc.html` — sign-off sheet
- `support.js`, `doc-page.js`, `_ds/`, `screenshots/` — required, keep them next to the pages

## Publish on GitHub Pages
1. Upload **every file and folder above**, including the hidden `.nojekyll` file, to the repository root.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / root.
3. Open `https://<user>.github.io/<repo>/`.

`.nojekyll` matters: without it GitHub Pages skips folders starting with `_`, and `_ds/` (styles) would not load.

## Notes
- Needs an internet connection: React, fonts and icons load from public CDNs (unpkg.com, fonts.googleapis.com).
- Opening the `.html` files by double-clicking (file://) may be blocked by the browser; use GitHub Pages or any local web server (e.g. `npx serve`).
- Data is held in memory and resets on reload.
