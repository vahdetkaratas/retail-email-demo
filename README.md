# Retail Email Portfolio Demo

A fictional Czech-language beauty & personal care retail newsletter built as a portfolio sample. **Not affiliated with TETA or any other retailer.** Prices, product names, and offers are illustrative, not real promotions.

## Files
- `index.html` — responsive portfolio presentation with desktop/mobile viewport switch.
- `email.html` — stand-alone HTML email sample, table-based layout and inline CSS.
- `assets/*.png` — original, locally generated illustrative product mockups.

## Local preview
Open `index.html` in a modern browser. No build tools, package installs, paid services or external libraries required. Open `email.html` for the email itself.

## Publish later on GitHub Pages
1. Create a public repository called `retail-email-demo`.
2. Upload `index.html`, `email.html`, `README.md` and the complete `assets/` folder.
3. Open Settings → Pages → Deploy from a branch → `main` / `(root)`.
4. GitHub Pages provides the live URL. **The project is not published yet.**

## Production caveats
- All images are local relative paths for the browser and GitHub Pages demo. In a real email, replace them with fully-qualified HTTPS URLs hosted on a public image server or email service.
- Buttons/links are illustrative. No real e-commerce destination, tracking or unsubscribe functionality is connected. The demo's hero CTA is an in-page anchor and is not guaranteed to work in email clients.
- Table layout, inline styles, preheader and alt text demonstrate email conventions, but **Gmail, Outlook and other email clients have not been tested**. Responsive behavior is demonstrated in a modern browser, not validated inbox rendering.
- Real marketing email would require sender identity, legally required subscription/unsubscribe handling, privacy compliance, and client testing.

Created as an independent, fictional portfolio project (2026).