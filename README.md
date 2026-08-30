# MSI SEO — Website

Static multi-page site for MSI SEO Agency (backlink services). No build step, no dependencies — plain HTML/CSS/JS.

## Files
```
index.html      Home
services.html   Services
pricing.html    Pricing
about.html      About
contact.html    Contact
assets/style.css
assets/script.js
```

## Put this on GitHub + go live with GitHub Pages

1. Create a new repo on GitHub (e.g. `msi-seo-website`). Don't add a README/gitignore there — you already have this one.
2. On your computer, open a terminal in this folder and run:
   ```
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/msi-seo-website.git
   git push -u origin main
   ```
3. On GitHub: open the repo → **Settings** → **Pages** (left sidebar).
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch = `main`, folder = `/ (root)`. Save.
5. Wait ~1 minute, then your site is live at:
   `https://YOUR_USERNAME.github.io/msi-seo-website/`

## Custom domain (optional)
If you own a domain, add a `CNAME` file in this folder containing just your domain (e.g. `msiseo.com`), then point your domain's DNS to GitHub Pages (A records to GitHub's IPs, or a CNAME record to `YOUR_USERNAME.github.io`). GitHub's docs: Settings → Pages → Custom domain field handles most of this automatically once DNS is set.

## Before you go live
- Contact form on `contact.html` is static (just shows an alert on submit). Wire it to [Formspree](https://formspree.io) (free, no backend needed) or your email.
- Add your real email/WhatsApp number in the Contact page — currently placeholder text.
