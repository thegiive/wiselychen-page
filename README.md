# Wisely Chen - AI Consultant Website

A Jekyll-powered personal website for AI consulting services, featuring VIBE coding methodology and spec-driven development.

## Quick Start

### Local Development

1. Install Jekyll and dependencies:
   ```bash
   bundle install
   ```

2. Serve the site locally:
   ```bash
   bundle exec jekyll serve
   ```

3. Visit `http://localhost:4000` to preview your changes

### GitHub Pages Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch.

## Content Management

### Updating Content

The site uses Jekyll with Markdown for easy content management:

- **Hero Section**: Edit `index.md` front matter
- **About Section**: Edit `index.md` front matter
- **Services**: Add/edit files in `_services/` directory
- **Methodologies**: Add/edit files in `_methodologies/` directory
- **Contact Info**: Update `_config.yml` author section

### Adding New Services

Create a new file in `_services/` directory:

```markdown
---
title: "Your Service Title"
description: "Service description here"
order: 5
---
```

### Adding New Methodologies

Create a new file in `_methodologies/` directory:

```markdown
---
title: "Methodology Name"
order: 1
---

Your methodology content in markdown format.

- Bullet points
- **Bold text**
- And more markdown features
```

## File Structure

```
├── _config.yml          # Site configuration
├── _layouts/             # HTML templates
├── _includes/            # Reusable components
├── _services/            # Service content (markdown)
├── _methodologies/       # Methodology content (markdown)
├── _data/               # Data files
├── assets/              # CSS, images, etc.
├── index.md             # Homepage content
└── Gemfile              # Ruby dependencies
```

## Customization

- **Styling**: Edit `assets/css/styles.css`
- **Site config**: Edit `_config.yml`
- **Layout**: Edit files in `_layouts/` and `_includes/`