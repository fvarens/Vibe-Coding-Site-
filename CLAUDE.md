# Focus Stack - Landing Page

## Project Overview

Static landing page for **Focus Stack**, a web design and automated lead follow-up service for law firms.

## Tech Stack

- Vanilla HTML5, CSS3, and JavaScript (no build tools or frameworks)
- Google Fonts (Playfair Display, DM Sans)
- All styles and scripts are inline in the HTML file

## Project Structure

```
index.html.html    # Main (and only) landing page
.superpowers/      # Superpowers skills framework (git submodule)
.claude/           # Claude Code project configuration
```

## Development Notes

- This is a single-page static site with no build process
- Open `index.html.html` directly in a browser to preview
- CSS uses custom properties (variables) for theming
- Responsive breakpoints at 768px and 480px
- Intersection Observer API used for scroll animations

## Superpowers Integration

This project uses the [superpowers](https://github.com/obra/superpowers) agentic skills framework. The `.superpowers/` directory is a git submodule. The SessionStart hook in `.claude/settings.json` bootstraps the skills framework automatically.

To update superpowers to the latest version:
```bash
git submodule update --remote .superpowers
```
