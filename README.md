# kennyhuachan.com

Static website for `kennyhuachan.com`, intended to be hosted from GitHub with
the lowest possible incremental cost.

## Recommended Hosting

Use Cloudflare Pages connected to this GitHub repository.

- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/`
- Production branch: `main`

This keeps hosting free for a normal personal site and avoids build tooling
until the site needs it.

## Deployment Flow

1. Create a GitHub repository named `kennyhuachan.com`.
2. Push this folder to that repository.
3. In Cloudflare Pages, create a project from the GitHub repository.
4. Add the custom domain `kennyhuachan.com`.
5. Update DNS as Cloudflare instructs.
6. Keep the WordPress site live until DNS and redirects are verified.

## Migration Checklist

- Export/download existing WordPress pages and media. Initial homepage content
  migrated on 2026-05-11.
- Recreate important pages in this repo.
- Map old WordPress URLs to new URLs in `_redirects`.
- Verify title tags, descriptions, and social preview metadata.
- Point `kennyhuachan.com` to the new static host.
- Cancel WordPress hosting only after the new site is live and verified.

## Cost Model

Expected incremental hosting cost: `$0/month` for the static site on Cloudflare
Pages or GitHub Pages, assuming domain registration is already paid elsewhere.

Possible future costs:

- Domain renewal at the registrar.
- Email hosting if the domain is used for email.
- Paid CMS or form handling if needed later.
- Paid GitHub/Cloudflare tiers only if traffic or team needs exceed free limits.
