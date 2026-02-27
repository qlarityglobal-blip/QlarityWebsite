# Qlarity — HVAC Revenue Infrastructure

Production website for Qlarity, a US-focused HVAC Revenue Infrastructure company.

## Stack

- Single-file HTML/CSS/JS — no build step required
- Google Fonts (Bebas Neue, Barlow Condensed, Barlow)
- Calendly booking integration: https://calendly.com/qlarityglobal/30min

## Deployment

This site is designed to be served as a static file. It can be deployed to:

- **GitHub Pages** — push to `main`, enable Pages on `/root` of `main` branch
- **Netlify** — drag and drop the folder or connect this repo
- **Vercel** — import repo, deploy as static site
- **Any web host** — upload `index.html` to your public root directory

## Custom Domain

To connect your domain:
1. Add a `CNAME` file to this repo containing your domain (e.g. `www.qlarityglobal.com`)
2. In your DNS provider, add a CNAME record pointing to `<your-github-username>.github.io`
3. Enable HTTPS in GitHub Pages settings

## Files

- `index.html` — full production website
- `CNAME` — custom domain config (add your domain here)
- `README.md` — this file
