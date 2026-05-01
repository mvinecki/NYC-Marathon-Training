# Marathon Training

A personal reference app for an NYC Marathon 2026 training plan.

## Run locally

```
npm install
npm start
```

Opens at http://localhost:3000

## Deploy to Railway

1. Push this folder to a GitHub repo
2. In Railway → New Project → Deploy from GitHub repo
3. Select this repo. Railway auto-detects Node, runs `npm install` then `npm start`
4. Open the generated URL on your phone, Add to Home Screen — done.

The app is a single self-contained `index.html` — all assets, fonts, and code are inlined. No build step.
