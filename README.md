# የማይደርቅ አበባ — ASCII lily bouquet

A static site: an animated bouquet of lilies drawn with text characters on a canvas, with the Amharic line "የማይደርቅ አበባ" underneath. No build step.

## Publish with GitHub Pages
1. Create a new repository on GitHub.
2. Upload `index.html`, `style.css`, and `script.js` to the root of the repo.
3. Go to Settings → Pages. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, then save.
4. After a minute, your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Customize
- Colors: `COLOR` in `script.js` and `--bg` in `style.css`.
- Flower positions and sizes: the `lilies` and `buds` arrays in `script.js`.
- Motion is turned off for visitors who prefer reduced motion.
