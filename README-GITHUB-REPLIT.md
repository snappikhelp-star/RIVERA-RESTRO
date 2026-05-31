# GitHub / Replit Ready Project

## Upload to GitHub
1. Extract this ZIP.
2. Upload extracted files/folders to a new GitHub repository.
3. Do not upload node_modules, dist, .cache, .local.

## Import to New Replit
1. New Replit account -> Create Repl -> Import from GitHub.
2. Open Shell.
3. Run:

If pnpm-lock.yaml exists:
pnpm install
pnpm run build

If package-lock.json exists:
npm install
npm run build

If bun.lock exists:
bun install
bun run build

## Cloudflare Pages
For most Vite/React projects:
Build command: npm run build or pnpm run build
Build output directory: dist
Deploy command: leave empty
