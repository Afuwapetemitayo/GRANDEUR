# Grandeur Starry Lamp (Vercel)

Static site. No build step.

## Deploy (drag & drop)
1. Go to https://vercel.com/new
2. Choose "Deploy" from a folder (or push this folder to a GitHub repo and import it).
3. Framework Preset: **Other**
4. Build Command: leave empty
5. Output Directory: **public**
6. Click Deploy.

## Deploy (Vercel CLI)
```
npm i -g vercel
cd vercel
vercel --prod
```

## Files
- public/index.html  – the full site (all images, fonts and code bundled in)
- vercel.json        – Vercel settings
