# journal-template
This is a lightweight Jekyll and GitHub Pages template.

It provides a structure for writing daily notes, reflections, study logs, and developer insights.

## Features
- Posts
- Markdown-based
- GitHub Pages auto-deploy

## Quick Start
1. Fork this repository.
2. Configure the `_config.yml`.
3. Add your journal entries ynder `_post` in `YYYY-MM-DD-title.md` format.
4. Open a Pull Request to `main`.
5. GitHub Pages will publish your site automatically.

## Folder Structure
```
/_posts    -> journal entries
/_tags     -> tags topics
/_layouts  -> templates
/_includes -> shared components
/assets    -> CSS, JS & images
```

## Conventions

### Posts
- Posts are Markdown files under `_posts/`.
- Post file in `YYYY-MM-DD-title.md` format.
- Use YAML front matter with `title` and optional `tags`.

### Tag Topics
- Tag Topics are Markdown files under `_tags/`.
- Tag Topics in `tag-topic-name.md` format.
- Use YAML front matter with `tag`.

## Post
### Example Post
```markdown
---
title: "Sample post"
tags: [sample, readme]
---

Example of post.
Write your dev notes, insights, reflections.
```

### How to use
1. Add your entries under `/_posts`.
2. Commit or open a PR.
3. GitHub Pages deploys automatically.

## Tag Topic
### Example Tag Topic
```markdown
---
layout: tag
tag: example
---
```

### How to use
1. Add your tag topic under `/_tags`.
2. Commit or open a PR.
3. GitHub Pages deploys automatically.