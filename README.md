# Easy_Blog

A blog built for my non-techical friends :)

## Quick Start

### Running Locally
```bash
bundle exec jekyll serve
```
Then visit `http://127.0.0.1:4000/`

### Writing a Post
1. Create a new file in `_posts/` with format: `YYYY-MM-DD-title.markdown`
2. Use this template:
```markdown
---
layout: post
title: "Your Post Title"
date: 2025-11-09 10:00:00 +0000
categories: [film, analysis]
---

Your content here
```

### Site Settings
Edit `_config.yml` to update:
- `title` - Blog name
- `description` - Blog description
- `email` - Contact email
- Social media usernames

## File Structure
```
.
├── _posts/          # Published blog posts
├── _drafts/         # Draft posts (not published)
├── _config.yml      # Site settings
├── about.markdown   # About page
├── index.markdown   # Homepage
└── Gemfile          # Dependencies
```

## Theme
Built with [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) - a modern, elegant Jekyll theme.

