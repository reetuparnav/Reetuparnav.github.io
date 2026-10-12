# Reetu's personal website

A free site built with Jekyll, hosted on GitHub Pages at https://reetuparnav.github.io

## Write a new post
Add a file to `_posts/` named `YYYY-MM-DD-short-title.md`:

```
---
layout: post
title: "Your title"
categories: blog        # or: articles (for professional pieces)
jel: "E31, E52"         # optional, articles only
summary: "One-line summary shown in lists."
---

Your text in Markdown.
```

You can do this directly on github.com: open `_posts`, click **Add file → Create new file**, paste, and commit. The site rebuilds in about a minute.

## Edit your details
- Name, tagline, email, social links: `_config.yml`
- Home page intro and hobby cards: `index.html`
- Publications: `research.html`
- Bio and CV: `about.md` (put your CV at `assets/cv.pdf`)
- Hobbies: `life.md`
- Photo: replace `assets/img/profile.svg` (or add `profile.jpg` and update `index.html`)

## Publish (free)
1. The site lives in the public repository `reetuparnav/reetuparnav.github.io`.
2. Upload the contents of this folder to it.
3. In the repository, go to **Settings → Pages**, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Your site is live at `https://USERNAME.github.io`. A custom domain (e.g. reetu.com, about $10–15/year) can be added under the same Settings page.
