# haryenjindan.github.io

A simple static site hosted with GitHub Pages. It includes a front page and a pricing page, built with plain HTML and Bootstrap via CDN.

## Live site

- https://haryenjindan.github.io

## Project structure

- `/index.html` — Front page with a link to the pricing page. Loads Bootstrap 5 from a CDN. Contains snippets for Intercom and Segment (Crisp and Drift examples are present in comments).
- `/pricing/index.html` — Pricing page with the same Bootstrap setup and tracking snippets.

## Local development

Because this is a static site, you can open the HTML files directly in a browser. For a closer match to production (and to avoid CORS quirks), run a tiny local web server:

```bash
# Option 1: Python (built-in on most systems)
python3 -m http.server 8080
# then visit http://localhost:8080

# Option 2: Node users (if you have npm)
npx serve -l 8080
```

## Deployment

This repository is configured as a user site (`<user>.github.io`), so pushes to the default branch (`master`) are deployed automatically by GitHub Pages.

## Contributing

1. Create a branch from `master`.
2. Make your changes (keep diffs minimal).
3. Open a pull request and request review.
