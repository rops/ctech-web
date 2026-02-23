# Agent Instructions

## Project Goal

Rebuild the **Computer's Technology S.r.l.** (CTech) company website from scratch as a modern, lightweight static site deployed to GitHub Pages. The new site replaces the legacy site at http://www.ctech.it.

## About the Company

Computer's Technology S.r.l. is an IT services company founded in 1984, based in Macerata (MC), Italy. They provide software solutions and IT consulting for businesses and accounting professionals. Key offerings:

- **Arca EVOLUTION** — ERP/management software for businesses (Wolters Kluwer product)
- **WinWaste** — Waste management software (Nica/Zucchetti product)
- **B.Point Solution Platform** — Accounting and tax management for professionals (Wolters Kluwer)
- **Genya** — Cloud-based accounting and tax management (Wolters Kluwer)

Public contact details (already published on the current site):
- Address: Via Cluentina, 26/B — Loc. Piediripa di Macerata (MC), 62100
- Phone: 0733.281142 / 292776
- Email: info@ctech.it
- P.IVA: 00840390439

## Kickoff (New Session Checklist)

When starting a fresh session on this project, follow these steps **in order**. Do NOT skip ahead to implementation.

### 1. Review the legacy site

Fetch and review the current website at http://www.ctech.it (HTTP only, no HTTPS). Check all pages:
- `index.html` (Home)
- `azienda.html` (About)
- `arca.html` (Arca EVOLUTION)
- `winwaste.html` (WinWaste)
- `osra-bpoint.html` (B.Point)
- `osra-genya.html` (Genya)
- `contatti.html` (Contact)

Summarize what exists, what works, and what's outdated or broken.

### 2. Present a plan before building

Before writing any code, present a plan to the user covering:
- **Site architecture** — Single-page vs multi-page, navigation structure
- **Design direction** — Visual style, color palette, typography, layout approach
- **Content strategy** — What to keep from the legacy site, what to rewrite, what to add
- **Marketing angle** — How to position CTech (trust, experience since 1984, local presence, product partnerships)
- **Technical approach** — CSS framework (or none), responsive strategy, accessibility, performance targets
- **Contact form** — How to handle form submissions on a static site (e.g. Formspree, mailto fallback, etc.)
- **SEO basics** — Meta tags, Open Graph, structured data, Italian language targeting
- **Phased delivery** — What to ship first, what can come later

### 3. Discuss and iterate

Wait for the user's feedback on the plan. Do not start implementation until the user approves the direction. Expect back-and-forth on design choices, content tone, and priorities.

### 4. Implement incrementally

Once approved, build in small increments. Commit and push after each meaningful milestone so the user can preview on GitHub Pages. Always check the live site after deployment.

## Repository Structure

- `index.html` — Main page (single-page or multi-page as needed)
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow (triggers on push to `main`)
- `opencode.json` — OpenCode configuration (GitLab-only provider, no external file access)

## Security — PUBLIC REPOSITORY

**This repository is public and deployed to GitHub Pages. Everything committed here is visible to the world.**

- NEVER commit secrets, API keys, tokens, credentials, passwords, or internal URLs.
- NEVER commit `.env` files or any file containing sensitive configuration.
- NEVER include internal infrastructure details, IP addresses, or private hostnames.
- NEVER embed tracking IDs, analytics keys, or third-party service credentials in HTML/JS.
- If a secret is needed at build/deploy time, use GitHub Actions secrets or environment variables — never hardcode values.

## Development

- This is a plain static site — no build step, no bundler, no package manager.
- The GitHub Pages workflow uploads the entire repo root as the site artifact, so every file at the root is publicly served (except dotfiles like `.git`, `.github`).
- Keep the site lightweight and self-contained. Inline styles and scripts are fine for now.
- Use modern HTML/CSS (no jQuery, no Bootstrap dependency required). Keep it minimal and fast.

## Git Workflow

- Commits and pushes to `main` are allowed and will trigger an automatic deployment to GitHub Pages.
- Write clear, concise commit messages.
- Double-check diffs before committing — remember, everything pushed is immediately public.
