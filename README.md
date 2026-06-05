# RamanaGR.github.io

Personal website for **Ramana Gangarao**.

## Live
- GitHub Pages: `https://ramanagr.github.io`

## Development
- Static site (HTML/CSS/JS) hosted via GitHub Pages.
- Tailwind utilities are compiled to `css/style.css` (not loaded from the CDN). GitHub Pages does not run a build step, so the compiled file must be committed.

### Rebuild CSS after editing Tailwind classes

If you change utility classes in `index.html`, regenerate and commit the stylesheet:

```bash
npm run build:css
```

Then commit `css/style.css` along with your HTML changes before pushing.

