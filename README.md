# clodomirsantana.github.io

Personal academic website for **Clodomir Santana**, Postdoctoral Scholar in the
Division of Cardiovascular Medicine at UC Davis Health.

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll template (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)).

## Structure

- `_config.yml` — site-wide settings, sidebar author profile, and profile links
- `_pages/about.md` — home / about page
- `_pages/publications.html` — publications listing, grouped by category
- `_pages/cv.md` — CV (mirrors `files/clodomir_santana_cv_2026.pdf`)
- `_publications/` — one Markdown file per publication
- `_data/navigation.yml` — top navigation

## Local development

Requires Ruby ≥ 3.0.

```bash
bundle install
bundle exec jekyll serve
# open http://localhost:4000
```

## Deployment

Pushing to the default branch triggers GitHub Pages to build and publish the site
at https://clodomirsantana.github.io.
