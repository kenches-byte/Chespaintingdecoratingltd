# Ches Painting & Decorating Ltd — GitHub Pages site

This repo contains a desktop-first static site for **www.chespaintingdecoratingltd.co.uk**.

## Quick deploy
1. Create a new repository and upload all files in this ZIP to the repo root.
2. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, Branch: `main` (folder: `/root`). Save.
3. Under **Custom domain**, set `www.chespaintingdecoratingltd.co.uk` and enable **Enforce HTTPS** once available.

## DNS (at your domain provider)
- `CNAME`  `www` → `USERNAME.github.io`  ← replace with your GitHub username
- Optional A/AAAA records for apex (`chespaintingdecoratingltd.co.uk`) to redirect to `www`:

  - A: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
  - AAAA: 2606:50c0:8000::153, ::8001, ::8002, ::8003

## Project structure
```
/
├─ index.html
├─ CNAME
├─ .nojekyll
├─ assets/
│  ├─ favicon.svg
│  ├─ apple-touch-icon.png
│  └─ social-card.png
└─ downloads/
   └─ (place your Standard Woodwork Spec PDF here)
```

> Replace the placeholder social image and icons whenever you like.

