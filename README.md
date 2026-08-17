# garvock.github.io

Root-domain GitHub Pages site for [TicTacRoll](https://github.com/Garvock/TicTacRoll) — a
dice-driven Ultimate Tic-Tac-Toe game. TicTacRoll's own repo is private, so this separate public
repo hosts:

- `index.html` — landing page
- `join/index.html` — tappable invite-link redirect (`?c=<CODE>` → `tictacroll://join/<CODE>`)
- `privacy-policy.html` — TicTacRoll's privacy policy (for Play Store submission)
- `.well-known/assetlinks.json` — Android App Links verification

This repo is intentionally named `garvock.github.io` — GitHub serves it at the domain root
(`https://garvock.github.io/`) rather than a `/reponame/` sub-path, which Android App Links'
`assetlinks.json` requires.

See `TicTacRoll`'s own `site/README.md` for the full setup/verification steps.
