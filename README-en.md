# Lucas Pio — Linktree

🇧🇷 [Leia em português](./README-pt-br.md)

A responsive personal link hub that brings together my company, contact channels, and work in one place.

## Purpose

This repository contains a self-contained landing page that acts as my digital business card. Its clean, responsive card layout highlights O Ponto Web and makes it easy for potential clients to get in touch.

It links out to:

- **O Ponto Web** — my web development company
- **WhatsApp** — quick conversation
- **Email** — direct contact
- **GitHub** — my code and projects

The page also includes semantic navigation, visible keyboard focus states, reduced-motion support, and a mobile layout.

## Tech stack

Just one HTML file. There is no build step, framework, package manager, or JavaScript — open it in a browser and it works.

- HTML5
- CSS3
- `DM Sans` — body and interface text
- `Manrope` — headings and brand marks

Both fonts are loaded from Google Fonts via CDN.

## Project structure

```
.
├── index.html          # the landing page and its styles
├── README.md           # language selector
├── README-en.md        # English documentation
├── README-pt-br.md     # Brazilian Portuguese documentation
└── LICENSE             # MIT license
```

## Running locally

Open `index.html` directly in a browser. To serve it over HTTP instead, run a static server from the project directory, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customizing

Everything lives in `index.html`:

| To change | Look in |
|---|---|
| Colors | `:root { ... }` inside `<style>` |
| Page title and search description | `<title>` and `<meta name="description">` |
| Name and introduction | `<header class="profile">` |
| Featured company | `<a class="company-card">` |
| Contact and project links | `<nav class="links">` |
| Footer text | `<footer>` |

## Deploying

Any static host works, for example:

- **GitHub Pages** — push the repository and enable Pages in the repository settings.
- **Vercel** or **Netlify** — drag and drop the folder.

## Contact

- GitHub: [github.com/LukasPio](https://github.com/LukasPio)
- Email: contato.lukaspio@gmail.com
- WhatsApp: [wa.me/5511945462692](https://wa.me/5511945462692)

## Feel free to use it

Feel free to fork or copy this code and swap in your own information — name, bio, links, and colors. No need to ask permission or credit me, just make it yours.

This project is available under the [MIT License](./LICENSE).
