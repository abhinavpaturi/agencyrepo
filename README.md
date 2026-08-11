# Marketing + AI Studio Site

One-page site for a productized marketing & AI integration business serving local
service businesses. Plain static files — no build step, no dependencies: `index.html`,
`styles.css`, `script.js`.

**Core products on the page**

1. **Local Ads Engine** — done-for-you Meta & Google ads, including a free one-time digital
   makeover (social profiles refresh, Google Business Profile optimization, booking system
   setup if needed).
2. **AI Front Desk** — AI receptionist: answers calls/texts 24/7, missed-call text-back,
   books appointments into your booking system.

Plus six add-on services (Review Engine, Website-in-a-Week, Customer Win-Back, Local SEO
Care Plan, AI Chat for Web & DMs, CRM & Lead Tracking), how-it-works, FAQ, and a
free-audit CTA.

## Before you launch — placeholder checklist

Search `index.html` for `TODO`. Every placeholder is marked:

- [ ] **Business name** — "Booked & Answered" is a placeholder (nav, footer, `<title>`,
      OG tags, JSON-LD). Keep it or rename everywhere.
- [ ] **Pricing** — `$750/mo` (ads) and `$249/mo` (AI receptionist) are sample CAD numbers.
- [ ] **Email & phone** — `hello@example.com` and `(226) 555-0134` are fake. Update the
      two CTA buttons in `#contact` and the JSON-LD `telephone`.
- [ ] **Booking link** — ideally point the audit CTAs at a Cal.com/Calendly link instead
      of `mailto:`.
- [ ] **Domain** — set `og:url` and the JSON-LD `url` once you have one.
- [ ] Optional: add an `og:image` (1200×630) for link previews, and your analytics/pixel
      tags before running ads to this page.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy free with GitHub Pages

1. Make the repo **public** (Settings → General → Danger Zone → Change visibility) —
   free GitHub Pages requires it.
2. **Settings → Pages → Deploy from a branch → `main` / root → Save.**

The site goes live at `https://abhinavpaturi.github.io/agencyrepo/` in about a minute,
and every push to `main` deploys automatically. Add a custom domain later in the same
settings screen (free HTTPS included).
