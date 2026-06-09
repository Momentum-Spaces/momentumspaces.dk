# Momentum Spaces — website

The website for **Momentum**, a small coworking space for young entrepreneurs at
Marselisborg Lystbådehavn in Aarhus. Live at **https://momentumspaces.dk**.

It is a plain, fast, **static** website — just HTML, CSS, fonts and images. No build
step, no frameworks, no JavaScript required.

## How it gets published
The site is hosted for free on **GitHub Pages**. Every time a change is pushed to the
`main` branch, GitHub automatically re-publishes the live site within a minute or two.

## Editing the site
- **Text** lives in `index.html` — find the Danish sentence you want to change and edit it.
- **Styling** lives in `assets/css/main.css`.
- **Photos** live in `assets/photos/` — replace a file with a new one of the same name to
  swap a picture (keep each one reasonably small, ideally under ~500 KB).
- **Logos, favicon, social image** live in `assets/img/`. **Fonts** live in `assets/fonts/`.

## Folder layout
- `index.html` — the whole page
- `assets/css/main.css` — fonts + design tokens + layout + the spinning orbit mark
- `assets/fonts/` — Aktifo A (headlines) + Hanken Grotesk (body text), self-hosted
- `assets/img/` — logos, favicon, social-share image
- `assets/photos/` — the photography
- `CNAME` — tells GitHub Pages to serve the site on momentumspaces.dk

## Preview it on your own computer (optional)
Open this folder in a terminal and run `python3 -m http.server 8000`, then visit
http://localhost:8000 in your browser.

---
Built from the Momentum design system.
