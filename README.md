# Personal Webpage

My personal webpage built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Setup

Install dependencies using [uv](https://docs.astral.sh/uv/):

```bash
uv sync
```

## Development

To preview the site locally:

```bash
uv run mkdocs serve
```

Then visit `http://127.0.0.1:8000` in your browser.

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the `main` branch.

You can also manually build and deploy:

- Build the site

```bash
uv run mkdocs build
```

- Deploy to GitHub Pages

```bash
uv run mkdocs gh-deploy
```
