# CMS Integration (Decap / Netlify CMS)

## Objective

Add a Git-based CMS to manage portfolio content using Markdown files.

## Why a CMS in a Portfolio Project

- Simulates a real-world workflow
- Separates content from code
- Allows non-technical editing
- Common industry practice

## Technology

- Decap CMS (formerly Netlify CMS)
- Git-based content management
- Markdown files stored in `src/content`

## Challenges Encountered

The initial configuration used `git-gateway`, which only works
when the project is hosted on Netlify.

This caused the CMS not to work in local development.

## Solution

For development and academic evaluation purposes, the backend
was changed to `local`, allowing the CMS to work locally
without external services.

The Netlify backend configuration is kept for future production use.

## Content Structure

The CMS writes content into:

- `src/content/news`
- `src/content/work`
- `src/content/pages`

Astro reads these Markdown files at build time.

## Result

The CMS is accessible at `/admin` and can manage content
without modifying the application code.
