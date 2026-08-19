# yourusername.github.io

Personal portfolio homepage — an about section plus a grid of project cards
linking out to individual project sites/repos (e.g. `2048-ledger`).

## Before you publish

This repo must be named exactly `yourusername.github.io` (your real GitHub
username) for GitHub Pages to serve it at the root domain instead of a
`/reponame/` subpath.

Open `index.html` and replace the placeholders:

- `Your Name` and the tagline in the `<header>`
- The three link URLs (GitHub, LinkedIn, `mailto:`) in `.links`
- The two `<p>` paragraphs under `ABOUT`
- The `2048 — Ledger` card's `href` — point it at your actual deployed
  `2048-ledger` Pages URL once that repo is live
- The two `placeholder` cards — swap each for a real `<a class="card">`
  once you have another project to add (copy the 2048 card's structure
  and change `data-accent` to `rust`, `moss`, `indigo`, or `brass` to vary
  the top stripe color)

## Deploy

1. Create a GitHub repo named `yourusername.github.io` (must match exactly).
2. Upload `index.html` (and this README if you want) to it.
3. Settings → Pages → Source: `Deploy from a branch` → Branch `main`,
   folder `/ (root)` → Save.
4. Live at `https://yourusername.github.io` within a minute or two —
   no `/reponame/` in the URL, since this is the special account-level repo.

## Adding another project later

Each new project can live as its own small repo (like `2048-ledger`) with
its own Pages URL, or exist elsewhere entirely. Either way, just add a new
card to the grid in `index.html` linking out to it.
