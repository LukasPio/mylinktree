# Lucas Pio — Linktree

A personal link-in-bio page with a terminal-inspired look, built to bring all my contact channels and work together in one place — and help me land new freelance clients.

## Purpose

This repository holds a single, self-contained landing page that acts as my digital business card. Instead of a generic list of buttons, it's styled like a code editor terminal session, which fits the audience it's meant for: people looking to hire a developer.

It links out to:

- **GitHub** — my code and past projects
- **Email** — direct contact
- **WhatsApp** — quick message
- **Portfolio** *(coming soon)* — a future page aggregating every project I've built or sold

## Tech stack

Just one HTML file. No build step, no framework, no JavaScript logic — open it and it works.

- `JetBrains Mono` — terminal-style headings and UI text
- `Inter` — body copy (the bio)

Both fonts are loaded from Google Fonts via CDN.

## Project structure

```
.
├── lucas-pio-linktree.html   # the page itself
└── README.md
```

## Customizing

Everything lives in `lucas-pio-linktree.html`:

| To change | Look in |
|---|---|
| Colors | `:root { ... }` inside `<style>` |
| Name / title | `.name` and `.role` classes |
| Bio text | `<div class="bio">` block |
| Links | `<div class="links">` section |

### Turning on the portfolio link

Once the portfolio page is live, replace:

```html
<span class="link disabled" aria-disabled="true">
```

with:

```html
<a class="link" href="https://your-url-here.com" target="_blank" rel="noopener noreferrer">
```

and drop the `<span class="badge">coming soon</span>` line.

## Deploying

Any static host works, for example:

- **GitHub Pages** — rename the file to `index.html`, push it to a repo, and enable Pages in the repo settings.
- **Vercel** or **Netlify** — drag and drop the folder.

## Contact

- GitHub: [github.com/LukasPio](https://github.com/LukasPio)
- Email: contato.lukaspio@gmail.com
- WhatsApp: [wa.me/5511945462692](https://wa.me/5511945462692)

## Feel free to use it

Feel free to fork or copy this code and swap in your own information — name, bio, links, and colors. No need to ask permission or credit me, just make it yours.
