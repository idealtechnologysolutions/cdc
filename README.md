# Coolant Data Capture — Prototype

Clickable prototype for coolant data capture. Pilot area: Sprint / TRUQ2 (TNGA, V6T and 24T to follow). Prepared by Ideal Technology Solutions.

## Files
- `index.html` — **current design** (same as `Coolant Data Capture - Sidebar v3.dc.html`): side menu with sign-in and per-site roles, plus Jeff’s round-four answers — editable products, ranges, machine IDs and titration charts; dust collector checks uploaded from the Microsoft Forms export. Opens at the site root.
- `links.html` — start page linking every document and earlier version
- `Coolant Data Capture - Sidebar v3.dc.html` — the current design under its working name
- `Coolant Data Capture - Sidebar v2.dc.html` — previous version, before Jeff’s round-four answers
- `assets/dust-collector-checks-2.4T-example.xlsx` — Jeff’s 2.4T Forms export, used by “Use Jeff’s 2.4T example”
- `assets/dust-collector-checks-Sprint-sample.xlsx`, `…-Tool-Regrind-sample.xlsx` — sample Forms exports in the 2.4T layout (made-up checks)
- `Coolant Data Capture - Functional Specification.dc.html` — **functional specification and requirements for sign-off** (Release 1)
- `Sprint Pilot - Prototype Features v3 Final.dc.html` — final feature walkthrough with screenshots (`screenshots/v3/`, plus `screenshots/v2/` for unchanged screens)
- `Sprint Pilot - Prototype Features v2.dc.html` — previous walkthrough, before Jeff’s round-four answers
- `Sprint Pilot - Open Questions for Michael.dc.html` — round-four business and technical questions
- `Coolant Data Capture.dc.html` — earlier version, top menu
- `Coolant Data Capture - Sidebar.dc.html` — earlier side-menu version, before sign-in and roles
- `Coolant Data Capture - Header - Sidebar.dc.html` — top bar + white side menu, Chemico Systems brand (Michael's layout)
- `Sprint Pilot - Prototype Features.dc.html` / `… - Side Menu.dc.html` — feature walkthroughs with screenshots
- `Coolant Data Capture (TNGA).dc.html` — earlier TNGA version
- `Sprint Pilot - Questions for Jeff.dc.html` — open questions for the pilot
- `Coolant Data Capture - Functional Overview.dc.html` — walkthrough with screenshots
- `Coolant Data Capture - Requirements Sign-off.dc.html` — earlier TNGA sign-off sheet (replaced by the Functional Specification)
- `support.js`, `doc-page.js`, `vendor/` (incl. `vendor/chemico/brand.css` — Chemico Graphic Standards colors and type), `assets/`, `screenshots/` — required, keep them next to the pages

## Publish on GitHub Pages
1. Upload **every file and folder above**, including the hidden `.nojekyll` file, to the repository root.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / root.
3. Open `https://<user>.github.io/<repo>/`.

No file or folder the pages need starts with `_`, so GitHub Pages serves everything even without `.nojekyll` (it is included anyway).

## Notes
- Needs an internet connection: React, fonts and icons load from public CDNs (unpkg.com, fonts.googleapis.com).
- Opening the `.html` files by double-clicking (file://) may be blocked by the browser; use GitHub Pages or any local web server (e.g. `npx serve`).
- Data is held in memory and resets on reload.
