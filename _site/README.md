# ITGenNexus @ ISIT 2026 — GitHub Pages Site

This repository is a lightweight Jekyll site designed for GitHub Pages.

## Quick start
1. Put your hero image at: `assets/img/guangzhou-hero.jpg`
2. Edit the site title/nav/hero text in `_config.yml`
3. Enable GitHub Pages:
   - Settings → Pages → Build and deployment
   - Source: Deploy from a branch
   - Branch: main / (root)

## Local preview (optional)
If you have Ruby/Jekyll installed:

```bash
bundle exec jekyll serve
```


## Setting the repo name (important)
If you publish this as a *project page* (recommended), edit `_config.yml` and set:

```yml
baseurl: "/YOUR_REPO_NAME"
url: "https://haiyun-he.github.io"
```

If you publish as `haiyun-he.github.io` (user site), keep `baseurl` empty.
