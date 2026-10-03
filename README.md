# Dagvik legal and product site

Static GitHub Pages site for the Dagvik landing page, Terms of Service and Privacy Policy.

- Landing page: `https://arbalester.github.io/stridetab-legal/`
- Product preview: `https://arbalester.github.io/stridetab-legal/preview.html`
- Privacy Policy: `https://arbalester.github.io/stridetab-legal/privacy.html`
- Terms of Service: `https://arbalester.github.io/stridetab-legal/terms.html`

The repository keeps its original name `stridetab-legal`, so the published URLs above stay valid. Renaming the repository changes them; then update `VITE_TERMS_URL` and `VITE_PRIVACY_URL` of the extension.

## Publish with GitHub Pages

1. Push this directory to the repository's `main` branch.
2. In the repository settings, open **Pages** and publish from the root of `main`.
3. Use the resulting HTTPS URLs in `VITE_TERMS_URL` and `VITE_PRIVACY_URL` before building the extension.

`privacy.html` mirrors `docs/PRIVACY.md` of the extension repository; update both together. Before publishing, replace the controller and privacy-email placeholders in `privacy.html`.

The site has no JavaScript, analytics, forms or external runtime dependencies. It is fully self-contained static HTML and CSS.
