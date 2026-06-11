# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static HTML/CSS landing page for Dingo Axis, an ecommerce data and reporting service. No build tools, frameworks, or dependencies.

## Local Development

Open `index.html` directly in a browser, or serve with any static file server:

```sh
python3 -m http.server 8080
```

## Deployment

Hosted on GitHub Pages with a custom domain (`CNAME` → `dingoaxis.com`). Pushing to `main` redeploys automatically.

## Architecture

Two source files:

- **`index.html`** — Single-page layout using `<main>`, `<section>`, and `<aside>`
- **`style.css`** — CSS Grid layout (3-column desktop, 1-column mobile at 800px breakpoint), dark theme (`#0f1115` background, `#d7dae0` text)

Contact email: `hello@dingoaxis.com`
