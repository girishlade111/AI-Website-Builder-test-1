# AI Website Builder (Test 1)

A no-code website builder prototype — an AI-assisted web app that generates and previews websites in the browser. Built in Marathi-first UI ("नो-कोड वेबसाइट बिल्डर") as a prototype of the LS Build concept.

## Features

- In-browser website builder UI with live preview
- Editor pane with syntax-highlighted code editing
- Export the generated site as a `.zip` file (JSZip + FileSaver)
- Dark themed, Tailwind CSS styled interface with Lucide icons
- Fully client-side — no build step, no backend

## Tech Stack

- Single-file HTML app
- Tailwind CSS (CDN)
- Lucide icons
- JSZip 3.10.1 + FileSaver.js for ZIP export
- Monaco-style editor styling

## Quick Start

No build required — this is a plain static HTML file.

- Open `index.html` directly in a browser, or
- Serve locally:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Project Structure

```
├── index.html   # Entire app (markup, styles, logic) — single file
└── README.md
```

## Deploy

Static single-file site — serve from any static host (GitHub Pages, Cloudflare Pages, Netlify).

---

Built by Girish Lade — https://ladestack.in
