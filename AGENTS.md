# Parry Electronics Repair - Static Site

## Project Overview
Simple static HTML/CSS website for an electronics repair business. No build tools, no package manager, no tests.

## Structure
- `index.html` - Main page (entry point)
- `style.css` - Stylesheet (uses CSS custom properties for theming)
- `SVGs/` - Brand logo SVGs (PR_16PIN_SVG.svg, PR_8PIN_SVG.svg)
- `STYLE_GUIDE.md` - Brand colors, typography, spacing guidelines

## Deployment
- GitHub Actions (`.github/workflows/pages.yml`) deploys to GitHub Pages on push to `main`
- Deploys entire repo root (`path: ./`)

## Development
- Open `index.html` directly in browser (no server required)
- No build/lint/test commands exist

## Key Conventions
- Brand colors defined as CSS custom properties in `style.css` (matching `STYLE_GUIDE.md`)
- Fonts: Space Grotesk (headings), Inter/Segoe UI (body) via Google Fonts
- Single inline `<script>` in `index.html` for copy-to-clipboard functionality