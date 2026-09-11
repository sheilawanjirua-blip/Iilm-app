# Ilm — Website / PWA

This folder is the web version of Ilm. It is a static website/PWA: no Node.js build is required.

## Quickest way to publish

Upload the contents of this folder to a static host such as GitHub Pages, Netlify, Vercel, Cloudflare Pages, or your own web hosting.

The site should be served over **HTTPS** in production. HTTPS is important for service workers and installability.

## Files

- `index.html` — Ilm application
- `manifest.json` — installable PWA metadata
- `sw.js` — service worker/offline shell
- `icons/` — app icons

## Custom domain

After choosing a host, buy/connect a domain such as `ilm.co.ke` (if available), then point the domain's DNS records to the host.

## Important

Ilm uses some external APIs for live Qur'an/audio/prayer data, so an internet connection is needed for those live features. The app shell and supported local data can be cached by the service worker.

This project is educational and is not a fatwa service. Serious personal religious/legal questions should be checked with a qualified scholar.
