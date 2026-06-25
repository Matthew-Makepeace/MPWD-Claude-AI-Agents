# Cowork Prompt — Concepts Salon Spa Web Redesign
*(Paste into Claude Cowork)*

---

I'm Matthew Makepeace (Makepeace Web Design). I'm working on a **website redesign package** for a client, **Concepts Salon Spa**. I need you to (1) get up to speed, (2) understand the hosting situation we just resolved, and (3) **record this project in Notion** so it's properly documented and trackable.

## The Client
- Concepts Salon Spa — full-service hair & beauty salon, **established 1982**
- 60 Bloor Street West, Toronto (inside Manulife Centre, Bloor-Yorkville)
- Contacts: **Sussan Soares** (Manager, primary contact), **Edward** (Owner)
- Existing site: conceptstoronto.com (old, broken)

## The Engagement
- **Web redesign package — 8 pages**
- Price: **$700 + 13% HST = $791 CAD**, in 3 milestones (30/40/30):
  - M1 (30%): $237.30 — **PAID** (received $237.20 by cheque; $0.10 short, carried to M2)
  - M2 (40%): $316.50 (incl. $0.10 carry) — due at development / design sign-off
  - M3 (30%): $237.30 — due at launch
- Recurring revenue plan: pitch a bundled **"Website Care Plan" at $185/mo + HST** (hosting + maintenance) at LAUNCH (not before).

## The Problem We Just Resolved (key context)
The original plan was to migrate the existing WordPress site to better hosting. It became a multi-hour ordeal:
- Old site: **WordPress 5.2.21 on Bell Canada**, no SSL (broken), broken plugins.
- Bell's broken SSL blocked all plugin installs/downloads (cURL error 60).
- The site export ballooned to **2GB+** from **1,724 leftover UpdraftPlus backups** (5.2GB) — cleared them, re-exported.
- All-in-One WP Migration import **stalled at 0%** ("restoring database") due to a **PHP 7 → PHP 8 mismatch** (Hostinger only offers PHP 8.2+, can't match the old PHP 7).
- **DECISION: Abandoned the migration. Building the redesign FRESH on Hostinger.**

## Current State
- New build home: clean WordPress on **Hostinger Business** plan → temp URL **`sienna-meerkat-802382.hostingersite.com`** (PHP 8.3, WP 7.0).
- Old Bell site stays LIVE & untouched until launch.
- At launch: **point conceptstoronto.com to Hostinger** (needs domain login from Edward/Sussan). **KEEP conceptstoronto.com** to preserve 40 years of SEO — do NOT switch to a new domain. (Optionally register conceptssalonspa.com in the client's name as a protective 301-redirect only.)
- Domain/hosting account must be owned by the CLIENT, not Matthew.

## Design System (LOCKED)
| Role | Hex | Name |
|------|-----|------|
| Page background | #f6e6e4 | Cream |
| Accent sections | #D4A5A0 | Dusty Blush |
| Secondary cards/dividers | #b79a8d | Rose Taupe |
| CTA button / footer | #503123 | Espresso |
| Links / hover / accents | #C9A96E | Antique Gold |
| Header | #6f675b | Warm Taupe |

- Fonts: **Josefin Sans** (headers, all-caps subheads, min 18px) + **Montserrat** (body/nav/buttons)

## Information Architecture (8 pages)
- **Home:** Hero · Our Salon · Services · Gallery · Testimonials
- **About:** Description · Values (Why Us) · FAQs
- **Services:** Item Pricing & Filters (format: "Service Name …… $price") · FAQs
- **Brands:** Logos + short descriptions
- **Gallery:** filter tabs · masonry grid · Instagram CTA
- **Contact:** Info (first) · Form · Google Maps · FAQs
- **Policies:** footer nav only
- **Promotions:** footer nav only
- **Header nav:** Services | About | Brands | Contact | [Book Now]
- **Footer:** Info | Hours & Social | Nav (3-column)

## Build Plan
- Builder: **Elementor** · SEO: **RankMath** · Forms: **WPForms**
- Hero copy (Aurther): "ONE SALON. EVERY SERVICE." or "Forty Years on Bloor Street. Still Your Best Look."
- SEO (Kristine, Tier 2): anchor keyword "hair salon Yorkville Toronto"
- Services + pricing and brand list already gathered (see client profile).

## Open Items (TBD with client)
- Booking platform (Vagaro / Fresha / Jane?)
- Photography (need REAL photos — no stock salon people)
- Which brands to feature
- Domain login from Edward/Sussan (for launch)

## What I need you to do
1. **Read the full client profile** for complete detail: `clients/concepts/concepts-client-profile.md`
2. **Create a Notion project page/workspace for Concepts Salon Spa** that captures: project overview, current status, milestone/payment tracking, the hosting decision + problem log, the design system, the IA, the build plan, and the open items above.
3. Structure it so I can track build progress and update it as the project moves toward launch.
