# Concepts Salon Spa — Client Profile

## Business Info
- **Name:** Concepts Salon Spa (standardise everywhere — current site is inconsistent)
- **Address:** 60 Bloor Street West, Toronto, ON — inside the Manulife Centre
- **Neighbourhood:** Bloor-Yorkville
- **Established:** 1982
- **Current site:** http://conceptstoronto.com (WordPress 5.2.21, HTTP only)

## Contacts
- **Sussan Soares** — Manager (not owner). Primary contact for the project. Confirm whether owner sign-off is needed on invoices/approvals.

## Project Details
- **Type:** Figma design first, then WordPress build
- **Price:** $700 + HST (13%) = $791.00 CAD
- **Invoice structure — 3 milestones (30/40/30):**
  - Milestone 1 (Design deposit 30%): $210 + HST = $237.30 — PAID 2026-06 by cheque, received $237.20 ($0.10 short, carried to M2)
  - Milestone 2 (Development phase 40%): $280 + HST = $316.40 (+ $0.10 carry = $316.50) — due at design sign-off / dev handoff
  - Milestone 3 (Launch 30%): $210 + HST = $237.30 — due on go-live
- **Invoice PO numbering:** INV-260612 (date-based format)
- **Tier:** Custom quote (Tier 2 scope — 8 pages)
- **SEO tier:** Tier 2
- **Meeting:** Met with Sussan Soares on 2026-06-11. Meeting went well.

## Pages (New IA)
1. Home
2. About
3. Services
4. Brands
5. Gallery (NEW)
6. Contact
7. Policies (NEW)
8. Promotions (footer nav only)

## Header Nav
Home | About | Services | Brands | Gallery | Contact | [BOOK NOW]

## Known Site Issues (from audit)
- WordPress 5.2.21 — critically outdated, needs update to current
- No SSL certificate (HTTP only — "Not Secure")
- Contact Form 7 returning 404 — replace with working form
- Broken Instagram feed (Access Token error)
- COVID-19 guidelines still live on homepage
- No booking button anywhere
- Inconsistent brand name across pages
- No gallery page
- No interior or team photography
- Footer has broken form instead of navigation
- Instagram linked in main header nav (move to footer icon)
- Hero leads with e-commerce delivery promo

## Questions to Confirm with Client
- [ ] Which booking platform? (Vagaro, Fresha, Jane App, Acuity?)
- [ ] Existing photography or need a shoot?
- [ ] Which 4 brands do they carry?
- [ ] Keep online store / Products page?
- [ ] Who currently has access to the WordPress backend?
- [ ] Confirm postal code (60 Bloor St W, Toronto, ON — M4W 3Y8?)

## Design Direction (FINAL — locked in)

### Colour Palette
| Role | Name | Hex |
|------|------|-----|
| Primary anchor | Espresso Brown | `#503123` |
| CTA / Action | Antique Gold | `#C9A96E` |
| Atmosphere / Personality | Dusty Blush | `#D4A5A0` |
| Background | Light Blush Cream | `#f6e6e4` |

| Role | Colour | Hex |
|------|--------|-----|
| Page background | Light Blush Cream | `#f6e6e4` |
| Accent sections (testimonials, banners) | Dusty Blush | `#D4A5A0` |
| Secondary cards / dividers / input borders | Rose Taupe | `#b79a8d` |
| CTA button | Espresso Brown | `#503123` |
| CTA hover / text links / dividers / price labels | Antique Gold | `#C9A96E` |
| Header background | Warm Taupe | `#6f675b` |
| Footer background | Espresso Brown | `#503123` |

- Never put `#D4A5A0` and `#b79a8d` adjacent — too close in tone, will muddy
- Never put `#D4A5A0` and `#f6e6e4` adjacent without espresso or gold separating them
- Gold (`#C9A96E`) fails contrast on blush backgrounds — never use as button fill
- Greyscale confirmed — tonal hierarchy holds without colour

### Typography
- **Josefin Sans** — Headers, display text. Light or Regular weight. All-caps for sub-headings. Min 18px.
- **Montserrat** — Body, nav, labels, CTAs. Regular 400 body / SemiBold 600 nav + buttons.

