# Flynn Planner

A multi-scale professional planning PWA — Year → Semester → Month → Week → Day.

Color-coded by pillar: Teaching (blue), Research (purple), Service (green), Admin/Finance (orange).  
Saturday is your Admin anchor day with a recurring finance checklist.

## Deploy to GitHub Pages (5 minutes)

1. Create a new **public** GitHub repo (e.g. `flynn-planner`)
2. Upload all files in this folder to the repo root
3. Go to **Settings → Pages → Source** → select **GitHub Actions**
4. Push to `main` — the site deploys automatically
5. Your URL: `https://yourusername.github.io/flynn-planner/`

## Install as app on iPhone

1. Open the URL in **Safari**
2. Tap the Share button → **Add to Home Screen**
3. It behaves like a native app (no browser chrome, offline support)

## Install as app on Mac / PC

1. Open in Chrome
2. Click the install icon in the address bar (or ⋮ menu → Install)
3. Runs in its own window

## Data

All data lives in your browser's `localStorage` — no server, no API, free forever.  
Use **Export Backup** (sidebar) to save a JSON file. **Import Backup** to restore.  
To sync between devices: export on one, import on the other. (Or use the same browser signed into Chrome sync.)

## Customization

- Edit `data.budgetItems` in `index.html` to change Saturday checklist items
- Colors are CSS variables at the top of `<style>` — easy to tweak
