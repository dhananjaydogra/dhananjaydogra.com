# dhananjaydogra.com

Personal portfolio website of Dhananjay Dogra — Oracle ERP & CRM specialist,
cloud-certified (AWS / Azure), based in the Greater Toronto Area.

## Stack

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step.
Fast, dependency-free, and deployable to any static host.

```
index.html      — single-page site
css/style.css   — styles (light/dark theme via CSS variables)
js/main.js      — theme toggle, mobile nav, scroll reveal
```

## Local preview

Open `index.html` directly in a browser, or serve it:

```
python -m http.server 4173
```

## Deployment

Deployed via a static host (Cloudflare Pages / Vercel / Netlify) connected to
this repository — every push to `main` auto-deploys to https://dhananjaydogra.com.
