# Copilot Instructions for This Codebase

## Project Overview
This is a single-file HTML project (`index.html`) implementing a Bootstrap-based image carousel and navigation bar. The project is minimal and does not use any build tools, frameworks, or external scripts beyond Bootstrap CDN.

## Key Patterns & Conventions
- **Bootstrap Integration:** All styling and UI components use Bootstrap 5 via CDN. No local CSS or JS files are present.
- **Single Entry Point:** All code resides in `index.html`. There are no additional assets, scripts, or configuration files.
- **No Build/Deploy Workflow:** There are no build steps, package managers, or test suites. All changes are made directly to `index.html` and viewed by opening the file in a browser.
- **Navigation Bar:** Uses Bootstrap's navbar component with dropdowns and search form. Follow Bootstrap markup conventions for any additions.
- **Image Carousel (if present):** Should use Bootstrap's carousel component. Reference Bootstrap documentation for markup and options.

## How to Extend
- **Add new UI components:** Use Bootstrap 5 markup and classes. Reference [Bootstrap 5 docs](https://getbootstrap.com/docs/5.0/components/) for patterns.
- **Add custom styles:** Inline `<style>` tags in the `<head>` are acceptable if needed. No external CSS files are used.
- **Add interactivity:** Use inline `<script>` tags in the HTML. Prefer Bootstrap's built-in JS features; avoid adding external JS libraries unless necessary.

## Examples
- To add a new button: `<button class="btn btn-primary">Click Me</button>`
- To add a new carousel: Use `<div class="carousel slide" ...>` as per Bootstrap docs.

## External Dependencies
- Bootstrap 5 (CSS and JS via CDN)

## File Reference
- `index.html`: Main and only file. All code changes should be made here.

## AI Agent Guidance
- Focus on direct HTML edits and Bootstrap patterns.
- Do not introduce build tools, package managers, or external assets unless explicitly requested.
- Keep all code self-contained in `index.html`.

---
If any conventions or workflows are unclear, ask the user for clarification before making changes.
