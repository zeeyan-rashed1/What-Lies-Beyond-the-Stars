# What Lies Beyond the Stars — Volume One

**Official QORA digital reading edition · First Edition · 2026**

A responsive publication website for *What Lies Beyond the Stars: The Qur’an, the Big Bang, and the Search for the Edge of Reality*, by The QORA Editorial Circle.

## Live website

https://zeeyan-rashed1.github.io/What-Lies-Beyond-the-Stars/

The address becomes available after the repository's GitHub Pages deployment finishes successfully.

## Repository structure

```text
.
├── index.html
├── README.md
├── chapters.json
├── favicon.svg
├── .nojekyll
└── assets/
    ├── cover.jpg
    └── what-lies-beyond-the-stars-volume-one.pdf
```

## Publish on GitHub Pages

This repository already has a GitHub Actions Pages workflow. Keep the existing `.github/workflows/static.yml` file.

1. Upload these package contents to the repository root, preserving the `assets/` folder.
2. Commit the changes to the `main` branch.
3. Open **Settings → Pages** and confirm the source is **GitHub Actions**.
4. Open **Actions** and confirm **Deploy static content to Pages** completes successfully.
5. Open the live website link above.

## Reader and website features

- Responsive editorial layout for desktop, tablet and mobile.
- Custom QORA book cover and publication information.
- Interactive PDF.js reading interface.
- Previous/next page navigation and page counter.
- Zoom controls and fit-to-width.
- Chapter shortcuts, thumbnails and progress indicator.
- Search across selectable PDF text.
- Last-read page saved locally in the browser.
- Direct PDF download and fallback link.
- Search and social-sharing metadata.

## Technical note

The enhanced reader loads PDF.js from cdnjs and therefore requires an internet connection. The direct PDF link remains available as a fallback. Keep the PDF and cover at the exact paths shown above because the page uses relative `assets/` URLs.

## Rights

The package deliberately includes no open-source licence. The manuscript states that copyright belongs to QORA. Publish and distribute the materials only if QORA controls the relevant rights or has permission to do so.
