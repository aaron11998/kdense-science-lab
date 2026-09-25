# Monetization channel attempt log — cycle 3 (2026-09-16, KDE-10)

Directive: attempt actual syndication/sale of D1 (ai-clinical-trials-2026) and D2 (ai-drug-discovery-2026).
Constraints: zero capital, zero owner credentials. Log every outcome; gated channels named, not forced.

## Outcomes

| # | Channel | Method | Outcome | Evidence |
|---|---------|--------|---------|----------|
| A1 | GitHub Pages (D1) | API enable, serve README report from main | SUBMITTED (live) | https://aaron11998.github.io/ai-clinical-trials-2026/ — HTTP 200 |
| A2 | GitHub Pages (D2) | API enable, serve README report from main | SUBMITTED (live) | https://aaron11998.github.io/ai-drug-discovery-2026/ — HTTP 200 |
| A3 | Public storefront / research index (directive §4 pivot) | New org repo + Pages static site with catalog, tiers, acquisition path | SUBMITTED (live) | https://aaron11998.github.io/kdense-science-lab/ — HTTP 200, robots+sitemap 200 |
| A4 | Release-feed syndication (D1) | GitHub Release v1.0.1 notes + storefront link; releases.atom feed | SUBMITTED (live, atom HTTP 200) | releases/tag/v1.0.1 |
| A5 | Release-feed syndication (D2) | GitHub Release v1.0.0 notes + storefront link; releases.atom feed | SUBMITTED (live, atom HTTP 200) | releases/tag/v1.0.0 |
| A6 | README commercial-tier block (D1+D2) | Commit + push tier table + storefront/discussions links | SUBMITTED (pushed, live on Pages) | both READMEs |
| A7 | Crawler/dataset syndication | schema.org Dataset JSON-LD in storefront + dataset-catalog.json in both repos | SUBMITTED (live) | 3 JSON-LD blocks in storefront HTML; catalog files in repos |
| A8 | Sales-contact channel | GitHub Discussions enabled on all three repos (invoice-based acquisition path, no card rails) | SUBMITTED (live) | has_discussions=true ×3 |
| M1 | Gumroad / Lemon Squeezy / Substack | Seller marketplace listing | GATED — account signup + payment rails (owner identity); per directive §3 not forced |
| M2 | LinkedIn article (owner profile) | Native post | GATED — personal profile / owner identity (channel plan C) |
| M3 | Journalist pitches (STAT, Endpoints, Nature news) | Individually addressed email | GATED — no mail infra configured for the lab + owner-relationship channel (channel plan D) |
| M4 | Reddit / Show HN / X threads | Community posting | GATED — account signup / karma identity (channel plans E) |
| M5 | Hugging Face datasets mirror | Org dataset upload | GATED — no HF token provisioned to the lab (upload requires auth) |
| M6 | Newsletter curator outreach | Email send | GATED — same mail gate as M3 |

## Sales status

- SOLD: none yet (surfaces live < 24h; watchers: Discussions on all three repos + releases.atom).
- Open-core model per approved KDE-5 pricing doc: free datasets as top-of-funnel, paid tiers as analyst work products.

## Owner-gated batch (for chairman)

1. Payment rails: any marketplace/self-serve checkout (Gumroad/Lemon Squeezy/Stripe) — enables the $490/$1,900/$6,000 tiers as self-serve.
2. Mail identity: one SMTP/IMAP account for the lab — unlocks journalist + curator outreach (drafts ready in syndication/ of both deliverables).
3. Social identity: LinkedIn/Reddit/HN/X posts (drafts ready).

Once any gate clears, re-route per channel plans (KDE-5 for D1, KDE-9 for D2).
