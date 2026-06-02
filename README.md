# UT Unit Toilet — 整體盥洗設備系統導入方案

A vertical long-form web page presenting the UT (Unit Toilet) modular restroom system, built on the HQ Interior & Space Design design system.

Static site — no build step. `index.html` + `images/`.

## Deploy

This is a zero-config static site. Vercel serves it as-is.

```bash
# 1. push to GitHub
git init
git add .
git commit -m "UT Unit Toilet web page"
git branch -M main
git remote add origin https://github.com/<you>/<repo>.git
git push -u origin main

# 2a. deploy via Vercel dashboard
#   vercel.com → Add New → Project → import the repo → Deploy
# 2b. or via CLI
npm i -g vercel
vercel --prod
```

No framework, no build command, no output directory needed — leave them empty / "Other".
