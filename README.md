# VM 2026 – Tippeligaen

Betting competition for the 2026 FIFA World Cup.

## Files

| File | Description |
|------|-------------|
| `VM2026_Admin.html` | Admin dashboard — import tips, enter results, generate summary |
| `VM2026_Public.html` | Public leaderboard — read-only, auto-refreshes every 5 min |
| `vm2026_data.json` | Exported data file (generated from admin dashboard) |
| `VM2026_MineTips.xlsx` | Betting sheet for each participant |

## Setup

### For the admin (Martin)
1. Open `VM2026_Admin.html` in your browser
2. Import all players' `.xlsx` files via the upload zone
3. Enter match results under **Kampresultater**
4. Click **⬆ Eksporter backup** — this downloads `vm2026_data_DATO.json`
5. Rename it to `vm2026_data.json` and upload it to this repository

### For the public page
The public page (`VM2026_Public.html`) fetches `vm2026_data.json` automatically.
It refreshes every 5 minutes.

After uploading to GitHub Pages the public URL will be:
`https://DITT_NAVN.github.io/REPO_NAVN/VM2026_Public.html`

## GitHub Pages setup
1. Go to repository **Settings → Pages**
2. Set source to **main branch / root folder**
3. Save — the site will be live within a minute
