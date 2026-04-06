# Diary of a White Collar Worker

A minimal public diary/blog designed for GitHub Pages.

## What is here

- A homepage
- An About page
- One sample diary post
- A GitHub Pages compatible Jekyll setup

## Publish it on GitHub

1. Create a new public GitHub repository named `chronicles-white-collar-worker`.
2. Upload the contents of this folder to that repository.
3. In GitHub, open `Settings` -> `Pages`.
4. Set the source to `Deploy from a branch`.
5. Choose the `main` branch and the `/(root)` folder.
6. Save, then wait for GitHub Pages to publish the site.

Your site URL should be:

`https://gandavensis.github.io/diary-of-a-white-collar-worker/`

## Write a new diary entry

Create a new Markdown file in `_posts/` using this pattern:

`YYYY-MM-DD-title.md`

Example:

`2026-03-21-a-small-office-victory.md`

Use this template:

```md
---
layout: post
title: "A Small Office Victory"
date: 2026-03-21 20:00:00 +0100
---

Write here.
```

## Optional local preview

If you have Ruby installed:

```bash
bundle install
bundle exec jekyll serve
```
