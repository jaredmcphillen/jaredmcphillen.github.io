# jaredmcphillen.github.io

A Jekyll blog starter for GitHub Pages. GitHub Pages builds the site from the
repository's root directory.

## Add a post

Create a Markdown file in `_posts` named `YYYY-MM-DD-title.md`. Start it with
front matter:

```yaml
---
layout: post
title: My post title
date: YYYY-MM-DD
---
```

Write the post below the front matter. The example post in `_posts` shows the
expected structure.

## Preview locally

Install Ruby and Jekyll, then run `jekyll serve` from the repository root and
open the local URL printed by Jekyll. GitHub Pages publishes the site when
changes are pushed to the configured publishing branch.

Update `_config.yml` to change the site title, description, URL, or base path.
