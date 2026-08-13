# yongliwebsite

This repository contains a simple Jekyll website scaffold so you can add new articles easily.

How to add a new article

1. Create a new file in the `_posts` directory named `YYYY-MM-DD-your-title.md`, for example:

   _posts/2026-08-13-my-new-article.md

2. Put front matter at the top of the file:

```
---
layout: post
title: "My new article"
date: 2026-08-13 12:00:00 +0000
---

Your article content (Markdown) goes here.
```

3. Commit and push the file to the repository. If you want the site to be published on GitHub Pages, enable GitHub Pages in repository settings and set the source to the default branch (usually `main` or `master`).

Preview locally

- Install Ruby and Bundler. In this repo run:

```
gem install bundler
bundle install
bundle exec jekyll serve
```

- Open http://127.0.0.1:4000 to preview.

Notes

- The site uses a minimal Jekyll layout in `_layouts`. Posts are stored in `_posts` and will be automatically listed on the homepage.
- If you prefer a different static site generator (Hugo, Next.js, etc.) let me know and I can convert the site.
