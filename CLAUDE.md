# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a GitHub Pages repository (`bernomone.github.io`) that serves as a personal website. The repository has a very minimal structure focused on hosting static content.

## Architecture

- **Static Site Structure**: This is a GitHub Pages repository that serves Markdown files as web pages
- **Project Organization**: Individual projects are organized in their own subdirectories (e.g., `cities4rent/`)
- **Content Format**: Projects use Markdown files (`index.md`) for content presentation

## Current Projects

### cities4rent
- **Location**: `/cities4rent/index.md`
- **Purpose**: A project that works with Airbnb data analysis
- **Content**: Simple Markdown page describing the project

## Development Workflow

Since this is a GitHub Pages repository:

1. **Local Development**: Edit Markdown files directly
2. **Preview**: GitHub Pages automatically builds and serves the site after commits to main branch
3. **Deployment**: Automatic via GitHub Pages when changes are pushed to main

## File Structure

```
bernomone.github.io/
├── _config.yml
├── cities4rent/
│   └── index.md
└── CLAUDE.md (this file)
```

## Theme Configuration

- **Theme**: Uses the `minima` theme (GitHub Pages supported)
- **Configuration**: `_config.yml` contains site-wide settings
- **Front Matter**: Each page uses YAML front matter for layout and metadata

## Adding New Projects

To add a new project:
1. Create a new subdirectory in the repository root
2. Add an `index.md` file with YAML front matter:
   ```yaml
   ---
   layout: default
   title: Project Name
   description: Project description
   ---
   ```
3. Follow the existing pattern established by `cities4rent/`

## Notes

- No build process or package management required
- Repository relies on GitHub Pages' built-in Jekyll processing
- All content is served as static pages
- Simple Markdown-based content structure