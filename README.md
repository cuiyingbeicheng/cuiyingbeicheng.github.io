# Ying Cui - Academic Website

Personal academic website for Ying Cui, built with the
[al-folio](https://github.com/alshedivat/al-folio) Jekyll template.

## Main content

- `_pages/about.md` - homepage and research overview
- `_pages/publications.md` - publication listing
- `_pages/research.md` - research programs and current directions
- `_pages/software.md` - research software
- `_pages/teaching.md` - teaching and research mentoring experience
- `_pages/cv.md` and `_data/cv.yml` - web CV
- `_bibliography/papers.bib` - publication metadata
- `assets/img/photo_website.JPG` - profile photograph
- `assets/img/og.png` - social-sharing preview

## Local preview

The recommended setup for this archived al-folio template is Docker:

```bash
docker compose pull
docker compose up
```

Open `http://localhost:8080`.

## Publishing

The included GitHub Actions workflow builds the site and publishes `_site` to
the `gh-pages` branch after a push to `main` or `master`. In the repository
settings:

1. Give GitHub Actions read and write permissions.
2. Configure GitHub Pages to deploy from the `gh-pages` branch.
3. Leave `baseurl` empty for the username-level Pages repository.

The canonical site URL is configured as `https://cuiyingbeicheng.github.io`.
