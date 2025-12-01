# Peptide Track+ Documentation Site

This is the documentation site for Peptide Track+, built with Jekyll and the Just the Docs theme.

## Setup

### Option 1: GitHub Pages (Recommended)

1. Create a new GitHub repository called `peptide-docs`
2. Push this `docs-site` folder contents to the repo
3. Go to repo Settings → Pages
4. Set Source to "Deploy from a branch"
5. Select `main` branch and `/ (root)` folder
6. Save

Your docs will be live at: `https://yourusername.github.io/peptide-docs/`

### Option 2: Local Development

```bash
# Install Ruby and Bundler first
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000/peptide-docs/

## Structure

```
docs-site/
├── _config.yml      # Jekyll configuration
├── index.md         # Home page
├── quick-start.md   # Quick start guide
├── user-manual.md   # Full documentation
├── faq.md          # FAQ page
├── Gemfile         # Ruby dependencies
└── README.md       # This file
```

## Customization

### Update Links

Edit `_config.yml`:
- `url` - Your GitHub Pages URL
- `baseurl` - Repository name (e.g., `/peptide-docs`)
- `aux_links` - Top navigation links

### Add Pages

Create new `.md` files with front matter:

```yaml
---
layout: default
title: Page Title
nav_order: 5
---

# Your Content Here
```

## Theme

Using [Just the Docs](https://just-the-docs.github.io/just-the-docs/) theme.

Features:
- Built-in search
- Mobile responsive
- Dark/light mode
- Clean design

## License

Copyright © 2025 Peptide Track+
