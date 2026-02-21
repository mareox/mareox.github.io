# CLAUDE.md

## Repository Purpose

Personal CV/resume site using Hugo + terminalcv theme. Deployed to https://mareox.github.io/

## Commands

```bash
# Local development
hugo server

# Production build
hugo --minify
```

## Architecture

- **Theme:** terminalcv (git submodule at `themes/terminalcv/`)
- **All content lives in `config.yml`** — no markdown content files needed
- **Sections:** whois, social, work, education, skills, projects, certifications, lab (custom misc)
- **Connected to:** homelab-journal at https://mareox.github.io/homelab-journal/

## Deployment

Automatic via GitHub Actions on push to `main`. Same pattern as homelab-journal.

## Updating Resume

Edit `config.yml` directly. Sections map to terminal commands visitors can type.

## Related

- **Homelab Journal:** `~/GIT/homelab-journal/` — linked from CV greeting, whois, projects, and lab sections
- **Resume source:** `U:\Users\MareoX\Documents\Resume\2026\resume.json`
