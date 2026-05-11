# FixFox Landing

Coming-soon page for [fixfox.ge](https://fixfox.ge) — trust layer for home services in Georgia.

## Stack

- Static HTML / CSS / vanilla JS
- Hosted on Cloudflare Pages
- Email capture via Formspree

## Local dev

```bash
python3 -m http.server 5176
# open http://localhost:5176
```

## Deploy

Pushed to `main` → Cloudflare Pages auto-builds and deploys.

Custom domains: `fixfox.ge`, `www.fixfox.ge`.

## Config

Set `FORMSPREE_ENDPOINT` in `index.html` to your Formspree form URL before first deploy.

## TODO before launch

- [ ] Replace `YOUR_FORM_ID` in `index.html` with real Formspree endpoint
- [ ] Add `og-image.png` (1200×630) for social previews
- [ ] Verify `hello@fixfox.ge` email routing
- [ ] Submit sitemap to Google Search Console
