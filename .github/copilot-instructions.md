# Copilot Instructions

## Build and publish

- This repository currently has no build, test, or lint tooling.
- The site is published as a plain static page from the repository root via GitHub Pages.
- The page styling uses MDB UI Kit from CDN, which provides a Material Design layer on top of Bootstrap 5.

## Architecture

- `index.html` is the whole application. There is no framework, bundler, or asset pipeline.
- GitHub Pages serves the root `index.html` directly, so changes to the page are made in-place and pushed to `main`.
- External UI dependencies are loaded from CDN in `index.html` rather than installed locally.

## Conventions

- Keep the site self-contained unless the repository intentionally grows beyond a single-page static site.
- Prefer Bootstrap 5 Material components and utility classes first, with only small local CSS overrides in `index.html`.
