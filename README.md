# Swept Away Chalet — Guest Guidebook

Static site. `index.html` + `/images`. No build step, no dependencies.

## Deploy on GitHub Pages

**Option A — its own repo (URL: `username.github.io/repo-name/`)**
1. Create a new public repo (e.g. `swept-away-guidebook`).
2. Upload `index.html` and the `images/` folder (keep the folder structure).
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main`, folder `/ (root)` → **Save**.
4. Wait ~1 min. Your URL: `https://username.github.io/swept-away-guidebook/`

**Option B — subfolder of your existing site (`rembuskos.github.io/guidebook/`)**
1. In your `rembuskos.github.io` repo, create a folder named `guidebook`.
2. Put `index.html` and `images/` inside it.
3. Pages is already on. URL: `https://rembuskos.github.io/guidebook/`

## Notes
- Keep `index.html` and `images/` together; image paths are relative (`images/img01.jpg`).
- Fonts load from Apple's system stack first, so no external font files are needed.
- To swap a photo, replace the matching file in `images/` (same filename) — no code changes.
