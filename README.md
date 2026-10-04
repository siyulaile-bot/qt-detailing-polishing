# QT Detailing Polishing

Single-page landing site for **QT Detailing Polishing** — a mobile / house-call car detailing service.

> “Hahhh...Baru laa kemahh..”

## What's inside

| File | Purpose |
|------|---------|
| `index.html` | The entire site — HTML, CSS and a tiny bit of JS. No build step, no dependencies. |
| `BRAND ICON.webp` | Brand image used in the hero section. |

## Sections

- **Hero** — business name, house-call tagline and a prominent WhatsApp CTA (`https://wa.me/60135062711`)
- **Car Wash & Detailing** — 3-tier comparison: Basic / Premium / QTD Premium with Small · Medium · Large pricing (promo prices shown struck-through against originals)
- **Car Seat Cleaning** — Eco vs QTS packages, steam callout, add-on price list
- **Contact** — TikTok, Instagram, Facebook and WhatsApp links

The WhatsApp button is sticky (floating pill on desktop, full-width bar on mobile) since it's the main conversion action.

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Deploy (GitHub Pages)

1. Push to this repo.
2. GitHub → **Settings → Pages** → Source: **Deploy from a branch** → `main` / `root`.
3. The site goes live at `https://siyulaile-bot.github.io/qt-detailing-polishing/`.

Any static host works too (Netlify, Cloudflare Pages) — just upload the folder as-is.
