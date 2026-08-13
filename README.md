# Singapore Property Calculator

Web calculator for Singapore property **sell / buy / combined** cashflows (stamp duties, agent, legal, CPF, loan rules).

## Live app

**https://ngsupeng76.github.io/sg-property-calculator/**

## Features

- Sell proceeds, buy costs, and combined picture
- Named **scenarios** saved in the browser on each device
- **Export / Import** JSON backup (move scenarios between phone and PC)
- **Share** link encodes the current scenario in the URL (works on any device)
- Installable **PWA** (Add to Home Screen on iPhone / Android / desktop)

## Why not open the HTML file directly?

`file://` and many mobile “Open in…” sandboxes wipe `localStorage` when the tab closes. Always use the hosted HTTPS link above for durable saves.

## Local development

Open `index.html` via any static server, e.g.:

```bash
npx --yes serve .
```
