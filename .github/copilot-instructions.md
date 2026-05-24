# Copilot Instructions

## Build and publish

- This repository currently has no build, test, or lint tooling.
- The site is published as a plain static page from the repository root via GitHub Pages.

## Architecture

- `index.html` is the whole application. There is no framework, bundler, or asset pipeline.
- GitHub Pages serves the root `index.html` directly, so changes to the page are made in-place and pushed to `main`.

## Conventions

- Keep the site self-contained unless the repository intentionally grows beyond a single-page static site.
- Prefer simple HTML and inline CSS for small changes so the page remains easy to publish through GitHub Pages without extra tooling.
