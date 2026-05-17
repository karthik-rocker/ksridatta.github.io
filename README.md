# Karthik Sridatta Portfolio Website

Personal portfolio website focused on AI development, backend engineering, and internship readiness.

## Live Site

- Custom domain: https://karthik.codes
- GitHub Pages URL: https://karthik-rocker.github.io/ksridatta.github.io/

## Overview

This is a fully static GitHub Pages portfolio with two main pages:

- Home page (`index.html`): AI-themed landing page with infographics, project cards, tech logos, contact links, and theme selector.
- Resume page (`resume.html`): Dashboard-style resume with capability meters, timeline, certifications, and one-page recruiter snapshot.

Resume PDF is available at:

- `Karthik_Sridatta_ATS_Final.pdf`

## Features

- Creative AI-inspired visual design
- Multiple theme options (Dark, Light, Aurora, Sunset)
- Theme persistence using `localStorage`
- Mobile responsive layout
- Accessibility improvements:
	- Skip-to-content links
	- Keyboard focus states
	- Reduced-motion support
- Technology logos and infographic sections
- Recruiter-friendly one-page snapshot section on the resume page

## Tech Stack

- Plain HTML + CSS + vanilla JavaScript
- Static hosting with GitHub Pages
- No framework, no build tool, no package manager

## Run Locally

From repository root:

```bash
python -m http.server 8000
```

Open:

- http://localhost:8000/
- http://localhost:8000/resume.html
- http://localhost:8000/Karthik_Sridatta_ATS_Final.pdf

## Deployment

Deployment is automatic through GitHub Pages from the `main` branch.

Standard deploy flow:

```bash
git add .
git commit -m "Your update message"
git push
```

## Custom Domain Notes

Domain is configured via `CNAME` file:

- `CNAME` contains: `karthik.codes`

Recommended DNS setup for GitHub Pages:

- Apex `A` records:
	- `185.199.108.153`
	- `185.199.109.153`
	- `185.199.110.153`
	- `185.199.111.153`
- `www` CNAME:
	- `karthik-rocker.github.io`

## Repository Structure

- `index.html` - Home page
- `resume.html` - Resume page
- `Karthik_Sridatta_ATS_Final.pdf` - Resume PDF
- `CNAME` - Custom domain mapping
- `AGENTS.md` - Agent guidance for this repository

## Contact

- LinkedIn: https://www.linkedin.com/in/karthik-sridatta1
- GitHub (Primary): https://github.com/karthik-rocker
- GitHub (Secondary): https://github.com/1dt23is030-cmd?tab=repositories
- Featured Project: https://github.com/karthik-rocker/civil-ai-agent