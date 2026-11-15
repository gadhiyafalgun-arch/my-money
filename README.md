# My Money

A private personal finance dashboard: credit cards, bills checklist, spending tracker and a debt payoff plan.

- Single file (`index.html`), plain HTML/CSS/JavaScript, no build step.
- No personal data in this repo. Your numbers live in a separate **private** repo (`data.json`).
- The app reads and writes that file through the GitHub API using a fine-grained token that you paste in once per device (stored only in that browser). Every save is a commit, so the data repo's history is your backup.
- Works offline from the last loaded copy and uploads changes when you're back online.
- `*.json` is git-ignored so data/backup files can't be committed by accident.

## Hosting
GitHub Pages from this repo (Settings → Pages → Deploy from branch `main`, folder `/`). The page is public but empty; without your token it can't see any data.
