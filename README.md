# Ledger

A calm, single-file personal finance tracker. Log income and expenses, browse them by day, week, or month, and keep an eye on a running balance and a savings goal — all in one static HTML page with no backend required.

## Features

- **Add, edit, and delete** income and expense entries, each with a date, amount, category, and note
- **Three views** — Daily, Weekly, and Monthly — with a period navigator to step back and forth
- Per-period summary: **money in, money out, and net**
- **Category breakdown chart** for spending, built with a colorblind-safe palette and layered textures so bars are distinguishable without relying on color alone
- **Running balance** at the top, based on a starting balance you set plus every entry logged
- **Savings goal** tracker with a progress bar toward a target amount
- **Export to CSV** for your full entry history
- **Clear all entries** with a one-click, two-step in-app confirmation
- Amounts formatted in **INR (₹)**

## Tech

Plain HTML, CSS, and vanilla JavaScript — no build step, no framework, no dependencies beyond Google Fonts (Fraunces, Inter, IBM Plex Mono) loaded over CDN. Everything runs client-side in the browser.

> **Note:** Data lives in memory for the current browser tab only. Refreshing the page resets it to the sample entries. There is no server or database, so entries aren't saved between visits or shared across devices.

## Running it locally

Just open `index.html` in any browser — no installation needed.

## Deploying to GitHub Pages

1. Push this repo to GitHub (make sure the tracker file is named `index.html`, or update the Pages settings accordingly).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save, wait a minute, and your tracker will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## License

© 2026 Ledger by Harshitamahant. All rights reserved.
