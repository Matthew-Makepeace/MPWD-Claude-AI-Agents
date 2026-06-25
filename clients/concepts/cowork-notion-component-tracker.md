# Cowork → Notion Prompt — Concepts Figma Component Build Tracker
*(Paste into Claude Cowork)*

---

I'm Matthew Makepeace (Makepeace Web Design). I'm designing the **Concepts Salon Spa** website — a web redesign being built fresh in **Figma**, then in **WordPress + Elementor** on Hostinger. I've finished the design-system component analysis from my wireframes. I need you to **set this up in Notion as a trackable component build board** so I can check off each component as I build it.

## Context (read for full detail)
- Full project profile: `clients/concepts/concepts-client-profile.md`
- Component build plan: `C:\Users\Matth\.claude\plans\silvia-are-you-up-peaceful-snail.md`
- Client: Concepts Salon Spa, est. 1982, 60 Bloor St West Toronto (Bloor-Yorkville). Contacts: Sussan Soares (manager), Edward (owner).
- 5 pages: Home, Services, About, Brands, Contact (+ "Shop" = external store link in nav, no Shop page).
- **Design system LOCKED** — Palette: `#503123` espresso, `#b79a8d` rose-taupe, `#C9A96E` antique-gold, `#D4A5A0` dusty-blush, `#f6e6e4` cream, `#6f675b` warm-taupe. Fonts: Josefin Sans (headings), Montserrat (body).

## What to create in Notion
A database called **"Concepts Salon Spa — Figma Component Build"**, default view grouped by **Phase** (so I build top-down).

**Properties:**
- **Component** (title)
- **Phase** (select): Foundations / Atoms / Molecules / Organisms / Page Templates
- **Status** (select): Not started / In progress / Done — default all to "Not started"
- **Type** (select): Style / Component / Template
- **Variants & states** (text)
- **Used on** (multi-select): Home / Services / About / Brands / Contact / Global
- **Notes** (text)

**Populate these rows:**

### Foundations (Type: Style)
- Color styles (6: espresso, rose-taupe, antique-gold, dusty-blush, cream, warm-taupe) — Global
- Text styles (~9: heading-display, h2, h3, eyebrow, body, body-sm, label, button, nav, price) — Global
- Spacing scale (4/8/12/16/24/32/48/64/96/128) — Global
- Grid (desktop 12-col 1280max; mobile 4-col) — Global
- Image ratios (gallery 1:1, service 4:3, Our Salon 3:4, brand circle 1:1, CTA 16:9) — Global

### Atoms (Type: Component)
- Button — primary (espresso fill/cream text, hover gold), secondary (outlined espresso, fills on hover), ghost; states default/hover/disabled/focus — Global
- Section eyebrow + heading block — center/left — Global
- Divider — solid (rose-taupe) + dashed — Global
- Social icon button — 3 networks — Global (footer + contact)
- Contact info row — icon + text — Global (footer + contact) [SHARED]
- Hours row — day + time — Global (footer + contact) [SHARED]
- Form input field — text + textarea variants; default/focus/filled/error/disabled; half-width capable — Contact
- Price list row — dotted leader, gold price figure — Services
- FAQ accordion row — collapsed (+) / expanded (×) — Services, About
- Brand logo circle — 1:1, hover ring — Brands
- Why-Concepts pillar item — filled/solid icon + label, gold on hover — About
- Stat item — figure + label — Home

### Molecules (Type: Component)
- Service card — image 4:3 + label, hover — Home
- Gallery tile — 1:1, hover — Home
- Testimonial card — quote + name (+ optional stars) — Home
- Filter tab + filter tab bar — active/inactive, gold underline — Services
- Accordion group — rows + heading — Services, About
- Inline CTA box — "Not Sure Where to Start?" — Services
- Brand category section — heading + logo grid + label + dashed divider — Brands
- Footer sub-sections — logo block, nav column — Global
- Stat row — 3 stat items — Home

### Organisms (Type: Component)
- Header / Nav bar — 5 items + Book Now; default/scrolled; mobile burger + drawer — Global
- Footer — assembled — Global
- Feature block (2-col) — image L/R + copy — Home, About
- Service card grid — 6 cards + heading + CTA — Home
- Gallery grid — 8 tiles (2×4) — Home
- Testimonial row/carousel — 4 cards — Home
- CTA strip / banner — image + overlay + button — Home (+ Services)
- Brand trust strip — logo row beneath hero — Home
- Hero — eyebrow + display heading + subhead + 2 buttons + stat row + bg — Home
- Price list group — category + stacked rows — Services
- Contact form — 2-col top row + stacked fields + Send Request; themed to WPForms — Contact
- Map block — static image + "Get Directions" link — Contact

### Page Templates (Type: Template)
- Home, Services, About, Brands, Contact — assemble from organisms

## Add these as callout blocks on the page

**🔒 Locked decisions:**
- Secondary button = outlined espresso (fills on hover)
- Icons = filled/solid (espresso, gold on hover)
- "Shop" = external store link in nav (no Shop page to build)
- Palette + fonts (above)

**⚠️ Watch-items / open decisions:**
- CTA button gold-hover contrast (WCAG check on button text size)
- Testimonial star ratings (recommended add for a trust-based brand)
- Gallery lightbox vs static grid
- blush/rose-taupe adjacency rule (Services CTA box + testimonial bg)
- Hero stat numbers ("100 ###" placeholders) — need real figures (client/Aurther)
- Contact map: static image + Get Directions (rec) vs live Google Maps embed
- Contact form required fields — client to confirm; built with WPForms
- Confirm external "Shop" store URL with client

## Final instruction
Create the database with the properties + rows above (Status all "Not started"), grouped by Phase. Add the Locked Decisions and Watch-items as callout blocks on the page. If a "Concepts Salon Spa" project page already exists in my Notion, nest this under it / link them.
