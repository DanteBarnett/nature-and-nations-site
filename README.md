# Nature & Nations — public site

Live at **https://natureandnations.com** (Cloudflare Pages project `nature-and-nations`).

The deployable site lives in **`public/`**. Pushing to `main` auto-deploys to Cloudflare
Pages via GitHub Actions (`.github/workflows/deploy.yml`).

## One-time setup
Add a repository secret **`CLOUDFLARE_API_TOKEN`** (a Cloudflare API token with
`Account → Cloudflare Pages: Edit`). The account ID is set directly in the workflow.

Settings → Secrets and variables → Actions → New repository secret.

## Updating the site
Edit files in `public/` and push to `main`. The Action redeploys automatically — no tokens to paste.

> Canonical source of these files is `docs/Design/site/` in the Nature & Nations project repo.
