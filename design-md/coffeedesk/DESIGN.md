---
version: alpha
name: Coffeedesk-design-analysis
description: >
  A warm, playful e-commerce interface for Coffeedesk (coffeedesk.pl) — Poland's specialty
  coffee & tea store. The system anchors on a clean white canvas warmed by cream utility
  bands, navy ink, and a single high-energy crimson action color, with coral hand-drawn
  illustration accents and saturated photo banners. Brand voltage comes from the
  navy/crimson/coral trio over warm whites — confident and humanist where most coffee
  stores go either rustic-brown or minimal-monochrome. Type voice is all-Inter:
  sentence-case bold headers, UPPERCASE letterspaced navigation and badges, comma-decimal
  złoty pricing. The custom rounded "coffeedesk" wordmark with a coral thumbs-up mark
  anchors the brand.

colors:
  primary: "#b90541"
  primary-active: "#9c0436"
  primary-disabled: "#e7c7d0"
  ink: "#140046"
  body: "#140046"
  body-soft: "#2a2350"
  muted: "#667685"
  muted-soft: "#979797"
  cloud: "#a1a4b2"
  hairline: "#d1d4df"
  hairline-strong: "#c1c0cc"
  coral: "#ff8594"
  coral-soft: "#ffb3bd"
  mint: "#a6e4e2"
  canvas: "#ffffff"
  surface-cream: "#fff8f0"
  surface-paper: "#faf6f0"
  surface-warmwhite: "#fbf5ee"
  surface-mint: "#a6e4e2"
  surface-dark: "#140046"
  on-primary: "#ffffff"
  on-dark: "#fbf5ee"
  on-dark-soft: "rgba(255,255,255,0.7)"
  success: "#3fae6b"
  warning: "#d4a017"
  error: "#b90541"

typography:
  display-hero:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 44px
    fontWeight: 700
    lineHeight: 1.12
    letterSpacing: -0.4px
  display-h1:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 34px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: 0
  display-h2:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  title-product:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 19px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  lead:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 17px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-md:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  meta:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  caption:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  label:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 10px
    fontWeight: 700
    lineHeight: 1.7
    letterSpacing: 0.3px
    textTransform: uppercase
  nav-link:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 0.5px
    textTransform: uppercase
  eyebrow:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 1.7px
    textTransform: uppercase
  price:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0.6px
  button:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 15px
    fontWeight: 700
    lineHeight: 1
    letterSpacing: 0.6px
    textTransform: uppercase
  wordmark:
    fontFamily: "Baloo 2, Inter, sans-serif"
    fontSize: 30px
    fontWeight: 800
    lineHeight: 1
    letterSpacing: -0.3px

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  ml: 20px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 80px

components:
  promo-strip:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.nav-link}"
    height: 40px
  utility-bar:
    backgroundColor: "{colors.surface-cream}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    height: 40px
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    padding: 16px 0
  header-bar:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    padding: 18px 0
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.xs}"
    padding: 14px 30px
  button-primary-active:
    backgroundColor: "{colors.primary-active}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.xs}"
  button-primary-disabled:
    backgroundColor: "{colors.primary-disabled}"
    textColor: "{colors.muted}"
    rounded: "{rounded.xs}"
  button-cart:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.price}"
    rounded: "{rounded.xs}"
    padding: 11px 18px
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.button}"
  icon-button-round-navy:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.full}"
    size: 48px
  icon-button-round-coral:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 48px
  search-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xs}"
    padding: 12px 18px
    height: 48px
  text-input:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.xs}"
    padding: 13px 16px
    height: 48px
  text-input-focused:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    rounded: "{rounded.xs}"
  checkbox:
    backgroundColor: "{colors.canvas}"
    rounded: 3px
    size: 20px
  hero-carousel:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-hero}"
    padding: 32px 0
  promo-banner-card:
    backgroundColor: "{colors.surface-cream}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
  product-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-product}"
    rounded: 0
    padding: 0
  badge-flag-navy:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label}"
    rounded: "{rounded.xs}"
    padding: 3px 9px
  badge-flag-crimson:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label}"
    rounded: "{rounded.xs}"
    padding: 3px 9px
  monthly-seal:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-primary}"
    accentColor: "{colors.coral}"
    rounded: "{rounded.full}"
    size: 120px
  section-header:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-h1}"
  newsletter-band:
    backgroundColor: "{colors.surface-mint}"
    textColor: "{colors.ink}"
    typography: "{typography.display-h2}"
    padding: 48px 0
  category-shortcut:
    backgroundColor: "{colors.surface-cream}"
    textColor: "{colors.ink}"
    typography: "{typography.title-sm}"
    rounded: "{rounded.full}"
    size: 120px
  feature-icon:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 96px
  faq-accordion-row:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-product}"
    padding: 22px 4px
  cafe-cta-band:
    backgroundColor: "{colors.surface-cream}"
    textColor: "{colors.ink}"
    typography: "{typography.display-h1}"
    padding: 56px 0
  cart-drawer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    width: 400px
  toast:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    accentColor: "{colors.coral}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.sm}"
    padding: 13px 22px
  footer:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark-soft}"
    typography: "{typography.body-md}"
    padding: 64px 0
