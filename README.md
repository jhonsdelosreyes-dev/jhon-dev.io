# Portfolio (static site)

Plain HTML/CSS/JS, no build step. All content is edited in `js/data.js` (profile, projects)
and `js/content.js` (graphics, videos, certificates, CV).

## Deploy on GitHub Pages
1. Push this folder's contents to a GitHub repo (`index.html` must be at the repo root).
2. Repo **Settings → Pages → Build and deployment → Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Open `https://<username>.github.io/<repo>/` after a minute or two.

All paths are relative, so it works both at `username.github.io` and at `username.github.io/repo/`.

## Folder layout
- `css/site.css`, `js/*.js` – styles and scripts (load order: data → content → render → site → media)
- `assets/` – images, videos, certificates, PDFs
- `img/` – profile photo and project screenshots (`img/projects/`)