### Layout & UX Notes
- No stock salon photography — hero uses type + texture + colour if real photos unavailable at launch
- Gallery page confirmed in. Still need real photography — no stock salon people.
- Header nav (4 items + BOOK NOW) — confirmed cleaner. Watch hamburger breakpoint at 768–1024px.
- Policies page: footer nav only — NOT in header nav
- Floating Book Now: bottom-right, 44×44px min, fades when header CTA is visible in viewport
- Promotions page: no content layout defined yet — needs a decision before build

## Copy Direction (Aurther)
- **Tone:** Warm authority. Established. Warm. Polished. Real. Write like a trusted stylist, not a spa brochure.
- **Hero headline:** "Forty Years on Bloor Street. Still Your Best Look."
- **Hero subheadline:** "Concepts Salon Spa has been cutting, colouring, and caring for Toronto since 1982. Come see what that kind of experience feels like."
- **Mission:** "We have been making Toronto look and feel their best since 1982 — one appointment at a time."
- **Brand story (About):** "Concepts Salon Spa opened its doors on Bloor Street West in 1982 — and Toronto has been walking through them ever since..."
- **CTA strip (preferred):** "You deserve a great appointment. Book yours at Concepts Salon Spa — Bloor St West, Toronto."
- **Contact intro:** "We are right in the heart of the city — 60 Bloor Street West, inside the Manulife Centre. Drop us a line, give us a call, or just stop by."

## SEO Strategy (Kristine — Tier 2)

### Primary Keyword Targets
1. hair salon Yorkville Toronto ← anchor keyword
2. salon spa Bloor Street Toronto
3. hair colour Toronto Yorkville
4. Bloor Street hair salon
5. Toronto hair extensions salon
6. facial spa Yorkville
7. waxing salon Toronto Yorkville
8. established hair salon Toronto
9. hair salon Manulife Centre
10. luxury salon Toronto Bloor

### Avoid
- "Toronto hair salon" (owned by Yelp/Groupon/directories)
- "best hair salon Toronto" (owned by editorial lists)
- "hair salon near me"
- "Toronto balayage" (major chains dominate)

### Per-Page SEO Summary
| Page | Title Tag | Primary Keyword |
|------|-----------|-----------------|
| Home | Hair Salon Yorkville Toronto \| Concepts Salon Spa | hair salon Yorkville Toronto |
| About | About Concepts Salon Spa \| Toronto Since 1982 | established hair salon Toronto |
| Services | Hair, Colour & Spa Services \| Concepts Salon Spa | hair colour Toronto Yorkville |
| Gallery | Gallery \| Concepts Salon Spa Toronto | Toronto hair salon results |
| Contact | Contact & Book \| Concepts Salon Spa Toronto | book hair salon Yorkville Toronto |

### Local SEO
- NAP must be identical everywhere: "Concepts Salon Spa / 60 Bloor Street West, Toronto, ON / [phone]"
- Claim + fully verify Google Business Profile
- GBP categories: Hair Salon (primary), Day Spa (secondary)
- Upload 10+ photos to GBP; write description with "Yorkville," "Bloor Street," "since 1982"
- Citation targets: Yelp Canada, Yellow Pages, Foursquare, Apple Maps, Bing Places, Facebook, booking platform listing, Manulife Centre directory

## Business Notes (Beth)
- $700 is underpriced for 8-page WordPress redesign + full site audit + plugin remediation. If quote not yet sent, push to $950+HST. If already quoted, hold but go in eyes open.
- 50/50 deposit split is correct.
- Do NOT hand over login credentials or push live until Invoice 2 is paid.
- **M1 Payment Record (2026-06-24):** Edward paid $237.20 by cheque against an M1 invoice of $237.30. Shortfall of $0.10. Payment accepted in full for M1 purposes — the $0.10 has been rolled into M2, bringing M2 from $316.40 to $316.50. No further action needed for M1, but note that Edward underpaid slightly on the first cheque.
- **Key contract clauses needed:**
  - Scope list (8 pages by name)
  - Existing site condition acknowledgement (3 hrs unexpected remediation included; beyond = change order)
  - Client responsible for photography/assets by agreed date
  - Client must confirm booking platform within 5 business days of kickoff
  - Third-party plugin liability disclaimer
  - 2 included revision rounds; additional = hourly
