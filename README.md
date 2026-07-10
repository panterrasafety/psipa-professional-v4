# PSIPA Professional v4.3 — Final Verified Release

This release preserves the complete working PSIPA v3.3 assessment workflow in a Vite/Cloudflare Pages deployment package. The application logic remains consolidated in `index.html` to preserve all proven field functionality while using Vite for repeatable production builds.

## Included

- Complete assessment workflow
- Smart Process Wizard and suggested hazards
- Work Front Hazard Review & Critical Control Verification
- Equipment Type and Hazard Source
- Hazard-specific Direct, Indirect, and Site-Specific control pickers
- Up to five selected controls per category
- SIF review, deficiencies, photos, signatures, save/load, import/export, email summary, and PDF/print
- PWA manifest, icons, and offline service worker

## Verified commands

```bash
npm ci --no-audit --no-fund
npm run build
```

## Cloudflare Pages settings

- Framework preset: None
- Build command: `npm run build`
- Build output directory: `dist`
- Root directory: blank
- `NODE_VERSION`: `20.19.0`

Upload the contents of this folder to the root of the GitHub repository. Keep `package.json` and `package-lock.json`; remove any old `yarn.lock`.
