# harpreetsingh.github.io

Personal academic website for Harpreet Singh (PhD student, Department of Economics, McGill University), built with Jekyll and the [The Plain Academic](https://github.com/brenov/the-plain-academic) theme, deployed via GitHub Pages.

Migrated from Google Sites (https://sites.google.com/view/hpsingh/home).

## Structure

- `index.html` — Home page
- `about.md` — About page
- `cv.md` — CV page (add your CV PDF to `assets/cv.pdf`)
- `teaching.md` — Teaching page
- `wassup.md` — Personal / "Wassup?" page
- `contact.md` — Contact page
- `_researches/` — Research papers & reports (one file per entry)
- `_projects/` — Current research projects (one file per entry)
- `_talks/`, `_posts`, `_blog/` — Empty for now (blog lives on Substack: https://harpreetsingh511.substack.com/)

## Local development

```
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000/harpreetsingh/

## Deployment

This repo is served via GitHub Pages from the `master` branch. In repo Settings → Pages, set the source branch to `master` (root). Once enabled, the site will be live at:

https://GitHarpreet.github.io/harpreetsingh/
