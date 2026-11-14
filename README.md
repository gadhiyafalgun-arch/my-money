# My Money

A private personal finance dashboard: credit cards, bills checklist, spending tracker and a debt payoff plan.

- Single file (`index.html`), plain HTML/CSS/JavaScript, no build step.
- All data stays in your browser (localStorage). Nothing personal is stored in this repo.
- Back up with **Data → Export backup**; restore or move devices with **Import**.
- `*.json` is git-ignored so data/backup files can't be committed by accident.

## Hosting privately
Deploy with Cloudflare Pages (connect this repo, no build settings), then lock it to your email with Cloudflare Zero Trust → Access.
