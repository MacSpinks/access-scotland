# Access Scotland

React/Vite rebuild of the Access Scotland website, redesigned from the live Wix site into a mobile-first single-page experience.

## Local development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

The production output is written to `dist/`.

## Netlify

This project is configured for an initial Netlify deploy with `netlify.toml`.

- Build command: `npm run build`
- Publish directory: `dist`
- Node version: `22.12.0`

## Current notes

- The gallery is currently powered by static data in `src/siteData.js`.
- `Second Mission Trip` still links to the live archive while that album import is unfinished.
- The mailing list form is visual-only right now and still needs a real provider hookup before launch.
- A future admin/photo-management flow can be layered in without rebuilding the front end structure.
