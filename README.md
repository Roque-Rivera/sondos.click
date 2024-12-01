# Fun IT Facts Website

A comic-toned static website about IT facts and tools, built with Jekyll.

## Features

- Responsive design with mobile support
- Dark mode toggle
- Easy content management through markdown files
- Section navigation (Blog, GIFs, Logos, Repos, About)
- Sidebar with fun IT tools

## Setup

1. Install Ruby and Jekyll:
```bash
gem install bundler jekyll
```

2. Install dependencies:
```bash
bundle install
```

3. Run the development server:
```bash
bundle exec jekyll serve
```

## Adding Content

### Blog Posts
Create new markdown files in the `_posts` directory following the format:
```markdown
---
layout: post
title: Your Post Title
date: YYYY-MM-DD
categories: [category1, category2]
---

Your content here
```

### Pages
Add new pages in the root directory or in their respective folders (e.g., `/about/index.md`).

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## Customization

- Modify `_config.yml` for site settings
- Edit styles in `assets/css/styles.css`
- Update JavaScript in `assets/js/theme.js`
