# GRIT LIFT — Landing Page

A single-page landing site for GRIT LIFT precision physique coaching.

## Structure

```
gritlift-site/
├── index.html        # the whole page (HTML + CSS in one file)
├── images/           # all photos + logo, kept as separate files
│   ├── logo.png      # transparent white logo (used in nav + footer)
│   ├── favicon.png   # browser tab icon
│   ├── hero-bg.jpg   # hero background
│   └── ... (client/result photos)
└── README.md
```

The page is plain HTML/CSS — no build step, no dependencies. Open `index.html`
in any browser to view it locally.

## Publishing with GitHub Pages (free hosting)

1. Create a new repository on GitHub (e.g. `gritlift`). Leave it empty.
2. Upload **all** the files in this folder, keeping the `images/` folder intact.
   - Easiest path: on the repo page click **Add file → Upload files**, then drag
     in `index.html`, `README.md`, AND the whole `images` folder.
3. Go to **Settings → Pages**.
4. Under **Source**, choose **Deploy from a branch**, pick `main` and `/ (root)`,
   then **Save**.
5. Wait ~1 minute. Your site goes live at:
   `https://YOUR-USERNAME.github.io/gritlift/`

## Swapping a photo later

Just replace the file inside `images/` with a new one of the **same filename**.
No code changes needed.
