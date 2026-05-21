# Coronel Rally Team — Dakar 2026 App

Internal team management web app for the Coronel Rally Team, built as a single-file HTML application.

## Features

- **Dashboard** — upcoming calendar dates, next race, crew availability, pending approvals
- **Calendar** — full 2026 schedule with collapsible months; colour-coded event categories
- **Tasks** — task management with status tracking and category filters
- **Tech** — car specs, tech info, parts inventory, catalogue
- **Team** — crew profiles and availability

## Work Categories

| Badge | Category | Description |
|-------|----------|-------------|
| 🟢 WP | Werkplaats | Workshop days |
| 🟠 CR7 | Buggy | CR7 buggy work |
| 🔵 Truck | Truck | Truck maintenance |
| 🟣 ALG | Algemeen | General tasks |
| 🩷 DAK | Dakar | Dakar preparation |

## Usage

Open `index.html` directly in any modern browser — no build step, no dependencies, no server required.

## Deployment

Can be hosted on any static hosting service (GitHub Pages, Netlify, Vercel, etc.).

### GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. App will be live at `https://<username>.github.io/<repo-name>/`

## Access / Roles

- **Viewer** — read-only access to all sections
- **Admin** — full access including task/calendar management (PIN protected)

## Tech Stack

- Vanilla HTML/CSS/JS — zero dependencies
- [Tabler Icons](https://tabler-icons.io/) via CDN
- Persistent storage via `window.storage` API (Claude.ai artifacts) — falls back gracefully in standalone use

---

*Coronel Rally Team · Dakar 2026*
