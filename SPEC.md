# TBWPP — The Big Wedding Planning Podcast

## Version
v0.2.0

## Technology
- Static single-page site (HTML/CSS/JS in one file)
- No framework, no build step, no dependencies
- Google Fonts: Inter (400–900)
- Hosting: Netlify (static)
- Mailing list: Mailchimp (free tier, to be integrated)

## Design System
Swiss-inspired, high-contrast B&W with one vibrant accent color. Bold grotesque typography (Inter 900 for display, tight letter-spacing). Flat — no shadows. See DESIGN.md and PRODUCT.md for full brand/design context.

Three accent color options under evaluation:
- Lime green (#84cc16)
- Orange (#f97316)
- Royal blue (#2563eb)

## Pages / Features
Single landing page with these sections (top to bottom):

1. **Nav** — TBWPP wordmark, links to About/Listen/Sign Up
2. **Hero** — Display headline ("Wedding planning for the rest of us."), tagline, mailing list signup form
3. **Stats bar** — 400+ episodes, 3.5M+ downloads, since 2016, 20+ years experience. Black background.
4. **About Michelle** — Photo placeholder, label, name, bio. Two-column layout.
5. **Coming Soon** — Teaser for new products. Black background. Intentionally vague.
6. **Testimonials** — 4 real listener reviews in 2-column grid.
7. **Listen** — Apple Podcasts + Spotify links. Black background.
8. **Footer CTA** — Repeat mailing list signup form.
9. **Footer** — Copyright line.

**Color switcher** (temporary): Fixed pill in top-right corner with 3 swatches to compare accent colors. Remove before final deploy.

## Data Model
- Static content, no backend
- Mailing list form submits to Mailchimp (TODO: integrate)
- Podcast links: Apple Podcasts + Spotify (TODO: add real URLs)

## Version History
| Version | Date | Summary |
|---------|------|---------|
| v0.1.0 | 2026-05-01 | Project scaffolding and design planning |
| v0.2.0 | 2026-05-01 | Landing page built — all sections, 3 accent colors, responsive, a11y |
