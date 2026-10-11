# Yousef Gamal Salem - Portfolio

Static site: `index.html` + `assets/`. No build step, no dependencies, no secrets.

## Update content
Edit the `const D = {...}` block near the bottom of `index.html`:
projects, skills, soft skills, socials, certificates, timeline, GitHub username.
Certificates, soft skills and the GitHub section stay hidden until you add data.

## Before publishing
1. Confirm the GitHub username in `D.github` (GitHub usernames cannot contain dots).
2. Replace `YOUR-DOMAIN.vercel.app` in the `<head>` (canonical, og:image).

## Run locally
`python3 -m http.server 8000` then open http://localhost:8000

## Deploy
**Vercel:** push to GitHub, Import Project at vercel.com, Framework Preset "Other", no build command, output directory `./`.
**GitHub Pages:** push to a repo, Settings > Pages > Deploy from branch `main` / root.
