# AI Website Builder (Test 1)

A single-file, no-code AI website builder prototype. Describe a website in plain language, and the app generates a full website using the Gemini API — then export it as a `.zip` or HTML file. Fully client-side, single `index.html`.

## Features

- Prompt-based website generation powered by the Gemini API
- Live preview pane with tab switching (editor / preview)
- Project workspace with new-project flow
- Export generated sites (ZIP download via JSZip)
- Marathi + English UI
- Single-file build — no bundler, no dependencies to install

## Tech Stack

- Single HTML file (HTML + Tailwind CDN + vanilla JS)
- Tailwind CSS (CDN)
- Lucide icons (CDN)
- JSZip (CDN)
- Gemini API for generation

## Quick Start

Just open `index.html` in a browser — or serve it:

```bash
npx serve .
```

Enter your Gemini API key in the app, type a prompt (e.g. "a portfolio site for a photographer"), and generate.

## Environment Variables

None in the repo. The app asks for a **Gemini API key** at runtime (entered by the user in the browser, never stored in the repo).

## Project Structure

```
├── index.html   # The entire app — UI, logic, export flow
└── README.md
```

## Deploy

Fully static — host `index.html` on any static host (GitHub Pages, Cloudflare Pages, Netlify).

---

Built by Girish Lade — https://ladestack.in
