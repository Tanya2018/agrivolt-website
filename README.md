# AgriVolt Africa — Website

5-page static site. Solar Field palette. Built to deploy on Netlify.

## Files
| File | Page |
|---|---|
| `index.html` | Home |
| `about.html` | About Us |
| `services.html` | What We Do |
| `industries.html` | Who We Serve |
| `contact.html` | Contact (Netlify form) |
| `thanks.html` | Form success page |
| `styles.css` | Design system — all styling |
| `script.js` | Nav toggle, scroll animations, form |

## Deploy on Netlify (2 minutes)
**Option A — drag & drop**
1. Go to app.netlify.com → "Add new site" → "Deploy manually"
2. Drag the whole `agrivolt` folder onto the drop zone
3. Live instantly on a `*.netlify.app` URL

**Option B — Git (for updates later)**
1. Push this folder to a GitHub repo
2. Netlify → "Import from Git" → pick the repo
3. No build command needed. Publish directory: `/`

## Custom domain
1. Buy `agrivolt.africa` (or `.co.ke` / `.com`) — Truehost or similar
2. Netlify → Domain settings → add custom domain
3. Point DNS (Cloudflare nameservers recommended — same as SAIS setup)

## Contact form
Netlify auto-detects the form (it has `data-netlify="true"`).
After first deploy: Netlify dashboard → Forms → set up email notifications so AgriVolt gets leads in their inbox.

## ⚠️ BEFORE GO-LIVE — replace these placeholders
Find-and-replace across all `.html` files:
- `hello@agrivolt.africa` → real email
- `254700000000` → real WhatsApp number (in `wa.me/` links)
- Office address on `contact.html` → real Nairobi address
- Add real `favicon.ico` + social share image

## Fonts
Fraunces + Sora, loaded from Google Fonts CDN. No install needed.
