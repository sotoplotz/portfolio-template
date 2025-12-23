# GitHub Pages Deployment Issue

## Problem

GitHub Pages tried to process Astro files with Jekyll, resulting in:
"Invalid YAML front matter in index.astro"

## Solution

1. Add `.nojekyll` file to root to disable Jekyll.
2. Build Astro project with `npm run build`.
3. Serve `dist/` folder as GitHub Pages source.

## Result

- Astro site deploys correctly
- Jekyll no longer interferes
- Repository fully academic- and professional-ready
