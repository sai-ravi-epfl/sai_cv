# Sai Sudharshan Ravi CV

This repository contains a self-contained CV website for GitHub Pages. It uses
plain HTML and CSS, so there are no local package installs or build steps.

## Project layout

- `public/index.html` - the CV website
- `public/assets/styles.css` - responsive styling
- `public/assets/Sai_Sudharshan_Ravi_CV.pdf` - downloadable CV PDF
- `public/assets/sai-sudharshan-ravi.jpg` - profile image
- `public/assets/favicon.svg` - browser icon
- `.github/workflows/pages.yml` - GitHub Pages deployment workflow

## Preview locally

Open `public/index.html` in a browser. Because the site is static and all assets
use relative paths, no local server is required.

## Deploy on GitHub Pages

1. Create a GitHub repository named `sai_cv`.
2. Push this repository to GitHub.
3. In GitHub, open **Settings > Pages** and set the source to **GitHub Actions**.
4. Wait for the `Deploy CV to GitHub Pages` workflow to finish.

Expected public URL:

`https://sai-ravi-epfl.github.io/sai_cv/`

The workflow publishes the contents of `public/`.

## Updating the CV

Edit the text in `public/index.html`. Replace the PDF or portrait in
`public/assets/` while keeping the same filenames, or update the matching links
in `index.html`.

## QR code

`public/assets/qr-code-assumed-site-url.png` and
`public/assets/qr-code-url.txt` target the expected GitHub Pages URL. Regenerate
them after deployment if the published URL differs.
