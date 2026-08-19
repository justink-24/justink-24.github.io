# justink-24.github.io

Justin Kpana's personal portfolio homepage: an about section plus a grid of
project cards linking out to individual project sites/repos (e.g.
`2048-ledger`).

## Repo name

This repo must be named exactly `justink-24.github.io` for GitHub Pages to
serve it at the root domain instead of a `/reponame/` subpath.

## Already filled in

- Name, tagline, and links (GitHub, LinkedIn, email) in the header
- The about section, covering creative/technical projects and interest in ML and AI
- The 2048 project card, pointing at `https://justink-24.github.io/2048-ledger/`

## Still to edit

- The two dashed "Next project goes here" placeholder cards, once you have
  another project to add (copy the 2048 card's structure and change
  `data-accent` to `rust`, `moss`, `indigo`, or `brass` to vary the top
  stripe color)

## Deploy

1. Create a GitHub repo named `justink-24.github.io` (must match exactly).
2. Upload `index.html` (and this README if you want) to it.
3. Settings, Pages, Source: `Deploy from a branch`, Branch `main`,
   folder `/ (root)`, Save.
4. Live at `https://justink-24.github.io` within a minute or two, no
   `/reponame/` in the URL, since this is the special account-level repo.

## Adding another project later

Each new project can live as its own small repo (like `2048-ledger`) with
its own Pages URL, or exist elsewhere entirely. Either way, just add a new
card to the grid in `index.html` linking out to it.
