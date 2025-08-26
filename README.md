# experiment--gh-pages-local

This repository was created to experiment with deploying a simple React (Vite) project to GitHub Pages using the **gh-pages CLI** package.

## What I tried
- Installed `gh-pages` and added `predeploy` / `deploy` scripts in `package.json`
- Built the project locally (`npm run build`)
- Deployed the contents of `dist/` to the `gh-pages` branch via `npm run deploy`

## What I learned
- GitHub Pages can host static files, but React projects must be built first
- Using the CLI is convenient for quick tests, but doesn’t feel like a real development workflow
- Client-side routing still requires workarounds (e.g. copying `index.html` to `404.html`)
