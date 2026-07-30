# harpreetsingh.github.io

Personal academic website for Harpreet Singh (PhD Candidate, Department of Economics, McGill University).

Static HTML + Bootstrap 5 site, based on the [fadikar.com](https://github.com/fadikar/fadikar.github.io) theme, deployed via GitHub Pages. No build step, no Jekyll — just plain HTML/CSS/JS.

## Structure

- `index.html` — Home (bio, research highlights, recent talks, "Beyond Research" teaser)
- `research.html` — Research projects grouped by theme, with related papers/reports
- `notes.html` — Lecture notes & GitHub resources (Math Camp, Macro notes)
- `cv.html` — Full CV
- `talks.html` — Talks & workshops delivered (data-driven from `data/talks.json`)
- `useful-links.html` — Curated links (data-driven from `data/useful-links.json`)
- `outdoor.html` — Sports, books, food, music — personal "Wassup?" content
- `data/talks.json`, `data/useful-links.json` — edit these to add/remove entries without touching HTML
- `images/profile/headshot.svg` — placeholder avatar; **replace with a real photo** (keep the filename or update the `<img src>` in every page's sidebar)
- `images/papers/*.svg` — placeholder thumbnails for research cards; replace with real figures if you have them

## Local preview

No build tools needed — just open `index.html` in a browser, or run a tiny local server:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000/

## Deployment (GitHub Pages)

1. Push all files to the root of this repo (branch `master` or `main`).
2. Repo Settings → Pages → Source: Deploy from branch → select branch, folder `/ (root)`.
3. Site will be live at `https://GitHarpreet.github.io/harpreetsingh/` (or your custom domain if you add a `CNAME` file).

## Editing content

- **Bio / contact / social links**: edit the sidebar block near the top of each `.html` file (same block repeated on every page — search for `sidebar-left`).
- **CV**: edit `cv.html` directly — each entry is a `.cv-item` block.
- **Research**: edit `research.html` — each project is a `.research-project-section`.
- **Talks**: add entries to `data/talks.json` (no HTML editing needed).
- **Useful Links**: add entries to `data/useful-links.json`.
- **Outdoor**: edit `outdoor.html` directly.
