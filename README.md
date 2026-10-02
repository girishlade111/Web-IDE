# Web-IDE

A browser-based Web IDE that lets you generate websites with natural language. A single-page app with an embedded code editor, live preview, and project export — all running client-side, no backend required.

## Features

- **AI-style natural-language site generation** — describe a website and get starter HTML/CSS/JS
- **Embedded code editor** (Monaco Editor, the same engine that powers VS Code)
- **Live preview** of your site as you type, with dark/light theme toggle
- **Export your project** as a ZIP file (via JSZip)
- **Fully client-side** — no sign-up, no server, works offline after first load

## Tech Stack

- HTML5 / CSS3 / JavaScript (vanilla)
- Tailwind CSS (CDN)
- Monaco Editor 0.44.0 (CDN)
- JSZip 3.10.1 for project export

## Quick Start

Open `index.html` in any modern browser — no build step, no dependencies to install:

```bash
# Option 1: just double-click index.html
# Option 2: serve locally
npx serve .
```

## Project Structure

```
Web-IDE/
├── index.html   # Entire app: editor UI, preview pane, export logic
└── README.md
```

## Deploy

Static single-file site — deploy anywhere: GitHub Pages, Cloudflare Pages, Netlify, or any static host.

---

Built by Girish Lade — [ladestack.in](https://ladestack.in)
