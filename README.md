# PSIPA Professional v4.0 – Frontend Rebuild

This release converts PSIPA from a single large HTML file into a proper React + Vite frontend project while preserving the approved compact 11 pt field-app layout and workflow.

## What is included

- React + Vite project structure
- Mobile-first compact layout
- PWA manifest and service worker
- Smart Process Wizard
- High Energy Hazard selection
- Work Front Hazard Review & Critical Control Verification
- Equipment Type and Hazard Source fields
- Hazard-specific Direct, Indirect, and Site-Specific control pickers
- Up to 5 controls per control group
- SIF Review Confirmation
- Local auto-save using browser local storage
- Executive Summary report view
- PDF/Print support

## Development

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

Cloudflare build settings:

- Framework preset: Vite
- Build command: `npm run build`
- Build output directory: `dist`

## Version

PSIPA Professional v4.0 – Frontend Rebuild
