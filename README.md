# Dagvik legal and product site

Static GitHub Pages site for the Dagvik landing page, Terms of Service and Privacy Policy.

- Landing page: `https://arbalester.github.io/dagvik-legal/`
- Product preview: `https://arbalester.github.io/dagvik-legal/preview.html`
- Privacy Policy: `https://arbalester.github.io/dagvik-legal/privacy.html`
- Terms of Service: `https://arbalester.github.io/dagvik-legal/terms.html`

The repository was renamed from `stridetab-legal` to `dagvik-legal`. GitHub Pages does not redirect the old project URL, so the extension's `VITE_TERMS_URL` and `VITE_PRIVACY_URL` defaults point to the new address.

## Publish with GitHub Pages

1. Push this directory to the repository's `main` branch.
2. In the repository settings, open **Pages** and publish from the root of `main`.
3. Use the resulting HTTPS URLs in `VITE_TERMS_URL` and `VITE_PRIVACY_URL` before building the extension.

`privacy.html` mirrors `docs/PRIVACY.md` of the extension repository; update both together. Before publishing, replace the controller and privacy-email placeholders in `privacy.html`.

The site has no JavaScript, analytics, forms or external runtime dependencies. It is fully self-contained static HTML and CSS.
