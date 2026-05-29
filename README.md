# Luciano Bicaku — Portfolio

Personal portfolio site for [luciano-bicaku.vercel.app](https://luciano-bicaku.vercel.app).

Single-file HTML/CSS/JS — no build step, no dependencies.

## Stack

- Vanilla HTML, CSS, JavaScript
- [Instrument Serif / Sans / JetBrains Mono](https://fonts.google.com) via Google Fonts
- Deployed on Vercel

## Structure

```
porfolio/
├── portfolio.html   # entire site lives here
└── assets/
    └── luciano.jpg  # portrait photo
```

## Running locally

```bash
# any static server works, e.g.:
npx serve .
# or just open portfolio.html directly in a browser
```

## Features

- Light / dark theme toggle (persisted via postMessage protocol)
- Scroll-reveal animations via IntersectionObserver
- Animated hero word entrance
- Cursor blob follower
- CV download (generates a `.txt` file client-side)
- Marquee tech strip
- Projects rendered from a JS data array

## SEO

- `meta description`, `canonical`, Open Graph, Twitter Card
- JSON-LD `Person` structured data
- `<noscript>` project list fallback for crawlers

## Deployment

Push to `main` → Vercel auto-deploys. No config needed beyond the Vercel project connection.

---

© 2026 Luciano Bicaku
