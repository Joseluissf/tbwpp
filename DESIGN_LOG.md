# TBWPP Design Log

Design decisions and rationale, append-only.

---

## v0.1.0 — Project Setup (2026-05-01)

### Project Scaffolding
- **Decision:** Created project at `~/projects/code/tbwpp/` as a static landing page with no framework or build step.
- **Rationale:** A podcast landing page is primarily content and branding — a single HTML/CSS/JS file keeps it simple, fast, and easy to deploy anywhere. Matches the approach used in other projects (JL2, portfolio-site).

### Design Tooling
- **Decision:** Set up impeccable skill for design planning and iteration.
- **Rationale:** Using `$impeccable teach` to define brand identity (PRODUCT.md) and `$impeccable shape` to plan the landing page UX/UI before writing code. This ensures design choices are intentional, not default.

---

## v0.2.0 — Landing Page Build (2026-05-01)

### Creative Direction: "The Swiss Wedding Zine"
- **Decision:** Swiss poster-inspired design. High-contrast B&W palette with one vibrant accent. Bold grotesque typography (Inter 900) with tight letter-spacing on display, open on body. Flat — no shadows, no elevation.
- **Rationale:** The brand is warm, real, and empowering — not precious or aspirational. Swiss fundamentals give it credibility and edge without feeling like a wedding brand. The B&W foundation keeps it timeless; the accent color adds energy without clutter.

### Accent Color Exploration
- **Decision:** Built three accent color options (lime green, orange, royal blue) with a live switcher to compare.
- **Rationale:** User wanted to see all three before committing. The switcher makes it easy to evaluate in context rather than guessing from swatches.

### Section Architecture
- **Decision:** Seven sections in this order: Hero (with signup), Stats bar, About Michelle, Coming Soon teaser, Testimonials, Listen links, Footer CTA (repeat signup).
- **Rationale:** Signup form appears twice (hero + footer) to catch both immediate converters and scrollers. Stats bar immediately after hero establishes credibility. "Coming Soon" is intentionally vague — new products are in development but not announced. Testimonials provide social proof. Listen links are secondary to signup.

### Typography: Inter
- **Decision:** Inter as the sole typeface, weight 900 for display, standard weights for body.
- **Rationale:** Swiss-inspired direction called for a grotesque sans. Inter is free (Google Fonts), has excellent weight range, and supports tight tracking well. Single-family approach keeps loading fast and the system simple for a quick ship.

### Mailing List: Mailchimp
- **Decision:** Mailchimp for email collection instead of Make.com.
- **Rationale:** Make.com is an automation platform, not a mailing list provider. Mailchimp is free up to 500 contacts, provides embeddable forms, and scales into full email marketing. Not a temporary solution — it's the real infrastructure from day one.

### Host Update
- **Decision:** Removed Shaun Gray from all project materials. TBWPP is now presented as Michelle D. Martinez solo.
- **Rationale:** Shaun is no longer part of the podcast.
