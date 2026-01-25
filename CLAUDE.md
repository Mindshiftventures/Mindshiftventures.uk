# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Corporate placeholder website for Mindshift Ventures Ltd - a UK-based technology company. Currently a single-page static site with "Coming Soon" messaging.

## Architecture

This is a minimal static HTML site:
- `index.html` - Single-page placeholder with inline CSS and minimal JavaScript
- Vercel Speed Insights loaded via ES module from CDN
- No build process required - serves directly as static files

## Development

Open `index.html` directly in a browser or serve with any static server:
```bash
npx serve .
# or
python -m http.server 8000
```

## Deployment

Deployed on Vercel. Push to `main` branch triggers automatic deployment.

## Dependencies

The `package.json` exists solely for Vercel Speed Insights integration (loaded via CDN in the HTML, not bundled).
