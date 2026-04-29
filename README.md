# Geosystem Innovation Laboratory Website

This repository contains the source for the Geosystem Innovation Laboratory (GIL) website built with Hugo Blox/Hugo.

## Overview

The site includes:

- Lab overview and homepage content
- Research area pages
- Team member profiles
- Publications imported as individual content entries
- Software/project pages
- Teaching materials
- News posts and announcements

## Repository Structure

- `content/`: Site content in Markdown
- `content/authors/`: People profiles used by the People page
- `content/publication/`: Publication entries
- `content/post/`: News posts
- `content/research/`: Research area pages
- `content/software/`: Software and code project pages
- `assets/media/`: Images and media used across the site
- `config/_default/`: Hugo and Hugo Blox configuration

## Local Development

Prerequisites:

- Hugo Extended

Run the site locally:

```bash
hugo server
```

Build the production site:

```bash
hugo --gc --minify
```

## Common Updates

Add a news post:

1. Create a new folder under `content/post/`.
2. Add an `index.md` file and an optional `featured.*` image.

Add a team member:

1. Create a folder under `content/authors/` named after the person.
2. Add `_index.md` with their profile metadata.
3. Add `avatar.jpg`, `avatar.png`, or similar.
4. Set `user_groups` so they appear in the correct section on the People page.

Add a publication:

1. Create a new folder under `content/publication/`.
2. Add `index.md`.
3. Add `cite.bib` if you want a BibTeX entry on the publication page.

Update homepage sections:

- Edit `content/_index.md`

Update navigation and site settings:

- Edit `config/_default/menus.yaml`
- Edit `config/_default/params.yaml`
- Edit `config/_default/hugo.yaml`

## Notes

- The repository currently assumes standard Hugo content organization with Hugo Blox blocks.
- If you deploy through GitHub Pages or Netlify, make sure the configured `baseURL` matches the final public URL.
