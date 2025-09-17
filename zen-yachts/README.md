# Zen Yachts — GitHub Pages Codebase

This zip contains a minimal, luxury-styled landing site for the Zen Yachts relaunch.

## Structure
```
/
├─ index.html
├─ styles.css
└─ assets/
   ├─ hero-placeholder.mp4
   ├─ para-ocean.jpg
   ├─ para-wake.jpg
   └─ para-green.jpg
```

## Deploy (GitHub Pages)
1. Create a new repository (e.g. `zen-yachts`) and upload these files to the root.
2. In **Settings → Pages**, set Source to **Deploy from a branch**, select `main` and `/ (root)`.
3. Replace `LOGO` with your mark, swap assets in `/assets`, and connect a form handler if needed.

## Custom Domain (GoDaddy → GitHub Pages)
- Add `A` records to GitHub Pages IPs and a `CNAME` for `www` → `<user>.github.io` in GoDaddy DNS.
- In GitHub Pages, set your custom domain and enable HTTPS.
