# Adderssite

Landing page for [adders.party](https://adders.party). Plain HTML, no build step.

- `public/index.html` is the whole site.
- Put a photo at `public/me.jpg` and the ME.EXE window dithers it automatically.
- Replace `YOUR-LINKEDIN-HANDLE` in `public/index.html` with your LinkedIn profile URL.

## Deploy

Cloudflare dashboard: Workers & Pages → Create → Import a repository → pick this repo.
Leave the build command empty; the deploy command is `npx wrangler deploy`.
Then add `adders.party` under the Worker's Settings → Domains & Routes.
Every push to `main` redeploys.
