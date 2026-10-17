# Fatemeh Ziari — Portfolio

A bilingual English/German portfolio website, prepared for GitHub Pages.

## Publish

The included GitHub Actions workflow deploys the static site from `dist/` whenever a commit is pushed to `main`. In the repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**. The published address will be shown under **Settings → Pages** after the first successful deployment.

The workflow excludes the ChatGPT Sites hosting manifest from the published files. The site uses relative asset links, so it works both at the repository Pages address and on a custom domain.

## Local preview

Open `index.html` in a modern browser. Use the EN / DE control to change languages.
