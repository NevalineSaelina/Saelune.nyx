# Nemu's Sekai · Nemu 2.0

A responsive, privacy-conscious personal website with five languages (Traditional Chinese, English, Japanese, French, German), dreamy/dark theme switching, animated sections, interest and game lists, personality-spectrum section, favorite characters/series, and social links.

## Files
- `index.html` — semantic page structure and metadata
- `style.css` — responsive styles, dream/dark themes, animations
- `script.js` — language switching, theme persistence, mobile navigation, reveal animations
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing

## Preview locally
Open `index.html` in a browser. For best results, use a local static server (for example VS Code Live Server).

## Publish safely on GitHub Pages
1. Back up your existing repository first; do not delete or rename the old site.
2. Create a **new public repository**, e.g. `nemu-site-v2`.
3. Upload these files to the repository root.
4. Open **Settings → Pages**.
5. Under Build and deployment, select **Deploy from a branch**, choose `main` and `/(root)`, then Save.
6. Wait for deployment and use the URL GitHub Pages displays.

The project is static and has no backend or contact form. Language and theme preferences are stored in the visitor's browser local storage. Avoid adding personal details you do not want public. A public GitHub Pages site is not anonymous.
