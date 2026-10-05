# Nodeworks

Business-card website for Nodeworks: fast, high-quality websites for small businesses. Pricing is agreed per project.

Plain static HTML/CSS/JS with no build step. Languages: Armenian, Russian and English.

## Files

- `index.html`: page structure, with the English text as the default
- `script.js`: Armenian and Russian translations (`I18N`) and contact links (`CONTACT`)
- `styles.css`: design tokens, layout, and light/dark themes

## Before launch

- [ ] Replace the placeholder contact links in `script.js` (`CONTACT`)
- [ ] Have a native speaker proofread the Armenian and Russian texts
- [ ] Register the domain (e.g. `nodeworks.am`) and Instagram handle
- [ ] Add 2–3 demo client sites to a portfolio section

## Run locally

```bash
python3 -m http.server 8080
```

## Deploy

Push to GitHub and connect the repository to Cloudflare Pages (free). There is no build command, and the output directory is `/`.
