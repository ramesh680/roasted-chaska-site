# Roasted Chaska - website

Static landing page for Roasted Chaska (Jaipur). No build step; Render serves `public/` as-is.

## Deploy on Render (Blueprint)
1. Push this repo to GitHub (`ramesh680/roasted-chaska-site`).
2. Render Dashboard -> New -> Blueprint -> pick the repo -> Apply.
3. Site goes live at `https://roasted-chaska.onrender.com` (or the name Render assigns).

Static sites on Render are free and do not sleep, unlike free web services.

## Editing
- Prices, products, WhatsApp number: `public/index.html`
- Every push to `main` redeploys automatically.

## Custom domain (later)
Render -> roasted-chaska -> Settings -> Custom Domains -> add `www.yourdomain.in`,
then add the CNAME record Render shows at your domain registrar. HTTPS is automatic.
