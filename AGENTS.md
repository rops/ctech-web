# Agent Instructions — CTech Website

## Project Overview

Website for **Computer's Technology S.r.l.** (CTech), a small Italian IT company (~5 people, <1M revenue) based in Piediripa di Macerata (MC), founded in 1984. They resell and support software + hardware/IT infrastructure.

## Tech Stack

- **Pure static HTML/CSS**, no frameworks, no build step
- Each page has its own inline `<style>` block (shared palette via CSS variables)
- Deployed to **GitHub Pages** via rsync workflow (excludes `materiali/` and `archive/`)

## Working Agreement

- Use concise, direct language (Italian)
- Propose a short plan before starting implementation
- Keep the site lightweight and fast
- Tone: direct, honest, professional but not corporate. "Siamo una piccola azienda e lo consideriamo un vantaggio." No fluff

## Site Structure

```
index.html         — Homepage (organized by target audience)
arca.html           — Arca EVOLUTION (ERP for businesses)
winwaste.html       — WinWaste (waste management software)
genya.html          — BPoint / Genya (accountant software)
contatti.html       — Contact page with form (Formspree)
assistenza.html     — Support page with SupRemo download
privacy.html        — (TODO) Privacy policy
cookie.html         — (TODO) Cookie policy
```

## Navigation

```
Home | Arca Evolution | WinWaste | BPoint/Genya | Contatti | [Assistenza] (CTA button)
```

## Brand Palette

| Variable | Hex | Role |
|---|---|---|
| `--ctech-red` | `#C52A2A` | CTech brand red (logo, links, CTA, accent) |
| `--ctech-red-dark` | `#A01E1E` | Hover states |
| `--ctech-navy` | `#1A2B4A` | Header, hero, footer backgrounds |
| `--blue` | `#007AC3` | Wolters Kluwer blue — "aziende" area |
| `--green` | `#059669` | "Rifiuti" area |
| `--amber` | `#d97706` | "Professionisti" area |
| `--teal` | `#00B8A9` | ESET teal — IT/cybersecurity accent |

## Products & Services

| Product | Producer | Territory | Target |
|---|---|---|---|
| Arca Evolution | Wolters Kluwer | Marche | Aziende (PMI) |
| WinWaste | Nica / Zucchetti | Marche, Umbria, Abruzzo | Gestione rifiuti |
| BPoint | WK/OSRA | Marche | Professionisti (dismissione 2030) |
| Genya | WK/OSRA | Marche | Professionisti (cloud, il futuro) |
| ESET | ESET | Marche | Tutti (cybersecurity) |
| Hardware/IT | Dell, HP, Microsoft | Marche | Tutti |

## Key Decisions

- Homepage organized by **target audience** (aziende, professionisti, rifiuti), not by product
- IT + Cybersecurity are **cross-cutting** — serve all client types
- Each person in the company handles one area exclusively
- No social media presence and no plans for it
- Contact form uses **Formspree** (action: `https://formspree.io/f/xpwzgqwn`)
- Remote support via **SupRemo** (link to download page)

## Content Sources

- Brand materials in `materiali/` (logos, brochures, screenshots)
- Old site archived in `archive/` (HTML, CSS, images, PDFs) — use for reference only
- Partner logos (SVG) in `archive/v0/assets/img/partner/`
- Client logos in `archive/v0/assets/img/clienti/`
- Product brochures in `archive/v0/assets/attachments/`

## Security

- Never include secrets, credentials, or private URLs
- This repository is public

## Remaining TODO

- Privacy and Cookie policy pages
- Proper logo file (transparent PNG or SVG) — user needs to provide source
- Consider extracting shared CSS to `style.css` if pages diverge
