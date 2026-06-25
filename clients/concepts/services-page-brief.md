# Concepts Salon Spa — Services Page Build Brief
*(Paste this into Claude Cowork to build the Services page)*

## Goal
Build a Services page for Concepts Salon Spa — a full-service hair and beauty salon (est. 1982) at 60 Bloor St West, Toronto (Bloor-Yorkville). The page lists all services in a clean price-list format with a **sticky filter/anchor nav** at the top so users can jump to a category. All service content must stay in the HTML (visually hidden if filtered, never lazy-loaded) so SEO is preserved.

## Design System
**Colours:**
- `#503123` Espresso Brown — CTA buttons, active filter state, footer
- `#b79a8d` Rose Taupe — secondary cards, dividers, inactive filter pills
- `#C9A96E` Antique Gold — price figures, text links, active underline, hover
- `#D4A5A0` Dusty Blush — accent section backgrounds
- `#f6e6e4` Light Blush Cream — page background
- `#6f675b` Warm Taupe — header background

**Type:**
- **Josefin Sans** — headers, category titles (Light/Regular, all-caps for sub-headings, min 18px)
- **Montserrat** — body, service names, prices, buttons (Regular 400 / SemiBold 600)

**Price list format:** `Service Name .......... $price` (dotted leader between name and price; price in gold)

## Filter / Nav Requirement
- Sticky horizontal filter bar at top: `All · Hair · Colour · Spa & Facials · Nails · Waxing · Specialty · Packages`
- Clicking a category filters (or smooth-scroll jumps) to that section
- Active pill = Espresso `#503123` fill / white text; inactive = Rose Taupe `#b79a8d`
- Sticky to top on scroll (`position: sticky; top: 0; z-index: 100`)
- Keep ALL content in the DOM for SEO
- Add a "Book Now" CTA button (Espresso, gold hover) after each category section

## Full Service List & Pricing

### HAIRCUTS
- Women's Cut & Style .......... $70+
- Men's Cut & Style .......... $35+

### STYLE
- Blow Dry .......... $40+
- Roller Set .......... $42+
- Updo .......... $75+

### COLOUR
- Colour Correction .......... $200
- Bleach & Toner .......... $110
- Balayage .......... $140
- Highlights (Full) .......... $150
- Partial Highlights .......... $95

### MANI / PEDI
- Manicure .......... $28
- French Manicure .......... $38
- Shellac Manicure .......... $50
- Shellac French Manicure .......... $58
- Pedicure .......... $55
- French Pedicure .......... $65

### WAXING — FACE
- Eyebrows .......... $22
- Eyebrow Shaping/Tweezing .......... $22
- Upper Lip .......... $16
- Brow & Lip .......... $32
- Chin .......... $15
- Sideburns .......... $19
- Cheek .......... $17
- Full Face .......... $63

### WAXING — BODY
- Bikini .......... $30
- Full Leg .......... $58
- Full Leg & Bikini .......... $120
- Arm .......... $32
- Chest .......... $50
- Back .......... $55

### FACIALS
- Guinot .......... $100–$185
- G.M. Collin .......... $105–$155
- Yon-Ka .......... $105–$145
- Dermalogica .......... $105–$155
- Phytomer .......... $105–$155
- Sothys .......... $105–$155

### SPECIALTY
- Lash Lift .......... $80
- Brow Lamination .......... $50
- Brow Tint .......... $20
- Lash Tint .......... $28
- Brow & Lash Tint .......... $40
- Brow Henna .......... $40

### PACKAGES
- The Gentle Touch (2h 15m) .......... $110
- Athena (2h 15m) .......... $136
- Aphrodite (4h) .......... $209

## Notes
- Pricing sourced from current site (conceptstoronto.com) — CONFIRM with client (Sussan, manager) before launch; some prices may be outdated (e.g. Balayage at $140 is well below Toronto market).
- Services page also needs an FAQs section at the bottom (service-specific questions: consultation included? how long does colour take? come with clean hair?).
- Build mobile-first — filter bar should collapse to a horizontal scroll or dropdown on small screens.
