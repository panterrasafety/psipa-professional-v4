# Cloudflare Pages deployment

Use these settings:

- Framework preset: None (or Vite if available)
- Production branch: main
- Build command: npm run build
- Build output directory: dist
- Root directory: leave blank
- Environment variable: NODE_VERSION = 22.16.0

Do not use `npx wrangler deploy` for this Pages project.
