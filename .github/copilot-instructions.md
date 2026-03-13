# Copilot Instructions for AI Coding Agents

## Overview
This workspace contains multiple web projects, each organized in its own folder. The main projects are:
- **CODER-Atestat-BradStefan**: Static site with HTML, CSS, and assets
- **CoderDojo**: Educational exercises and lessons, mostly HTML/CSS
- **ItFest2026**: Event/project site with subpages and custom styles

## Architecture & Structure
- Projects are separated by folder. Each project has its own HTML and CSS files.
- No backend/server code is present; all projects are static web content.
- Asset management: Images, videos, and fonts are referenced via relative paths or external URLs (Google Fonts, etc).
- CSS is imported via `<link>` in HTML or `@import` in CSS files.
- Subfolders (e.g., `amnevoiedeajutor`, `pagini-navbar`) group related pages and styles.

## Developer Workflows
- No build tools or package managers detected. All development is direct file editing.
- No test or debug scripts; preview changes by opening HTML files in a browser.
- To add new pages, copy an existing HTML file and update links/styles as needed.

## Project-Specific Conventions
- Use relative paths for assets and stylesheets (e.g., `../css/home.css`).
- External fonts are loaded via Google Fonts `@import`.
- HTML files often include hints or comments for educational purposes.
- Required form fields use the `required` attribute.
- No JavaScript detected; interactivity is limited to HTML/CSS features.

## Integration & Dependencies
- No API calls or backend integration.
- External dependencies are limited to fonts and images via CDN or direct links.
- No cross-project communication; each folder is self-contained.

## Examples
- Linking CSS: `<link rel="stylesheet" href="../css/home.css">`
- Importing fonts: `@import url('https://fonts.googleapis.com/css2?family=Roboto...');`
- Asset usage: `<img src="../assets/images.png">`, `<video src="../assets/video.mp4">`

## Key Files & Directories
- `CODER-Atestat-BradStefan/html/` and `css/`: Main site pages and styles
- `CoderDojo/CSS/` and `Exercitii/`: Educational content and exercises
- `ItFest2026/home/`, `amnevoiedeajutor/`, `pagini-navbar/`: Event site structure

## Guidance for AI Agents
- When adding new pages, follow the folder structure and naming conventions.
- Use relative paths for all internal links and assets.
- Preserve educational hints and comments in exercise files.
- Avoid introducing build tools or backend code unless requested.
- Keep instructions concise and focused on the current project structure.

---
*Please review and suggest edits if any section is unclear or missing important project-specific details.*
