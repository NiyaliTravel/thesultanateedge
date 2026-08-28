# The Sultanate Edge — website

**Coming-soon** static page for The Sultanate Edge, part of The Sultanate Hotels collection. The property is not yet operational; this site deliberately shows no rates and no booking flow.

- Pure static HTML/CSS — no build step. `index.html` + `assets/` are served as-is.
- `assets/style.css` is the collection's shared stylesheet — keep it byte-identical across all Sultanate sites.

## Deploy

GitHub → Hostinger Git auto-deploy. Push to `master` and Hostinger redeploys (preset: **Static**, no build framework).

## When the property opens

Replace the coming-soon page with the full site template used by Fulhadhoo/Courtyard, and enable the property in the hub's booking proxy allowlist (server-side, on the droplet).
