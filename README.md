# Fool on the Hill

A clean, Medium-style personal blog built with Jekyll and hosted free on GitHub Pages.

Live at: https://foolonthehill16.github.io/mywebsite/

## Writing a new post

1. Open the `_posts` folder and click **Add file → Create new file**.
2. Name it `YYYY-MM-DD-short-title.md` (for example `2026-12-03-my-first-job.md`).
3. Start the file with this header, then write the story below it in Markdown:

```markdown
---
title: "My First Job"
subtitle: "A one-line hook that shows on the front page."
tags: [work, lessons]
image: /assets/images/first-job.jpg   # optional cover photo
---

Opening paragraph of the story...

<!--more-->

The rest of the story...
```

4. Commit. The site rebuilds automatically in about a minute.

## Adding photos

Upload images to `assets/images/` and reference them as `/assets/images/name.jpg`
in the `image:` field, or inside a post with `![Alt text]({{ '/assets/images/name.jpg' | relative_url }})`.

## Changing the name, tagline, or bio

Edit `_config.yml`. The About page is `about.md`.

## Structure

- `_posts/`  stories (one Markdown file each)
- `_layouts/` page templates (home, post, page)
- `_includes/` header, footer, reading time
- `assets/style.css` all styling, including dark mode
- `tags.html` the Topics page
