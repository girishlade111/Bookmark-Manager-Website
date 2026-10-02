# Bookmark Manager Website

A single-file bookmark manager web app — save, search, edit, and organize your bookmarks in a clean interface with dark mode support. Everything runs client-side in the browser; bookmarks are stored in `localStorage`, so no account, server, or database is needed.

## Features

- Add bookmarks with title and URL
- Instant search across saved bookmarks
- Edit and delete bookmarks
- Dark mode toggle
- Import and export bookmarks (backup/restore)
- Persistent storage via `localStorage`
- Responsive, mobile-friendly layout
- Zero dependencies to install — one HTML file

## Tech stack

- HTML, CSS, vanilla JavaScript (single file: `index.html`)
- Tailwind CSS via CDN
- Lucide icons via CDN

## Quick start

No build step. Just open the file:

```bash
# Option 1: open directly in a browser
open index.html

# Option 2: serve locally
npx serve .
# or
python3 -m http.server
```

Then visit the shown URL.

## Project structure

- `index.html` — the entire app (markup, styles, logic)

## Deploy notes

Static site, deploys anywhere (GitHub Pages, Cloudflare Pages, Netlify) with zero configuration.

---

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)
