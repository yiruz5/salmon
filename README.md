# Journey up the Cedar River

Interactive page: 10 recording sites along the Cedar River (Renton, WA), site videos, and a "what a fish hears" listening lab.

## Files GitHub Pages needs
```
index.html          ← the site
support.js
.nojekyll           ← required: lets the _ds folder be served
_ds/                ← design system styles
uploads/            ← hydro_*.wav and electro_*.wav (55, 100, 410 Hz)
videos/             ← site-01.mp4 … site-10.mp4 (you add these)
```

## Publish
1. Create a public repo on github.com and upload everything above (keep the folder structure).
2. Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
3. After ~1 minute the site is at `https://<username>.github.io/<repo-name>/`.

## Notes
- File and folder names are case-sensitive on GitHub Pages (`site-01.mp4`, not `Site-01.MP4`).
- GitHub blocks files over 100 MB and warns over 50 MB; keep each video under ~50 MB.

River course © OpenStreetMap contributors.
