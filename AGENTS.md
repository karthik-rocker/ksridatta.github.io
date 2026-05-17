# AGENTS.md

Guidance for AI coding agents working in this repository.

## Project Purpose

- Maintain a student portfolio website that highlights resume and projects.
- Site is hosted as a static GitHub Pages site with a custom domain.

## Tech Stack

- Plain static HTML and inline CSS only.
- No framework, bundler, package manager, or test runner.

## Key Files

- `index.html`: landing page and primary navigation.
- `resume.html`: embedded resume viewer and resume download/open actions.
- `Karthik_Sridatta_ATS_Final.pdf`: resume file used by `resume.html`.
- `CNAME`: custom domain configuration for GitHub Pages.
- `README.md`: minimal project identifier.

## Safe Change Rules

- Keep the site fully static; avoid introducing build tools unless explicitly requested.
- Preserve mobile responsiveness when editing layout or styles.
- Keep existing navigation working:
  - Home: `/`
  - Resume page: `/resume.html`
  - Resume PDF: `/Karthik_Sridatta_ATS_Final.pdf`
- Keep accessibility basics intact (semantic headings, readable contrast, `aria-label` where present).
- Do not rename or move `CNAME` or the resume PDF unless asked.

## Common Tasks

- Add/update project showcase content in `index.html`.
- Refresh resume view/download links in `resume.html` if resume filename changes.
- Adjust visual style while preserving existing page purpose and links.

## Local Validation

- Quick preview with a static server from repo root:
  - `python -m http.server 8000`
- Then verify these URLs manually:
  - `http://localhost:8000/`
  - `http://localhost:8000/resume.html`
  - Resume button opens the expected PDF.

## Completion Checklist For Agents

- Navigation links work on desktop and mobile widths.
- Resume PDF loads from both `resume.html` button and iframe.
- No accidental framework/tooling files were added.
- `CNAME` remains unchanged.