---

## Overview

Coffeedesk.pl is the warmest, most playful interface in the specialty-coffee retail category. The base atmosphere is a **clean white canvas** warmed by **cream utility bands** (`{colors.surface-cream}` — #fff8f0) — the warmth lives in the chrome (top promo bar, benefit strip, category circles) rather than flooding the whole page, keeping product photography crisp on white. Headlines run an all-**Inter** type system: **sentence-case bold** display headers paired with **UPPERCASE letterspaced** navigation and badges. The combination feels like a friendly, expert shopkeeper — confident and human, never rustic-brown or sterile-minimal.

Brand voltage comes from the **navy + crimson + coral trio**. Navy (`{colors.ink}` — #140046) is the ink: nearly all text, the top promo bar, and the full mega-footer. Crimson (`{colors.primary}` — #b90541) is the single action color — every "add to cart", every price button, every primary CTA. Coral (`{colors.coral}` — #ff8594) is the illustration and sticker accent — hand-drawn benefit icons, badge fills, the brand thumbs-up mark. A calm mint (`{colors.mint}` — #a6e4e2) backs lifestyle photography and the newsletter band.

The system alternates surface modes band-by-band:
1. **White canvas** (`{colors.canvas}`) — default product floor, where photography lives
2. **Cream bands** (`{colors.surface-cream}` / `{colors.surface-paper}`) — utility bar, benefit strip, café CTA, category circles
3. **Navy surfaces** (`{colors.surface-dark}`) — top promo strip, mega-footer, and the cart drawer's accents

The pacing rhythm is white-to-cream-to-navy, with **saturated photo banners** (solid pink / yellow / teal seamless backdrops) providing the page's color bursts.

**Key Characteristics:**
- Warm white canvas warmed by cream chrome bands (`{colors.surface-cream}` — #fff8f0). Photography stays crisp on white; warmth lives in the utility surfaces.
- Crimson primary CTA (`{colors.primary}` — #b90541). Used on every add-to-cart and price button — the one unambiguous "do this / pay this" color.
- All-Inter type: sentence-case **bold** display headers (never a serif), UPPERCASE letterspaced nav + badges, comma-decimal złoty pricing (`58,99 zł`).
- Navy ink (`{colors.ink}` — #140046) as the dominant text + dark-surface color — the promo strip and footer, never gray-black.
- Coral hand-drawn marker illustrations (navy outline + flat coral fill) for benefit icons and the café scene — playful, humanist, never photorealistic or emoji.
- Circular navy "miesiąca / na półce" seals with a coral star and hand-script ring text — a signature sticker device.
- Border radius is tight: `{rounded.xs}` (4px) is the house default on buttons, inputs, badges and product images; `{rounded.full}` for round icon buttons and seals. Cards are largely square-cornered and borderless — whitespace separates.
- Section rhythm `{spacing.section}` (80px); generous card-internal whitespace; centered ~1260px content frame.

## Colors

### Brand & Accent
- **Crimson / Primary** (`{colors.primary}` — #b90541): The single Coffeedesk action color. Every add-to-cart button, every price pill, every primary CTA (KUP TERAZ, ZAPISZ SIĘ), the struck-vs-current price emphasis. The most-used color after navy and white.
- **Crimson Active** (`{colors.primary-active}` — #9c0436): The press / hover-darker variant.
- **Crimson Disabled** (`{colors.primary-disabled}` — #e7c7d0): A desaturated rose disabled state.
- **Coral** (`{colors.coral}` — #ff8594): The illustration + sticker accent. Hand-drawn benefit-icon fills, the brand thumbs-up mark, the seal star, soft highlights. Never used for primary actions.
- **Coral Soft** (`{colors.coral-soft}` — #ffb3bd): A lighter coral wash for doodle accents.
- **Mint** (`{colors.mint}` — #a6e4e2): Backs lifestyle product photography and the newsletter band. The calm counter-tone to crimson.

### Surface
- **Canvas** (`{colors.canvas}` — #ffffff): The default page floor. Clean white keeps product photography crisp.
- **Surface Cream** (`{colors.surface-cream}` — #fff8f0): Top utility bar, benefit strip, café CTA band — the brand's warm chrome tone.
- **Surface Paper** (`{colors.surface-paper}` — #faf6f0): Sticker/banner paper grounds, category-circle fills.
- **Surface Warm-white** (`{colors.surface-warmwhite}` — #fbf5ee): The warm-white text tone used on navy surfaces (echoes the cream chrome).
- **Surface Mint** (`{colors.surface-mint}` — #a6e4e2): The newsletter band and calm photo panels.
- **Surface Dark** (`{colors.surface-dark}` — #140046): The navy used for the top promo strip and the mega-footer. Same hex as ink — the dark surface is the brand's deep navy, not a separate black.
- **Hairline** (`{colors.hairline}` — #d1d4df): The 1px border tone on light surfaces — inputs, section rules, dividers.
- **Hairline Strong** (`{colors.hairline-strong}` — #c1c0cc): A slightly deeper border for emphasized outlines.

### Text
- **Ink** (`{colors.ink}` — #140046): All headlines, nav, product titles, and primary text. Deep navy, never gray-black.
- **Body Soft** (`{colors.body-soft}` — #2a2350): An optional softened navy for long-form running text.
- **Muted** (`{colors.muted}` — #667685): Secondary / supporting text — "Producent:", helper lines, FAQ answers.
- **Muted Soft** (`{colors.muted-soft}` — #979797): Struck-through old prices, fine meta, faint labels.
- **Cloud** (`{colors.cloud}` — #a1a4b2): Disabled text, placeholder hints.
- **On Primary** (`{colors.on-primary}` — #ffffff): Text on crimson buttons and badges.
- **On Dark** (`{colors.on-dark}` — #fbf5ee): Warm-white text on navy surfaces (echoes the cream chrome tone).
- **On Dark Soft** (`{colors.on-dark-soft}` — rgba(255,255,255,0.7)): Footer link text, secondary labels on navy.

### Semantic
- **Success** (`{colors.success}` — #3fae6b): Green "available / in stock" status dots (rare on marketing surfaces).
- **Warning** (`{colors.warning}` — #d4a017): Warning callouts (rare).
- **Error** (`{colors.error}` — #b90541): Validation errors — reuses crimson, the brand's only red.

## Typography

### Font Family
The system runs **Inter** for everything — display headers, navigation, body, prices, badges and captions. **Inter** is the actual site face across five weights (Light → Bold). The custom rounded **"coffeedesk" wordmark** is a separate logotype, substituted here with **Baloo 2** (the closest free rounded match). Fallback stack: `Inter, system-ui, -apple-system, "Segoe UI", Roboto, sans-serif`.

The hierarchy is weight-and-case driven, not family-driven:
- Inter **Bold, sentence case** (negative-to-zero tracking) → hero, h1, h2, product titles
- Inter **Bold, UPPERCASE, letterspaced** → nav, eyebrows, badges, button labels, prices
- Inter **Regular** → body, lead, meta, fine print
- Baloo 2 ExtraBold → the wordmark only

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.display-hero}` | 44px | 700 | 1.12 | -0.4px | Hero promo headline ("Smaki czerwca z Heresy i Trigger") |
| `{typography.display-h1}` | 34px | 700 | 1.15 | 0 | Section heads (Bestsellery, Nowości, Kawiarnie) |
| `{typography.display-h2}` | 24px | 700 | 1.2 | 0 | Sub-section heads, newsletter headline |
| `{typography.title-product}` | 19px | 700 | 1.3 | 0 | Product card titles, FAQ questions |
| `{typography.lead}` | 17px | 400 | 1.55 | 0 | Hero intro / lead paragraph |
| `{typography.body-md}` | 16px | 400 | 1.6 | 0 | Default running-text |
| `{typography.meta}` | 14px | 400 | 1.45 | 0 | "Producent:", helper text, dates — muted |
| `{typography.caption}` | 12px | 400 | 1.4 | 0 | Fine print, copyright |
| `{typography.label}` | 10px | 700 | 1.7 | 0.3px / UPPERCASE | Product flags (NOWOŚĆ, DARMOWA DOSTAWA) |
| `{typography.nav-link}` | 16px | 700 | 1.4 | 0.5px / UPPERCASE | Top-nav menu items |
| `{typography.eyebrow}` | 14px | 700 | 1.4 | 1.7px / UPPERCASE | Section eyebrows (KAWY MIESIĄCA) |
| `{typography.price}` | 16px | 700 | 1.2 | 0.6px | Price labels on crimson |
| `{typography.button}` | 15px | 700 | 1.0 | 0.6px / UPPERCASE | Button labels (KUP TERAZ) |
| `{typography.wordmark}` | 30px | 800 | 1.0 | -0.3px | "coffeedesk" wordmark — Baloo 2 |

### Principles
Display headers are **bold sentence case** — friendly and direct, never a serif and never thin. Navigation, eyebrows, badges and buttons are **UPPERCASE with positive tracking** (0.5–1.7px), which carries the brand's tidy, confident retail voice. Body stays Regular for paragraphs; bold reappears only for product titles and labels.

Prices follow Polish convention — **comma decimal, lowercase `zł` after a space** (`58,99 zł`) — set bold and letterspaced. The legally-required lowest-price line ("Najniższa cena: …") sits small and muted beneath. Discounts pair a struck-through old price (muted-soft) with the crimson current price.

### Note on Font Substitutes
**Inter** is the real site face and is freely available on Google Fonts — no substitution needed for body or headers. For the **wordmark**, the custom rounded original is not public; **Baloo 2** (ExtraBold) is the closest open-source rounded match, with **Quicksand** Bold as a fallback. Replace with the official `coffeedesk-logo.svg` for pixel-accurate brand use.

## Layout

### Spacing System
- **Base unit:** 4px.
- **Tokens:** `{spacing.xxs}` 4 · `{spacing.xs}` 8 · `{spacing.sm}` 12 · `{spacing.md}` 16 · `{spacing.ml}` 20 · `{spacing.lg}` 24 · `{spacing.xl}` 32 · `{spacing.xxl}` 48 · `{spacing.section}` 80.
- **Section padding:** `{spacing.section}` (80px) vertical between major bands.
- **Card internal padding:** product cards rely on whitespace + image, not box padding; banner/feature content uses `{spacing.ml}`–`{spacing.xl}` (20–32px).
- **Newsletter / café bands:** `{spacing.xxl}`–64px internal.

### Grid & Container
- **Max content width:** ~1260px centered inside a 1920 canvas (≈330px side gutters on the real site; use 24px gutters responsively).
- **Header:** logo left · centered search · account/wishlist/cart cluster right. Mega-nav row centered below.
- **Hero:** ~0.8 / 1.2 split — copy (eyebrow + h1 + lead + CTA) left, big photo banner right with round nav arrows overhanging the edges and dots below.
- **Promo banner grid:** 3-up at desktop, 2-up tablet, 1-up mobile.
- **Product rails:** 4-up at desktop, 2-up tablet, 1-up mobile; a section header with title + long hairline rule + "zobacz wszystkie produkty →" link.
- **Benefit strip:** 4-up icons; **category shortcuts:** 4 circles + arrows; **footer:** 3-column link lists.

### Whitespace Philosophy
White canvas + crisp product cut-outs + uniform 80px band rhythm create a tidy, breathable retail pace. Product cards are separated by space, not borders or heavy shadow. Warmth and rhythm come from alternating cream chrome bands and the navy footer — not from filling the body with color.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Body sections, nav, product cards at rest |
| Soft hairline | 1px `{colors.hairline}` border | Inputs, section rules, dividers |
| Card shadow | `0 2px 10px rgba(20,0,70,0.06)` | Banner cards, gentle product elevation |
| Hover lift | `0 8px 24px rgba(20,0,70,0.12)` + ~1–2px rise | Product card / button hover |
| Pop / overlay | `0 12px 40px rgba(20,0,70,0.16)` | Cart drawer, floating overlays |

The elevation philosophy is **whitespace first, shadow subtle, color-block for chrome**. Most depth comes from the white-vs-cream-vs-navy surface contrast and from saturated photo banners. Product cards rest flat and lift gently on hover (shadow + slight image scale). No glassmorphism; the only notable translucency is white-90% overlays on photography and the navy drawer scrim.

### Decorative Depth
- The coral **thumbs-up brand mark** sits in the wordmark lockup; hand-drawn coral marker illustrations (navy outline + flat coral fill) carry the benefit strip and café scene.
- Circular **"miesiąca / na półce" seals** (navy disc, coral star, faint inner ring, hand-script ring text) overlay photo banners.
- Saturated seamless photo backdrops (pink, yellow, teal) supply the page's color bursts behind crisp product cut-outs.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.xs}` | 4px | The house default — buttons, inputs, badges, product images, banner cards |
| `{rounded.sm}` | 6px | Toast, slightly softer panels |
| `{rounded.md}` | 8px | Banner / promo cards |
| `{rounded.pill}` | 9999px | Badge pills, category circles |
| `{rounded.full}` | 9999px / 50% | Round icon buttons (carousel arrows), monthly seals, shortcut circles |

### Photography & Illustrations
Coffeedesk leans on two image registers that coexist:
- **Studio product photography** — bright, warm, high-key cut-outs on solid seamless color (pink / yellow / teal), lots of negative space, editorial and playful.
- **Hand-drawn marker illustration** — navy outline + flat coral fill, loose and friendly (the delivery box-with-legs, the café scene, doodle accents). Minimal, never photorealistic.
Coffee-bag artwork itself is bold and graphic. Testimonial/avatar photography is rare; when used, crop to circles.

## Components

### Chrome

**`promo-strip`** — Full-width navy bar at the very top. 40px tall, `{colors.surface-dark}` background, warm-white centered UPPERCASE message flanked by truck glyphs (e.g. "Darmowa dostawa z kawami od Runty Roaster").

**`utility-bar`** — Cream band beneath the strip. `{colors.surface-cream}`, 40px, left cluster of coral-icon benefit chips (Darmowa dostawa od 199 zł · Błyskawiczna wysyłka · Pakujemy na prezent), right cluster Kontakt + phone. Type `{typography.label}`.

**`header-bar`** — White sticky header: the `coffeedesk` wordmark left, a centered `{component.search-input}`, and a right cluster of stacked icon+label actions (Zaloguj / Ulubione / Koszyk) with a crimson count bubble. 1px hairline base border.

**`top-nav`** — Centered mega-nav row of UPPERCASE links (Marki · Nowości · Kawa · Herbata · Młynki · Zaparzacze · Ekspresy · Akcesoria · Naczynia · Dodatki · Outlet · Poradnik) in `{typography.nav-link}`; crimson text + crimson underline on hover.

### Buttons

**`button-primary`** — The signature crimson CTA. Background `{colors.primary}`, white UPPERCASE `{typography.button}`, padding 14×30, rounded `{rounded.xs}` (4px). Active `button-primary-active` darkens to `{colors.primary-active}`; hover adds a soft lift. Used for KUP TERAZ, ZAPISZ SIĘ, ZOBACZ.

**`button-cart`** — The price-button on product cards: crimson background, white cart glyph + price in `{typography.price}`, padding 11×18, rounded `{rounded.xs}`.

**`button-ghost`** — Transparent UPPERCASE link button in ink, used for "zobacz wszystkie produkty →" and inline section CTAs (arrow in coral).

**`icon-button-round-navy`** — 48px circular navy button for carousel prev/next; hovers to crimson. **`icon-button-round-coral`** — the coral round arrow variant used on category shortcuts.

### Cards & Containers

**`hero-carousel`** — White hero with an ~0.8/1.2 split: eyebrow + h1 + lead + `{component.button-primary}` left; a saturated photo banner right with round nav arrows overhanging the edges and a dot indicator below. Auto-advances.

**`promo-banner-card`** — A 3-up grid of clickable photo banners (Wiosna w filiżance · Nowość na półce · Fellow), `{rounded.md}`, soft card shadow, UPPERCASE label beneath.

**`product-card`** — The workhorse. Borderless white: a square product photo on white with top-left stacked flag badges and a top-right wishlist heart, then a bold `{typography.title-product}` title, muted "Producent:" / "Data palenia:" meta, and a foot row pairing a struck/lowest price with a crimson `{component.button-cart}`. Image scales gently on hover.

**`monthly-seal`** — A 120px circular navy seal overlaying banners — coral star centered, a faint inner ring, and hand-script ring text ("kawy / herbata miesiąca", "nowość / na półce").

**`section-header`** — Title in `{typography.display-h1}` + a long 1px hairline rule stretching to a right-aligned "zobacz wszystkie produkty →" ghost link.

**`newsletter-band`** — A full-width `{colors.surface-mint}` band: a white inset card (headline "Zgarnij 20 zł rabatu i darmową dostawę!", body, e-mail `{component.text-input}` + crimson submit, consent `{component.checkbox}`) beside a full-bleed lifestyle photo.

**`category-shortcut`** — "Na skróty" row: 120px `{colors.surface-cream}` circles holding a centered product cut-out with a label below, flanked by round arrows.

**`feature-icon`** — Benefit strip: a 96px coral circle holding a navy line icon (or the hand-drawn box illustration), with an UPPERCASE title and a muted one-line subline (Darmowa dostawa · Ekspresowa przesyłka · Malujemy rysunki · Pakujemy na prezent).

**`cafe-cta-band`** — A `{colors.surface-cream}` band: large "Kawiarnie Coffeedesk" headline + crimson ZOBACZ button beside coral line-art props.

**`faq-accordion-row`** — Single-open accordion: bold `{typography.title-product}` question + a rotating chevron, revealing a muted `{typography.body-md}` answer, each row on a hairline base border.

### Inputs & Forms

**`search-input`** — Header search: white field, hairline border, `{rounded.xs}`, placeholder "Szukaj…", trailing magnifier glyph. 48px tall.

**`text-input`** — Standard field (newsletter e-mail). White, hairline border, `{rounded.xs}`, 13×16 padding. **`text-input-focused`** thickens / shifts the border to navy.

**`checkbox`** — 20px square, 3px radius, hairline border; consent rows pair it with small `{typography.meta}` copy.

### Tags / Badges

**`badge-flag-navy`** — "Nowość" flag: navy fill, white `{typography.label}`, `{rounded.xs}`, padding 3×9. Sits top-left on product media.

**`badge-flag-crimson`** — "Darmowa dostawa" / "-20%" flag: crimson fill, white `{typography.label}`, same shape. Stacks under the navy flag.

### Overlays & Feedback

**`cart-drawer`** — A 400px white panel sliding from the right over a navy scrim. Header (Koszyk + close), scrollable line items (thumb, title, crimson price, ±qty stepper), and a foot with total + crimson "Przejdź do kasy" block button.

**`toast`** — A centered navy pill at the bottom on add-to-cart ("Dodano do koszyka") with a coral check glyph; `{rounded.sm}`, brief auto-dismiss.

### Footer

**`footer`** — Deep navy footer closing every page. `{colors.surface-dark}` background, warm-white headings + `{colors.on-dark-soft}` links, 3-column link lists (Coffeedesk / Obsługa klienta / Kawiarnie), an "Oferta dla firm" + "Coffeedesk.com (EU) →" + Instagram row, and a tiny UPPERCASE copyright line. The wordmark sits at top in warm-white. The footer never inverts.

## Do's and Don'ts

### Do
- Keep the body floor **white** and let warmth live in the cream chrome bands and navy footer. Product photography needs the white to stay crisp.
- Reserve `{colors.primary}` (crimson) for **actions** — add-to-cart, prices, primary CTAs. It is the one unambiguous "do this / pay this" color.
- Use `{colors.coral}` only for **illustration, badges and the brand mark** — never for primary buttons.
- Set display headers in **bold sentence case** (Inter); set nav, eyebrows, badges and buttons in **UPPERCASE letterspaced** Inter.
- Format prices Polish-style: **`58,99 zł`** (comma decimal, lowercase zł after a space), bold; pair a struck old price with the crimson current price.
- Keep product cards **borderless** — separate with whitespace, lift gently on hover.
- Use the hand-drawn **coral-on-navy marker** illustration style for benefit/feature icons and the café scene.
- Apply `{spacing.section}` (80px) between major bands; keep radii tight at `{rounded.xs}` (4px).

### Don't
- Don't flood the page with color or use rustic browns / sterile grays. The trio is navy + crimson + coral over warm whites.
- Don't use a serif or a thin weight for display headers. Coffeedesk headers are bold Inter.
- Don't paint accent moments coral on buttons, or use crimson decoratively — crimson means action.
- Don't introduce a fourth surface tone (no purple cards, no green sections). White / cream / navy + mint accent is the set.
- Don't use emoji or unicode icon glyphs — personality comes from hand-drawn illustration and sticker badges.
- Don't add hover styling beyond what's encoded — crimson darkens on press, cards lift gently; nothing else.
- Don't over-round. 4px is the default; only icon buttons and seals go fully round.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | Hamburger nav; hero stacks (copy then banner); promo banners 1-up; product rails 1–2-up; category circles scroll; footer 3 cols → 1 |
| Tablet | 768–1024px | Nav tightens / wraps; promo banners 2-up; product rails 2-up; benefit strip 2-up |
| Desktop | 1024–1440px | Full mega-nav; 3-up promo banners; 4-up product rails; 4-up benefit strip |
| Wide | > 1440px | As desktop with more outer gutter; content caps ~1260px |

### Touch Targets
- `{component.button-primary}` / `{component.button-cart}` ≥ 44px tall in practice.
- `{component.icon-button-round-navy}` at 48px.
- `{component.search-input}` / `{component.text-input}` at 48px.
- Entire product card media + title area is tappable.

### Collapsing Strategy
- Mega-nav collapses to a hamburger sheet < 768px; utility bar chips reduce to the essentials.
- Hero's split collapses to single column — eyebrow + h1 + lead + CTA first, photo banner below.
- Product rails and promo grids reduce columns rather than shrinking cards.
- Cart drawer goes near-full-width (max 90vw) on mobile.
- Photo banners keep their seamless backdrop and scale the product cut-out proportionally.

### Image Behavior
- Product photos sit contained on white; never cropped awkwardly — preserve the cut-out negative space.
- Banner photography scales proportionally; seals reflow toward a corner.
- Lifestyle/avatar photos crop to circles where used.

## Iteration Guide

1. Focus on ONE component at a time. Reference its YAML key (`{component.product-card}`, `{component.newsletter-band}`).
2. Variants of a component (`-active`, `-disabled`, `-focused`) live as separate entries under `components:`.
3. Use `{token.refs}` everywhere — never inline hex.
4. Document Default and Active/Pressed states only — skip hover specifics beyond "crimson darkens, card lifts".
5. Display headers stay **bold sentence-case Inter**; nav/badges/buttons stay **UPPERCASE letterspaced Inter**. The case split is the type voice.
6. Navy + crimson + coral over warm whites (plus mint accent) is the palette. Don't add a fourth surface tone.
7. When in doubt about emphasis: bigger/bolder Inter and more whitespace before adding color.

## Known Gaps

- The custom rounded **"coffeedesk" wordmark** and **coral thumbs-up mark** are brand assets, not public web fonts; the wordmark is substituted with **Baloo 2** here. Treat the logo as an asset to drop in (`assets/logo/coffeedesk-logo.svg`).
- **UI line icons** (user, heart, cart, search, mail, phone, chevrons) use a Lucide-style inline-SVG stand-in matched to the site's thin rounded stroke; swap for the site's own SVGs if available.
- Three of the four **hand-drawn benefit illustrations** (24H stopwatch, painting cat, gift box) and the **"Kawiarnie Coffeedesk" café scene** were not present in the source export — only the delivery box-with-legs illustration (`assets/icon-darmowa-dostawa.png`) is included; the rest are represented with coral line-icon placeholders.
- **Animation / transition timings** (hero auto-advance cadence, drawer slide, toast dismiss) are encoded loosely in the UI kit but not formalized as tokens here.
- Form **validation states** beyond focus (inline error / success) are not extracted — they'd need a checkout or sign-up flow to confirm.
- The **checkout / account / category-listing** surfaces and the physical-café and B2B pages share these tokens but add components (filters, cart summary, order steps) that are out of scope for this homepage-focused document.
- Product copy, prices and roast dates are realistic samples, not a live catalog.
