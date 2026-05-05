# TBWPP — The Big Wedding Planning Podcast

## Version
v0.3.0

## Technology
- Static single-page site (HTML/CSS/JS in one file)
- No framework, no build step, no dependencies
- Google Fonts: Inter (400–900)
- Hosting: Netlify (free tier), auto-deploys from GitHub
- Mailing list: Make.com webhook → Google Sheets
- Repo: https://github.com/Joseluissf/tbwpp
- Live: https://thebigweddingplanningpodcast.com

## Design System
Swiss-inspired, high-contrast B&W with hot pink accent (#f92a7e). Bold grotesque typography (Inter 900 for display, tight letter-spacing). Flat — no shadows. Rounded corners (12px buttons/inputs, 16px images). See DESIGN.md and PRODUCT.md for full brand/design context.

## Pages / Features
Single landing page with these sections (top to bottom):

1. **Nav** — TBWPP wordmark, links to About/Listen/Sign Up
2. **Hero** — Show art (480px desktop), display headline ("Wedding planning for the rest of us."), tagline, mailing list signup form, Instagram + TikTok pill buttons. On mobile: art → headline → form → social.
3. **Stats bar** — 400+ episodes, 3.5M+ downloads, since 2016, 20+ years experience. Black background.
4. **About Michelle** — Photo (rounded), label, name, bio. Two-column layout.
5. **Coming Soon** — Teaser for new products. Black background. Intentionally vague.
6. **Testimonials** — 4 real listener reviews in 2-column grid.
7. **Listen** — Apple Podcasts + Spotify links (rounded pill buttons). Black background.
8. **Footer CTA** — Repeat mailing list signup form.
9. **Footer** — Copyright line.

## Data Model
- Static content, no backend
- Signup form sends GET to Make.com webhook (`?email=value`) → Google Sheets ("TBWPP / The Big Wedding Planning Podcasts", sheet "Website Launch")
- Podcast links: Apple Podcasts, Spotify (external)
- Social links: Instagram, TikTok (external)

## Assets
- `show-art.jpg` — podcast cover art (diamond ring with rainbow rays)
- `michelle.webp` — host headshot photo

## Version History
| Version | Date | Summary |
|---------|------|---------|
| v0.1.0 | 2026-05-01 | Project scaffolding and design planning |
| v0.2.0 | 2026-05-01 | Landing page built — all sections, responsive, a11y |
| v0.3.0 | 2026-05-05 | Launched — accent color, show art, social links, Make.com signup, Netlify deploy, custom domain |
