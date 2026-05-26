# Solo Traveler Media

Jekyll version of the Solo Traveler Media website with a blog.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Blog posts

Add new posts in `_posts/` using the filename format:

```text
YYYY-MM-DD-post-title.md
```

Each post should include front matter like:

```yaml
---
layout: post
title: "Post Title"
date: 2026-05-26
excerpt: "Short summary of the post."
---
```
