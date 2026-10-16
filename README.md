# Brettlee — Portfolio

A responsive, dark, textured personal portfolio built with plain HTML, CSS, and JavaScript. No build step or package installation is required.

## Preview locally

1. Download or clone this repository.
2. Open `site/index.html` in a browser. For best local testing, use VS Code's Live Server extension.

## Publish with GitHub Actions + GitHub Pages

1. Create a GitHub repository (for example, `portfolio`).
2. Put all files from this folder in the repository root, keeping the `.github/workflows/deploy.yml` path intact.
3. Commit and push the files to the `main` branch.
4. In GitHub, open **Settings → Pages** and set **Build and deployment → Source** to **GitHub Actions**.
5. Open the repository's **Actions** tab. The `Deploy portfolio to GitHub Pages` workflow should run automatically after your push.
6. Once the workflow succeeds, open **Settings → Pages** to find your published URL.

Every push to `main` redeploys the site. You can also run the workflow manually from the Actions tab.

## Personalize before publishing

- Update the project descriptions and statuses in `site/index.html` so they match what you have actually shipped.
- The email currently points to `brettleevector@gmail.com`.
- Replace the generic GitHub and LinkedIn profile links in the footer with your own profile URLs.
- Add real project/repository links when the projects are ready. Current project cards point to the contact section instead of pretending to link to live repositories.
- Update the page title, meta description, and social preview text in the `<head>` if your positioning changes.

## Structure

```text
.
├── .github/
│   └── workflows/
│       └── deploy.yml
├── site/
│   ├── index.html
│   └── assets/
│       ├── styles.css
│       └── script.js
└── README.md
```

## Features

- Responsive layout and mobile navigation
- Dark charcoal theme with grain texture and acid-lime accents
- Project category filters
- Scroll reveal effects with reduced-motion support
- Accessible skip link, focus styles, semantic sections, and ARIA labels
- GitHub Pages deployment via GitHub Actions
