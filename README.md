# Sara Pineda Z – personal website

Quarto website published with GitHub Pages.

## Local preview
    quarto preview

## Publish
1. Create the repo `spinedaz.github.io` (or any name) and push this folder to `main`.
2. Run once: `quarto publish gh-pages` (creates the `gh-pages` branch).
3. GitHub → Settings → Pages → Source: branch `gh-pages`, folder `/ (root)`.
4. From then on every push to `main` republishes the site (see `.github/workflows/publish.yml`).

## Add a post
Create `posts/YYYY-MM-DD-title.qmd` with `title`, `date` and `categories` in the header.
