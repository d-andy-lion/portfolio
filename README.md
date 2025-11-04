# Portfolio — static site

This repository contains a minimal static portfolio site built with plain HTML and CSS. It's ready to publish on GitHub Pages.

Files added

- `index.html` — main page
- `css/styles.css` — site styles
- `assets/` — folder for images and other assets (empty placeholder)

Quick start

1. Edit `index.html` to add your name, bio, projects and links.
2. Add any images you want into `assets/` and reference them from the HTML.
3. Commit and push to GitHub.

Enable GitHub Pages

1. In your repository on GitHub, go to Settings → Pages.
2. Under "Build and deployment", choose "Source" → Branch: `main` and Folder: `/ (root)` and save.
3. GitHub will publish your site at `https://<your-username>.github.io/<repo-name>/` (it may take a minute).

If you'd prefer to publish from a `docs/` folder instead, move `index.html` and `css/` into a `docs/` directory and select `main`/`docs` as the Pages source.

Optional: automatic deploys

If you later switch to a generator (Vite, Next.js, etc.), I can add a GitHub Action to build and deploy to `gh-pages` automatically.

Next steps I can do for you

- Customize the design and typography
- Add project-specific pages and thumbnails
- Add a contact form using Formspree or Netlify Forms
- Add a workflow to auto-publish from `main`/`docs` or `gh-pages`
