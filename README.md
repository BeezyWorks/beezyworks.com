# beezyworks.com

The landing page for BeezyWorks: Siddur One, Mikros BaDerech and Mishnayos, plus a bit about me.

Plain static files in `public/`, no build step. Deployed as a Cloudflare Worker with static assets (`wrangler.jsonc`): build command empty, deploy command `npx wrangler deploy`.
