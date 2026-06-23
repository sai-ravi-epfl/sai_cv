# Sai Sudharshan Ravi CV site

A self-contained personal website for GitLab Pages. It uses plain HTML and CSS, so there is nothing to install.

## Deploy to GitLab Pages

1. Create a new **public** GitLab project named `sai-cv`.
2. Upload every file from this folder, keeping the `public` directory and `.gitlab-ci.yml` at the repository root.
3. Commit to the default branch.
4. Wait for the CI pipeline to finish. GitLab Pages deploys the contents of `public`.
5. In GitLab, open **Deploy > Pages** to copy the exact published URL.

GitLab Pages supports plain HTML, CSS, and JavaScript sites that are built and published through GitLab CI/CD. The included CI configuration publishes the repository's `public` directory.

## Expected URL and QR code

This package assumes:

`https://saisudharshan2000.gitlab.io/sai-cv/`

The QR code in `public/assets/qr-code-assumed-site-url.png` contains that address. Before adding it to a poster, open the deployed website and confirm that the exact address is correct. If your GitLab username, group, or project name differs, regenerate the QR code using the exact Pages URL.

## Files

- `public/index.html` - the website
- `public/assets/styles.css` - the responsive styling
- `public/assets/sai-sudharshan-ravi.jpg` - cropped profile image from the supplied CV image
- `public/assets/Sai_Sudharshan_Ravi_CV.pdf` - downloadable PDF created from the supplied CV image
- `public/assets/qr-code-assumed-site-url.png` - poster-ready QR code for the assumed deployment address
- `.gitlab-ci.yml` - GitLab Pages deployment configuration

## Update content later

Edit the relevant text in `public/index.html`. Replace the CV PDF or portrait image in `public/assets` while keeping the file names, or update the matching links in `index.html`.
