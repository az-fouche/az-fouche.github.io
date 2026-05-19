# az-fouche.github.io

Personal blog. Built with [Jekyll](https://jekyllrb.com/) and served by GitHub Pages.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Writing a post

Add a markdown file to `_posts/` named `YYYY-MM-DD-slug.md` with this frontmatter:

```yaml
---
layout: post
title: "Post title"
date: YYYY-MM-DD
---
```

Push to `main` — GitHub Pages builds and deploys automatically.
