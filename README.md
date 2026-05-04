# cookie-clicker

Fully static Snapchat privacy proxy. No backend needed.

Built with Scramjet v1 + bare-mux v2 + Epoxy transport via public Wisp server.

## Deploy (GitHub Pages / Netlify)

Just drop the contents of the `public/` folder into your repo root or Netlify site — that's it.

## Host it yourself (optional)

```bash
cd public
npx serve .
```

## Config

Edit `public/config.js` to change:
- `TARGET_URL` — site to proxy
- `WISP_URL` — swap in your own Wisp server if needed
- `SCRAM_PREFIX` — URL prefix for proxied content
