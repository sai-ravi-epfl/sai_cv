# Sai Sudharshan Ravi CV

This repository contains a self-contained CV website for GitLab Pages. It uses
plain HTML and CSS, so there are no package installs or build steps.

## Project layout

- `public/index.html` - the CV website
- `public/assets/styles.css` - responsive styling
- `public/assets/Sai_Sudharshan_Ravi_CV.pdf` - downloadable CV PDF
- `public/assets/sai-sudharshan-ravi.jpg` - profile image
- `public/assets/favicon.svg` - browser icon
- `.gitlab-ci.yml` - GitLab Pages deployment pipeline

## Preview locally

Open `public/index.html` in a browser. Because the site is static and all assets
use relative paths, no local server is required.

## Deploy on GitLab Pages

1. Push this repository to GitLab.
2. Wait for the `pages` CI job to finish on the default branch.
3. Open **Deploy > Pages** in GitLab and use the published URL shown there.

The pipeline publishes the contents of `public/`, which is the directory GitLab
Pages expects for a static site artifact.

## Updating the CV

Edit the text in `public/index.html`. Replace the PDF or portrait in
`public/assets/` while keeping the same filenames, or update the matching links
in `index.html`.

## QR code

`public/assets/qr-code-assumed-site-url.png` and
`public/assets/qr-code-url.txt` are optional helper files. They contain an
assumed URL, so regenerate them after deployment if the Pages URL differs.
