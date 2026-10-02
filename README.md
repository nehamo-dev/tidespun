# tidespun
Production platform for AI native creators

## Website
Marketing homepage for Tidespun, the end-to-end publishing platform for AI-native creators.

## What's here
- `public/index.html`: the full homepage (responsive, desktop and mobile)
- `public/assets/`: logo and artwork files
- `wrangler.jsonc`: Cloudflare Workers config that serves `public/` as a static site

## Run locally
Open `public/index.html` in a browser, or serve the folder with any static server, for example:

```
python3 -m http.server 8000
```

## Deploy
Deployed on Cloudflare Workers (static assets). No build step: Cloudflare runs `npx wrangler deploy`, which uploads the `public/` folder.

## Not connected yet
- The waitlist form does not save sign-ups. Connect it to a form service or email list before launch.
- "Contact us for pricing" and the footer links point to placeholder anchors.