- **Maintenance retainer pitch at launch:** Light Maintenance $160/month + HST (WordPress updates, seasonal menu updates, booking integrations). 12 months = $1,920 CAD.

### Recurring Revenue Strategy (Beth, 2026-06-17)
- **Scope creep handling:** Absorb the migration/hosting hours (relationship investment — early days with a 44-yr Yorkville client). "Transparent absorption" — mention it at M2 handoff (explain the site had to be rebuilt fresh on modern hosting, that it added unplanned hours absorbed on Makepeace's end). Sets up the Care Plan pitch + signals no unlimited free work. Lock the "3 hrs remediation included, beyond = change order" clause into the standard contract going forward.
- **Pricing lesson:** This was Tier 2 work ($1,250) quoted at $700 — undercharged ~$550 before migration hours. Future: add $150–300 "legacy site remediation" buffer for clients on old/unknown backends.
- **Hosting:** Keep Hostinger account under Matt's name (leverage + recurring revenue). Don't transfer to client. Disclose in writing that site is hosted on Makepeace's account with client's domain pointed at it.
- **RECOMMENDED OFFER — bundled "Website Care Plan": $185/month + HST ($209.05/mo total)** = Hostinger Business hosting (~$20 cost) + Light Maintenance ($160) + small bundle margin. Covers monthly WP/plugin updates, SSL monitoring, 1 content update/month, priority support.
- **Pitch timing:** At Milestone 3 invoice (LAUNCH) — never during the build. Frame as "Website Care Plan — so your site stays current, secure, always working for your clients" (reliability language, not "maintenance").
- **12-month value if Care Plan lands:** Project $791 + $2,508.60 maintenance = **$3,299.60 Year 1.** Recovers the underprice within 3–4 months. Established business = low churn → years 2–3 near-pure recurring revenue.

## Hosting & Build Decision (2026-06-17)
- **DECISION: Build fresh on Hostinger — NOT migrating the old site.**
- **Why:** Old Bell site is WP 5.2.21 w/ broken plugins that won't run on PHP 8 (Hostinger only offers PHP 8.2+, no PHP 7). Migration attempts (All-in-One WP Migration) repeatedly failed: broken SSL on Bell blocked plugin installs, 2GB+ export (1,724 UpdraftPlus backups = 5.2GB bloat — cleared), import stalled at 0% on PHP 7→8 mismatch. Site is being redesigned anyway; content already gathered by Jack.
- **New host:** Hostinger **Business Web Hosting** plan (PHP 8.3, WP 7.0)
- **Temp build URL:** `sienna-meerkat-802382.hostingersite.com` (build the redesign here)
- **Old Bell site:** stays LIVE & untouched serving conceptstoronto.com until launch
- **Launch:** point conceptstoronto.com nameservers/DNS to Hostinger (needs Edward/Sussan — domain managed via Internet Names For Business / meganameservers.com). Free SSL auto-activates on Hostinger.
- **Account note:** Hostinger set up under Matthew's account for now — decide w/ Beth whether to bill client or transfer ownership at launch.

## Build Notes (fresh build on Hostinger)
- Page builder: Elementor (Matt exploring; sticky anchor nav for Services page via Menu Anchor + Sticky)
- Bring content from Jack's scrape (services/pricing, brands) — recreate in new design, don't migrate
- Replace Contact Form 7 with WPForms Lite or Fluent Forms
- Gallery: FooGallery or Envira Gallery for masonry + filter tabs
- Booking: "Book Now" button with URL placeholder — swap once platform confirmed
- Instagram feed: static grid cleaner than Meta API
- SEO plugin: RankMath
- No COVID section, no e-commerce delivery promo — fresh start avoids all old cruft

## Status
- [ ] Quote sent / confirmed with client?
- [ ] Deposit invoiced?
- [ ] Booking platform confirmed?
- [ ] Photography situation confirmed?
- [ ] WordPress backend access obtained?
- [ ] Staging site created?
