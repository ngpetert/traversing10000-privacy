[README.md](https://github.com/user-attachments/files/27110351/README.md)# traversing10000-privacy
Host of privacy terms in relation to the web pages or apps I build
[Uploading README.md…](# Traversing10000 — Privacy Policy Website

Standalone static privacy policy site for all Traversing10000 products.

**Live URL:** https://privacy.traversing10000.com

## Deployment

This is a pure static HTML site — no build step required.

### Cloudflare Pages Settings

| Setting | Value |
|---|---|
| Build command | *(leave blank)* |
| Build output directory | `/` (root) |
| Node.js version | N/A |

### Custom Domain

Add `privacy.traversing10000.com` as a custom domain in Cloudflare Pages.
Cloudflare will auto-configure DNS since the domain is already on Cloudflare.

## Updating the Policy

Edit `index.html` directly. Update the "Last Updated" date in:
1. The `<title>` meta description
2. The `.page-meta` section near the top of `<main>`
3. The sidebar footer date
)
