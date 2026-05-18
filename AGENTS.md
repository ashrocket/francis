# Francis Codex Notes

## Source of Truth

- This repo owns the web game deployed at `https://francis.darger.bandmusicgames.party`.
- `../bandmusicgames` owns the native iOS version. Use this repo as reference source when porting gameplay into Swift/SwiftUI, but do not place native iOS code here.

## Deploy

- Local dev: `npm run dev`
- Cloudflare Pages deploy: `npm run deploy`
- Cloudflare Pages project name: `francis-darger`

## Repo Hygiene

- Keep generated files out of git: `.wrangler/`, `node_modules/`, and `.DS_Store` stay ignored.
- Commit web gameplay changes here before handing off or deploying.
- The current local `origin` points to `ashrocket/francis`, which is not available on GitHub. Fix the remote before relying on push-based deploys.
