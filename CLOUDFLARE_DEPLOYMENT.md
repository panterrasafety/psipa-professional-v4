# Cloudflare deployment

1. Upload all project files to the GitHub repository root.
2. Remove any old `package-lock.json` or `yarn.lock` before uploading this release.
3. In Cloudflare Pages use:
   - Framework preset: None
   - Build command: npm run build
   - Build output directory: dist
   - Root directory: blank
   - NODE_VERSION: 20.19.0
4. Commit to `main`. Automatic deployment should begin.
