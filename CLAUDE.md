# CLAUDE.md

## Repository Purpose

Personal CV/resume portfolio site — pure static HTML. Deployed to https://mareox.github.io/cv-page/

## Architecture

- **Single `index.html`** with embedded CSS and vanilla JS — no build tools, no frameworks
- **Resume PDF** at `static/Mario_Sanchez_Resume.pdf`
- **Deployment:** GitHub Actions uploads repo root directly to GitHub Pages (no build step)

## Editing Content

All content lives in `index.html`. Sections in scroll order:
1. Hero — name, title, value prop, resume download CTA
2. About — professional summary with metric cards
3. AI-Enhanced Engineering — three pillars (workflows, security research, diagnostic tools)
4. Experience — timeline of PANW career progression
5. Skills — grouped tag chips (Security, Cloud, Automation, AI/ML, Infrastructure)
6. Projects — card grid (Homelab, DNS Automation, SCM Converter, Troubleshooting Tools)
7. Certifications & Education
8. Footer — social links, resume download

## Local Preview

Open `index.html` directly in a browser — no server needed.

## Deployment

Automatic via GitHub Actions on push to `main`. No build step — the workflow uploads the repo root as-is.

## Related

- **Homelab Journal:** `~/GIT/homelab-journal/` — linked from hero, about, projects, and footer
- **Resume source:** `U:\Users\MareoX\Documents\Resume\2026\resume.json`
