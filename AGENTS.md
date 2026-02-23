# Agent Instructions

## Project Overview

CTech company website — a static site deployed to GitHub Pages via GitHub Actions.

## Repository Structure

- `index.html` — Main (and currently only) page
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

## Git Workflow

- Commits and pushes to `main` are allowed and will trigger an automatic deployment to GitHub Pages.
- Write clear, concise commit messages.
- Double-check diffs before committing — remember, everything pushed is immediately public.
