# Dr. R N Sezer & Associates — Service Pages Build Context
# Handoff file for new session — pick up where we left off

---

## Status at Handoff

- Services page (post ID: 25) — all 12 cards updated ✓
- Card 10 updated to Emergency Dentistry ✓
- All 12 service page copy written ✓ (see service-page-copy.md)
- 11 of 12 Unsplash image URLs extracted ✓
- Emergency Dentistry image URL — STILL MISSING (run query below first)
- 0 of 12 service sub-pages built

---

## First Task: Get Emergency Dentistry Image URL

Run this WP CLI db query via WP Vibe on site https://drsezerassociates.ca:

```
db query "SELECT SUBSTRING(meta_value, 41200, 400) FROM {prefix}postmeta WHERE post_id=25 AND meta_key='_elementor_data'"
```

If that doesn't show a photo URL, also try positions 40800, 41600, and 42000.
The URL pattern is: `https://images.unsplash.com/photo-XXXXXXXXXXX?q=80&w=...`

---

## Confirmed Image URLs (11 of 12)

1. **Dental Implants**: `https://images.unsplash.com/photo-1593022356769-11f762e25ed9?q=80&w=1740&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
2. **Porcelain Veneers**: `https://images.unsplash.com/photo-1654373535457-383a0a4d00f9?q=80&w=774&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
3. **Teeth Whitening**: `https://images.unsplash.com/photo-1606811971618-4486d14f3f99?q=80&w=1674&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
4. **Invisalign**: `https://images.unsplash.com/photo-1777793636393-a0fec488f3fb?q=80&w=1548&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
5. **Root Canal Treatment**: `https://images.unsplash.com/photo-1777793389944-f7165259a05c?q=80&w=1548&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
6. **Fillings**: `https://images.unsplash.com/photo-1657470179447-0f5aa16daa91?q=80&w=774&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
7. **Porcelain Crowns**: `https://images.unsplash.com/photo-1675516030465-e2ad117e870f?q=80&w=1740&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
8. **Dentures**: `https://images.unsplash.com/photo-1612283104841-d1918e7666c7?q=80&w=1928&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
9. **Dental Bonding**: `https://images.unsplash.com/photo-1690167687106-180b0ea1d813?q=80&w=830&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
10. **Emergency Dentistry**: MISSING — run query above
11. **Bridges**: `https://images.unsplash.com/photo-1661701422675-c272cdcf8dbf?q=80&w=1740&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`
12. **Pediatric Dentistry**: `https://images.unsplash.com/photo-1631051103633-24959376b92d?q=80&w=930&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D`

---

## WordPress Site Details

- **Live domain**: https://drsezerassociates.ca
- **Services page post ID**: 25
- **WP MCP prefix tool**: `mcp__Dr_R_N_Sezer_Associates_MCP_WP__`
- **WP Vibe prefix tool**: `mcp__Concepts_Salon_-_WP_Vibe_MCP__`
- **Page template to use**: `elementor_header_footer`
- **Post parent for all 12 sub-pages**: 25

---

## Page Layout (Figma-approved)

### Hero Band — light cyan background (#b2e8f1)
- Breadcrumb: Home / Services / [Service Name]
- H1: Service name (Red Hat Display, navy #17468d)
- Right column: Intro paragraph (~60 words)
- Two CTAs: "Book Consultation →" (links to /contact-us) | "See Process" (anchors to #process)

### Two-Column Section Below
**Left sidebar (fixed ~280px):**
- "Our Services" heading
- List of all 12 services as `<a>` links
- Active service highlighted in cyan (#1dc2df)
- "All Services →" button linking to /services

**Right main content:**
1. Large service image (object-fit: cover, full width, ~400px tall) — Unsplash URL from above
2. "What is [Service]?" — 3 paragraphs of body copy
3. "When Should You Get One?" — 4–5 bullet points  
4. "What to Expect" — id="process" — numbered 3-step list (bold title + 1 sentence)

---

## Brand Colors
- `#17468d` — navy (primary headings)
- `#6189c4` — secondary blue
- `#1dc2df` — cyan (active states, accents)
- `#b2e8f1` — light teal/cyan (hero background)
- `#202020` — dark (body text)
- `#929292` — grey
- `#ffffff` — white

## Fonts
- Red Hat Display — headings
- Helvetica — body
- Montserrat 600 — breadcrumbs

---

## The 12 Service Slugs (post_name for URL)

| # | Service | Slug |
|---|---------|------|
| 1 | Dental Implants | dental-implants |
| 2 | Porcelain Veneers | porcelain-veneers |
| 3 | Teeth Whitening (Zoom!) | teeth-whitening |
| 4 | Invisalign | invisalign |
| 5 | Root Canal Treatment | root-canal-treatment |
| 6 | Fillings | fillings |
| 7 | Porcelain Crowns | porcelain-crowns |
| 8 | Dentures | dentures |
| 9 | Dental Bonding | dental-bonding |
| 10 | Emergency Dentistry | emergency-dentistry |
| 11 | Bridges | bridges |
| 12 | Pediatric Dentistry | pediatric-dentistry |

---

## Build Method

Use WP Vibe `POST /wpvibe/v1/elementor/save-page` to inject Elementor JSON.
Build Dental Implants page first as the template, then replicate for remaining 11.

After all pages saved:
- Set `post_parent = 25` via `PUT /wp/v2/pages/<id>` for each
- Run `wp elementor flush-css` and `wp cache flush`

---

## Service Page Copy

All 12 sets of copy are in:
`/home/user/MPWD-Claude-AI-Agents/clients/drsezerassociates/service-page-copy.md`
