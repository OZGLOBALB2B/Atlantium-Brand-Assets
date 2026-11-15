# Atlantium Brand Guidelines

Static brand guidelines site for Atlantium Technologies, prepared by OZ Global B2B.

Sources: Atlantium Guidelines 2023 (V3), Brand Guidelines & Tone of Voice 2025, the Atlantium Website UI (Figma, 2026) and Atlantium's master logo and icon files.

## Contents

```
index.html              The whole site (HTML, CSS and JS in one file)
assets/img/             Photos and product images used by the page
downloads/master/       Original Illustrator master files (RGB and CMYK)
downloads/*.zip         Ready-made packs: logo files and the icon set
.nojekyll               Tells GitHub Pages to serve files as they are
```

Logo and icon downloads (SVG, PNG, PDF, ZIP) are generated in the browser from the artwork inside `index.html`, so they need no build step.

## Publish

### Netlify (recommended)
1. Push this folder to a GitHub repository.
2. In Netlify: **Add new site → Import from Git**, pick the repository.
3. Leave the build command empty and set the publish directory to `/`.

### GitHub Pages
1. Push this folder to a GitHub repository.
2. **Settings → Pages → Build and deployment**: Source *Deploy from a branch*, branch `main`, folder `/ (root)`.

## Notes
- Open the site through a web server, not by double-clicking `index.html`; the moving water in the hero needs it.
- Fonts load from Google Fonts (DM Serif Display, Poppins). Ploni (Hebrew) is a licensed font and is not included.
