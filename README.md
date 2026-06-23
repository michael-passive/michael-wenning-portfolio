# themichaelwenning.com

Personal portfolio for Michael Wenning — Founder & AI Product Leader.

A single, self-contained static page (`index.html`): HTML + CSS + vanilla JS, no build step.
Fonts load from Google Fonts; all other visuals are CSS/SVG. All motion respects
`prefers-reduced-motion`.

## Hosting

Served via **GitHub Pages** at the custom domain in `CNAME` (`www.themichaelwenning.com`).
Any push to `main` deploys automatically.

## Files

- `index.html` — the site (single source of truth for layout, copy, and animation).
- `Michael_Wenning_Resume.pdf` — resume; linked by the "Download resume" buttons.
- `Michael_Wenning_Resume.docx` — original Word version, kept for reference.
- `CNAME` — custom domain for GitHub Pages.
- `.nojekyll` — disables Jekyll processing.

## Local preview

Open `index.html` directly in a browser, or run `python3 -m http.server` in this folder.
