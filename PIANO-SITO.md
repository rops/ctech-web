# Piano Sito CTech — Computer's Technology S.r.l.

> Piano completo per la ricostruzione del sito web aziendale.
> Ultimo aggiornamento: Febbraio 2026

---

## 1. Informazioni Aziendali

- **Ragione sociale:** Computer's Technology S.r.l.
- **Fondazione:** 1984
- **Sede:** Via Cluentina, 26/B — Loc. Piediripa di Macerata (MC), 62100
- **Telefono:** 0733.281142 / 292776
- **Email:** info@ctech.it
- **P.IVA:** 00840390439
- **GA4 ID:** G-BC7DWNT8X2

---

## 2. Mappa del Sito (13 pagine)

| # | File | Pagina | Milestone |
|---|------|--------|-----------|
| 1 | `index.html` | Home | M1 |
| 2 | `contatti.html` | Contatti | M1 |
| 3 | `grazie.html` | Grazie (post-form) | M1 |
| 4 | `azienda.html` | Chi Siamo | M2 |
| 5 | `arca.html` | Arca EVOLUTION | M2 |
| 6 | `winwaste.html` | WinWaste (+ sezione R.E.N.T.Ri #rentri) | M2 |
| 7 | `osra-bpoint.html` | B.Point Solution Platform | M3 |
| 8 | `osra-genya.html` | Genya | M3 |
| 9 | `eset.html` | ESET Cybersecurity | M3 |
| 10 | `assistenza.html` | Assistenza Tecnica | M3 |
| 11 | `servizi-it.html` | Servizi IT / Infrastruttura | M3 |
| 12 | `privacy.html` | Privacy Policy | M4 |
| 13 | `cookie-policy.html` | Cookie Policy | M4 |

**Nota:** I nomi `osra-bpoint.html` e `osra-genya.html` sono mantenuti per compatibilità con i link esistenti (nessun redirect 301 possibile su GitHub Pages).

---

## 3. Navigazione

```
Logo (sx)                                                  Hamburger (mobile)
─────────────────────────────────────────────────────────
Home | Chi Siamo | Soluzioni ▾ | Servizi ▾ | Contatti

Soluzioni:
  ├── Arca EVOLUTION (gestionale)
  ├── WinWaste (gestione rifiuti)
  ├── B.Point (fiscale)
  └── Genya (fiscale cloud)

Servizi:
  ├── Assistenza Tecnica
  ├── Servizi IT / Infrastruttura
  └── ESET Cybersecurity
```

---

## 4. Design System

### Palette

| Ruolo | Colore | Hex | Uso |
|-------|--------|-----|-----|
| Primary (CTA/Accent) | Rosso CTech | `#C52A2A` | Bottoni, link hover, badge |
| Primary Dark | Rosso scuro | `#A01E1E` | Hover sui bottoni |
| Secondary (Structure) | Navy | `#1A2B4A` | Header, footer, titoli |
| Secondary Light | Navy chiaro | `#243B63` | Hover navbar |
| Background | Bianco | `#FFFFFF` | Sfondo principale |
| Surface | Grigio chiaro | `#F5F7FA` | Sezioni alternate |
| Text | Grigio scuro | `#2D3748` | Corpo testo |
| Text Light | Grigio medio | `#64748B` | Testo secondario |
| Border | Grigio bordo | `#E2E8F0` | Bordi, separatori |

### Tipografia

- **Font:** Inter (Google Fonts), fallback: system-ui, sans-serif
- **H1:** 2.5rem (40px), bold 700, line-height 1.2
- **H2:** 2rem (32px), bold 700, line-height 1.3
- **H3:** 1.5rem (24px), semibold 600, line-height 1.4
- **H4:** 1.25rem (20px), semibold 600, line-height 1.4
- **Body:** 1rem (16px), regular 400, line-height 1.7
- **Small:** 0.875rem (14px)

### Spaziatura

- Base unit: 0.5rem (8px)
- Section padding: 5rem (80px) top/bottom
- Container max-width: 1200px
- Border radius: 8px (cards), 6px (buttons), 4px (inputs)

### Componenti

- **Bottoni CTA:** Sfondo `#C52A2A`, testo bianco, padding 0.875rem 2rem, border-radius 6px, hover `#A01E1E`
- **Bottoni Secondary:** Sfondo bianco, bordo `#C52A2A`, testo `#C52A2A`, hover sfondo `#C52A2A` + testo bianco
- **Card:** Sfondo bianco, border 1px `#E2E8F0`, border-radius 8px, box-shadow subtle, hover lift
- **Badge:** Piccolo tag con sfondo leggero + testo colorato

---

## 5. Keyword Map & SEO

### Homepage (`index.html`)
- **Title:** Computer's Technology — Software Gestionale e Servizi IT a Macerata
- **Meta:** Soluzioni software per aziende e professionisti nelle Marche. Arca EVOLUTION, WinWaste, B.Point, Genya. Assistenza e consulenza IT dal 1984.
- **Keywords:** software gestionale macerata, assistenza informatica macerata, consulenza IT marche, Arca EVOLUTION macerata

### Contatti (`contatti.html`)
- **Title:** Contatti — Computer's Technology | Macerata
- **Meta:** Contattaci per una consulenza gratuita. Sede a Piediripa di Macerata. Tel. 0733.281142 — info@ctech.it.
- **Keywords:** contatti ctech, computer's technology macerata, assistenza informatica macerata

### Chi Siamo (`azienda.html`)
- **Title:** Chi Siamo — Computer's Technology | Dal 1984 al fianco delle imprese
- **Meta:** Oltre 40 anni di esperienza IT nelle Marche. Partner Wolters Kluwer, Zucchetti, ESET. 300+ clienti soddisfatti.
- **Keywords:** azienda informatica macerata, partner wolters kluwer marche, assistenza IT macerata

### Arca EVOLUTION (`arca.html`)
- **Title:** Arca EVOLUTION — Software Gestionale ERP | CTech Macerata
- **Meta:** Arca EVOLUTION di Wolters Kluwer: gestionale ERP per PMI. Contabilità, magazzino, fatturazione elettronica, CRM. Rivenditore autorizzato Marche.
- **Keywords:** arca evolution, software gestionale ERP, gestionale aziendale macerata, wolters kluwer arca, fatturazione elettronica gestionale

### WinWaste (`winwaste.html`)
- **Title:** WinWaste — Software Gestione Rifiuti | R.E.N.T.Ri | CTech
- **Meta:** WinWaste (Zucchetti Ambiente): software per la gestione rifiuti e registro elettronico R.E.N.T.Ri. Assistenza in Marche, Umbria e Abruzzo.
- **Keywords:** winwaste, software gestione rifiuti, rentri software, registro elettronico rifiuti, MUD software

### B.Point (`osra-bpoint.html`)
- **Title:** B.Point Solution Platform — Software Fiscale Commercialisti | CTech
- **Meta:** B.Point di Wolters Kluwer: piattaforma completa per commercialisti e studi professionali. Dichiarazioni, contabilità, paghe. Assistenza Marche.
- **Keywords:** bpoint, b.point solution platform, software commercialista, wolters kluwer fiscale, software studio professionale

### Genya (`osra-genya.html`)
- **Title:** Genya — Gestione Fiscale in Cloud | Wolters Kluwer | CTech
- **Meta:** Genya: la suite cloud Wolters Kluwer per commercialisti. Contabilità, dichiarativi, bilanci. Automatizzazione e collaborazione studio-cliente.
- **Keywords:** genya, genya wolters kluwer, software commercialista cloud, gestione fiscale cloud

### ESET (`eset.html`)
- **Title:** ESET Cybersecurity — Antivirus e Protezione Aziendale | CTech
- **Meta:** Soluzioni ESET per la sicurezza informatica aziendale. Antivirus, endpoint protection, gestione centralizzata. Rivenditore Marche.
- **Keywords:** eset macerata, antivirus aziendale, sicurezza informatica PMI, endpoint protection

### Assistenza (`assistenza.html`)
- **Title:** Assistenza Tecnica Informatica — Computer's Technology | Macerata
- **Meta:** Assistenza tecnica IT per aziende e studi professionali. Supporto on-site e remoto, contratti di manutenzione, pronto intervento.
- **Keywords:** assistenza tecnica informatica macerata, supporto IT aziende, manutenzione informatica

### Servizi IT (`servizi-it.html`)
- **Title:** Servizi IT e Infrastruttura — CTech | Macerata
- **Meta:** Progettazione reti, server, cloud migration, backup, virtualizzazione. Infrastruttura IT per PMI nelle Marche.
- **Keywords:** servizi IT macerata, infrastruttura informatica, cloud migration PMI, reti aziendali

---

## 6. Copertura Territoriale

| Servizio | Area |
|----------|------|
| Arca EVOLUTION | Marche |
| B.Point | Marche |
| Genya | Marche |
| WinWaste | Marche, Umbria, Abruzzo |
| ESET | Marche |
| Assistenza / Servizi IT | Marche |

---

## 7. Strategia CTA (per pagina)

| Pagina | CTA Primaria | CTA Secondaria |
|--------|-------------|----------------|
| Home | "Richiedi una consulenza gratuita" → contatti.html | Telefono cliccabile |
| Chi Siamo | "Scopri le nostre soluzioni" → #soluzioni home | "Contattaci" |
| Arca EVOLUTION | "Richiedi una demo gratuita" → contatti.html?servizio=arca | "Scarica brochure" |
| WinWaste | "Verifica la conformità R.E.N.T.Ri" → contatti.html?servizio=winwaste | "Richiedi demo" |
| B.Point | "Richiedi una demo" → contatti.html?servizio=bpoint | — |
| Genya | "Prova Genya gratuitamente" → contatti.html?servizio=genya | — |
| ESET | "Richiedi un preventivo" → contatti.html?servizio=eset | — |
| Assistenza | "Richiedi assistenza" → contatti.html?servizio=assistenza | Telefono |
| Servizi IT | "Richiedi un sopralluogo" → contatti.html?servizio=servizi-it | — |
| Contatti | Form Formspree (multi-checkbox) | Telefono + Email + Mappa |

---

## 8. Scadenze R.E.N.T.Ri (da evidenziare su winwaste.html)

- **Dicembre 2023:** Iscrizione operatori >50 dipendenti (già attivo)
- **14 Agosto 2025:** Operatori 11-50 dipendenti
- **13 Febbraio 2026:** Operatori <10 dipendenti + rifiuti pericolosi

---

## 9. Specifiche Tecniche

- **Hosting:** GitHub Pages (static site)
- **CSS:** Custom pure (no framework). CSS variables, Grid, Flexbox
- **Font:** Inter (Google Fonts)
- **Form:** Formspree (free tier, 50 submissions/month). Telefono + email sempre visibili come fallback
- **Cookie banner:** Native HTML/CSS/JS (no third-party)
- **GA4:** G-BC7DWNT8X2
- **Performance:** < 2s load, < 100KB CSS, lighthouse 90+
- **Schema.org:** LocalBusiness, SoftwareApplication
- **Open Graph:** Meta tags per ogni pagina
- **Lang:** `it`
- **No build step, no bundler, no package manager**

---

## 10. Roadmap

### Milestone 1 — Fondamenta (settimana corrente)
- [x] Creazione directory e asset
- [ ] `style.css` — design system completo
- [ ] Navbar responsive + Footer
- [ ] `index.html` — homepage completa
- [ ] `contatti.html` — form Formspree multi-checkbox
- [ ] `grazie.html` — pagina ringraziamento
- [ ] Cookie banner GDPR
- [ ] Favicon, GA4, meta tags
- [ ] Deploy e verifica su GitHub Pages

### Milestone 2 — Pagine Prodotto Core
- [ ] `azienda.html` — Chi Siamo
- [ ] `arca.html` — Arca EVOLUTION
- [ ] `winwaste.html` — WinWaste + sezione R.E.N.T.Ri

### Milestone 3 — Pagine Complementari
- [ ] `osra-bpoint.html` — B.Point
- [ ] `osra-genya.html` — Genya
- [ ] `eset.html` — ESET Cybersecurity
- [ ] `assistenza.html` — Assistenza Tecnica
- [ ] `servizi-it.html` — Servizi IT

### Milestone 4 — Rifinitura
- [ ] `privacy.html` — Privacy Policy
- [ ] `cookie-policy.html` — Cookie Policy
- [ ] Schema.org structured data
- [ ] Open Graph tags
- [ ] Performance optimization
- [ ] Cross-browser testing
