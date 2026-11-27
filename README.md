# dotam308.github.io

Personal site for Peter, Senior Software Engineer (Backend & Distributed Systems).

Live site: https://dotam308.github.io/

## Files

- `index.html` – the CV in English
- `vi/index.html` – the CV in Vietnamese
- `styles.css` – terminal-style theme with light and dark modes, phone and print styles
- `avatar.jpg` – profile photo

Plain HTML and CSS, plus a few lines of inline JavaScript for the theme toggle. There is no framework, build step, backend, analytics or external font.

## Publish with GitHub Pages

Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: **main**, folder **/ (root)** → Save.

The page follows the visitor's system light/dark setting; the toggle in the top bar overrides it and is remembered in the browser. A few lines of inline JavaScript handle only that toggle.

## Update

Edit both `index.html` and `vi/index.html` so the two languages stay in sync, then commit and push to `main`. When you change `styles.css`, bump the `?v=` number on its link in `index.html` so browsers load the new version.
