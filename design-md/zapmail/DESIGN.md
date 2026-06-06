---
version: alpha
name: Zapmail
description: An infrastructure-confident SaaS interface anchored on a bright white canvas with black primary CTAs and a single hot Indigo (#4F39F6) carrying every brand moment. The system reads as engineered-not-decorative — generous whitespace, large-radius cards (~28px), real product dashboard chrome shown in-card, and full-bleed Indigo→lavender gradient hero bands with a soft cloud texture layered over them so screenshots appear to emerge from behind the clouds. Type is Plus Jakarta Sans across five weights — all-caps display claims at the top, polite sentence-case body below. Brand voltage comes from the Indigo gradient and from headline metrics, never from accent decoration.

colors:
  canvas: "#FFFFFF"
  ink: "#010613"
  black: "#000000"
  body: "#616161"
  muted: "#A1A1A1"
  charcoal-800: "#232323"
  charcoal-700: "#333333"
  charcoal-600: "#545454"
  gray-500: "#616161"
  gray-400: "#A1A1A1"
  gray-300: "#C7C7C7"
  border: "#EEEEEE"
  divider: "rgba(0,0,0,0.10)"
  surface-soft: "#FAFAFA"
  surface-tinted: "#F7F7F7"
  surface-card: "#F8F8F9"
  surface-input: "#F4F4F4"
  glass-white-10: "rgba(255,255,255,0.10)"
  glass-white-20: "rgba(255,255,255,0.20)"
  on-dark: "#FFFFFF"
  on-primary: "#FFFFFF"
  indigo: "#4F39F6"
  indigo-700: "#4338CA"
  indigo-500: "#6366F1"
  indigo-soft: "#E0E7FF"
  indigo-bright: "#7529F0"
  violet-400: "#8969F3"
  lavender: "#A5B4FC"
  success: "#19BB7D"
  success-soft: "#8BDF55"
  warn: "#FF9D6B"
  warn-soft: "#FFEDD4"
  danger: "#DF2020"
  info: "#3278B2"

gradients:
  hero: "linear-gradient(180deg, #4F39F6 0%, #6F5DF7 40%, #8C7DF9 70%, #B7B0FB 100%)"
  ai-card: "linear-gradient(180deg, #8C7DF9 0%, #A39CF8 100%)"

typography:
  display:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 115px
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: -0.02em
  h1:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.01em
  h2:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 36px
    fontWeight: 700
    lineHeight: 1.1
  h3:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.2
  h4:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.3
  stat:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 56px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: -0.02em
  lead:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-muted:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 16px
    fontWeight: 300
    lineHeight: 1.5
  small:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.4
  button:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 14px
    fontWeight: 700
    lineHeight: 1.0
  badge:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 11px
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0.06em
  caption:
    fontFamily: "'Plus Jakarta Sans', ui-sans-serif, sans-serif"
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4

rounded:
  sm: 8px
  md: 12px
  lg: 20px
  xl: 28px
  2xl: 40px
  pill: 9999px

spacing:
  space-1: 4px
  space-2: 8px
  space-3: 12px
  space-4: 16px
  space-5: 20px
  space-6: 24px
  space-8: 32px
  space-10: 40px
  space-12: 48px
  space-16: 64px
  space-20: 80px
  space-24: 96px

shadow:
  pill: "0 2px 4px -2px rgba(0,0,0,0.10), 0 4px 6px -1px rgba(0,0,0,0.10)"
  card: "0 1px 4px 0 rgba(9,14,21,0.06), 0 4px 28px 0 rgba(9,14,21,0.06)"
  popover: "0 1px 6px 0 rgba(9,14,21,0.06), 0 2px 32px 0 rgba(9,14,21,0.16)"

components:
  button-primary:
    backgroundColor: "{colors.black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 28px
    shadow: "{shadow.pill}"
  button-primary-active:
    backgroundColor: "{colors.charcoal-800}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    transform: scale(0.98)
  button-indigo:
    backgroundColor: "{colors.indigo}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 28px
    shadow: "{shadow.pill}"
  button-indigo-active:
    backgroundColor: "{colors.indigo-700}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
  button-white:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.black}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 24px
    shadow: "{shadow.card}"
  button-outline:
    backgroundColor: transparent
    textColor: "{colors.black}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 14px 28px
    border: 1.5px solid "{colors.black}"
  button-ghost:
    backgroundColor: "{colors.glass-white-10}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 8px 20px
    backdropFilter: blur(16px)
  button-buy:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.black}"
    typography: "{typography.button}"
    fontWeight: 600
    rounded: "{rounded.pill}"
    padding: 12px 18px
  badge-popular:
    backgroundColor: "{colors.warn}"
    textColor: "{colors.on-dark}"
    typography: "{typography.badge}"
    rounded: "{rounded.pill}"
    padding: 6px 12px
  badge-free:
    backgroundColor: "{colors.warn-soft}"
    textColor: "#7a3a13"
    typography: "{typography.badge}"
    rounded: "{rounded.pill}"
    padding: 6px 12px
  badge-admin:
    backgroundColor: "{colors.surface-tinted}"
    textColor: "{colors.charcoal-800}"
    typography: "{typography.badge}"
    rounded: "{rounded.pill}"
    padding: 6px 12px
    border: 1px solid "{colors.border}"
  badge-prewarm:
    backgroundColor: "{colors.indigo-soft}"
    textColor: "{colors.indigo-700}"
    rounded: "{rounded.pill}"
    padding: 8px 14px
    fontSize: 13px
  count-badge:
    backgroundColor: "{colors.danger}"
    textColor: "{colors.surface-soft}"
    typography: "{typography.badge}"
    rounded: 9px
    padding: 0 5px
  faq-row:
    backgroundColor: "{colors.surface-tinted}"
    textColor: "{colors.black}"
    typography: "{typography.h4}"
    rounded: "{rounded.lg}"
    padding: 18px 22px
  faq-row-open:
    backgroundColor: "{colors.surface-tinted}"
    textColor: "{colors.black}"
    rounded: "{rounded.lg}"
    padding: 20px 22px
  text-input:
    backgroundColor: "{colors.surface-input}"
    textColor: "{colors.charcoal-700}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 16px 18px
    height: 56px
  text-input-focused:
    backgroundColor: "{colors.surface-input}"
    textColor: "{colors.charcoal-700}"
    rounded: "{rounded.md}"
    border: 1px solid "{colors.ink}"
  text-input-search:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.charcoal-700}"
    rounded: "{rounded.md}"
    shadow: "{shadow.card}"
    padding: 16px 18px
  pricing-tier-card:
    backgroundColor: "{colors.surface-tinted}"
    textColor: "{colors.black}"
    titleTypography: "{typography.h3}"
    bodyTypography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 26px 24px
  pricing-tier-card-featured:
    backgroundColor: "{colors.indigo-700}"
    textColor: "{colors.on-dark}"
    titleTypography: "{typography.h3}"
    bodyTypography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 26px 24px
---

## Overview

Zapmail's marketing surface is an infrastructure-confident modern-SaaS interface — bright white canvas (`{colors.canvas}` — #ffffff) with black primary CTAs (`{colors.primary}` — #000000), Plus Jakarta Sans across five weights, and `{colors.surface-tinted}` (#f7f7f7) light-gray cards holding real product dashboard fragments. The system reads as engineered-not-decorative — every band states a capability and proves it with a metric or a screenshot, never with ornament.

A single hot **Indigo** (`{colors.indigo}` — #4F39F6) carries every brand moment: the full-bleed hero gradient, the featured pricing tier, in-card links, and the brand logo. There is no competing accent — the Indigo does all the brand work, and a small semantic set (success green, warm peach, danger red) only ever appears inside product chrome. The brand never softens the Indigo into a generic blue-purple "AI gradient"; it is used flat and confident.

Type voice splits by case, not by family: a single typeface (Plus Jakarta Sans) carries an **all-caps display claim** at the top of the page (`{typography.display}` — 115px / weight 800 / negative tracking, "EMAIL INFRA / AT SCALE") and **polite sentence-case body** everywhere below. Component voltage comes from **product UI fragments shown directly inside cards** — the warmup-duration table, the domain list, the DNS-records panel — and from **headline metrics** (`1M+`, `330k+`, `5 mins`, `4.5★`) rendered large over quiet gray labels.

Unlike the dark-footer convention, Zapmail keeps its footer **white** and closes the page with a giant outline-thin "Zapmail" wordmark. The only dark surface on a light page is the featured pricing tier, which flips to `{colors.indigo-700}`.

**Key Characteristics:**
- White canvas with black primary CTA (`{colors.primary}` — #000000). Buttons are fully `{rounded.pill}` with confident weight-700 labels — never blue, never indigo for the top-level action.
- Single brand color: `{colors.indigo}` (#4F39F6) powers the hero gradient, the featured pricing tier, in-card links, and the logo. Used flat — never as a soft AI-gradient trope.
- All-caps `{typography.display}` hero claims (115px / weight 800 / -2px tracking) over the Indigo gradient; everything else is sentence-case Plus Jakarta Sans.
- Light-gray card surfaces (`{colors.surface-tinted}` — #f7f7f7) for feature cards, FAQ rows, and pricing tiers (non-featured). The featured pricing tier flips to `{colors.indigo-700}` (the only dark card on light pages).
- Real product dashboard chrome embedded directly in cards — Zapmail shows the actual warmup table, domain manager, and DNS panel inside its marketing cards rather than illustrating around them.
- The cloud-over-gradient hero is the signature motif. Product screenshots dissolve into white at the bottom via an alpha mask, appearing to emerge from behind the clouds.
- Glass nav pills (`{component.nav-pill}`) — `{colors.glass-fill}` + `backdrop-filter: blur(16px)` — sit over the hero. The translucent-chrome-over-imagery treatment is one of the system's signature interactive components.
- Avatars are circular (`{rounded.full}`), 40px diameter, used in testimonial rows — the only place where chromatic pastels appear.
- Numbers as headline material: stats render in `{typography.stat}` (56px / 700) over a `{colors.muted}` label, and are the visual hero of the "Trusted by thousands" band.
- Spacing rhythm is `{spacing.section}` (96px) to `{spacing.section-lg}` (120px) between major bands — generous enough to read as engineered-not-cramped.
- Border radius is large and hierarchical: `{rounded.md}` (12px) for inputs, `{rounded.lg}` (20px) for FAQ rows + testimonial cards, `{rounded.xl}` (28px) for content + pricing cards + the hero device, `{rounded.xxl}` (40px) for the hero shell, `{rounded.pill}` for buttons + nav pills + badges, `{rounded.full}` for avatars.

## Colors

### Brand & Accent
- **Indigo** (`{colors.indigo}` — #4f39f6): The single brand color. Powers the hero gradient base, in-card links, the logo, and brand-action buttons. Press state on indigo buttons shifts to `{colors.indigo-700}`.
- **Indigo 700** (`{colors.indigo-700}` — #4338ca): The featured pricing tier surface — the only "dark card" tone on a light page — and the pressed state of indigo buttons.
- **Indigo 500** (`{colors.indigo-500}` — #6366f1): Lighter accent for inline links inside cards.
- **Indigo Soft** (`{colors.indigo-soft}` — #e0e7ff): Tinted background for the "Pre-warmed" pill and AI-mock chips.
- **Indigo Bright** (`{colors.indigo-bright}` — #7529f0): The floating Intercom messenger button.
- **Violet 400 / Lavender** (`{colors.violet-400}` — #8969f3 / `{colors.lavender}` — #a5b4fc): Mid and low stops of the hero gradient and the AI-card band. These appear only inside gradients — never as flat fills on CTAs.

### Surface
- **Canvas** (`{colors.canvas}` — #ffffff): The default page floor. Most of the page is white.
- **Surface Soft** (`{colors.surface-soft}` — #fafafa): Barely-tinted panels and very-soft section dividers.
- **Surface Tinted** (`{colors.surface-tinted}` — #f7f7f7): Feature cards, FAQ rows, inactive pricing tiers, toggle backgrounds — the workhorse light-gray.
- **Surface Card** (`{colors.surface-card}` — #f8f8f9): Testimonial and integration wrappers; default avatar fills.
- **Surface Input** (`{colors.surface-input}` — #f4f4f4): Form field fills (login email / password).
- **Surface Strong** (`{colors.surface-strong}` — #e5e5e5): Disabled button background; strong hairline alternative.
- **Glass Fill** (`{colors.glass-fill}` — rgba(255,255,255,0.10)): Nav pills and ghost buttons over the hero, paired with `blur(16px)`. Brightens to `{colors.glass-fill-hover}` on hover.
- **Hairline** (`{colors.hairline}` — #eeeeee): The 1px border tone on light surfaces — used sparingly, mostly on the dashboard device frame.
- **Hairline Soft / Divider** (`{colors.hairline-soft}` — #f3f3f3 / `{colors.divider}` — rgba(0,0,0,0.10)): The footer rule and pricing-list separators.

### Text
- **Ink** (`{colors.ink}` — #010613): Deep body text; the near-black tone for running copy in tinted contexts.
- **Primary / Black** (`{colors.primary}` — #000000): All headlines and the primary action surface.
- **Charcoal 800 / 700 / 600** (`{colors.charcoal-800}` … `{colors.charcoal-600}`): Secondary headings and strong body in tinted contexts.
- **Body** (`{colors.body}` — #616161): Default running-text color.
- **Muted** (`{colors.muted}` — #a1a1a1): Stat labels, footer links, captions — usually paired with weight 300.
- **Muted Soft** (`{colors.muted-soft}` — #c7c7c7): Tertiary text and the footer wordmark stroke.
- **On Primary / On Indigo** (`{colors.on-primary}` / `{colors.on-indigo}` — #ffffff): Text on black buttons and over the Indigo gradient.
- **On Indigo Soft** (`{colors.on-indigo-soft}` — rgba(255,255,255,0.85)): Muted white for sub-copy over the gradient.

### Semantic
- **Success** (`{colors.success}` — #19bb7d): The Wallet Balance amount and the TrustPilot star; confirmation states in product UI.
- **Warning** (`{colors.warning}` — #ff9d6b): The "POPULAR" badge fill; `{colors.warning-soft}` (#ffedd4) for soft bands and "2 months free" flags.
- **Error** (`{colors.error}` — #df2020): Notification count dot.
- **Info** (`{colors.info}` — #3278b2): Microsoft 365 accent.
- **Integrate Orange** (`{colors.integrate-orange}` — #ff7a30): The "50+ more" integrations link and flame icons.

## Typography

### Font Family
The system runs **Plus Jakarta Sans** for everything — display, headings, body, UI chrome, and captions. There is no second typeface. Five weights see real use: Light (300), Regular (400), Medium (500), SemiBold (600), Bold (700) — plus Extrabold (800) reserved for the hero display and the logo wordmark. The fallback stack walks `ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif`.

The split is functional and case-based, not family-based:
- Display (ALL CAPS, weight 800, -2px tracking) — the single hero claim, split across two stacked lines
- Headings (sentence case, weight 700, slight negative tracking) — section heads, card titles
- Body + UI (sentence case, weight 300–500, 0 tracking) — paragraphs, labels, buttons, nav

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.display}` | 115px | 800 | 0.95 | -2px | Hero claim, ALL CAPS ("EMAIL INFRA / AT SCALE") |
| `{typography.display-lg}` | 48px | 700 | 1.05 | -0.5px | Section heads ("Flexible pricing plans") |
| `{typography.display-md}` | 36px | 700 | 1.1 | -0.4px | In-card heads ("Skip the Warmup.") |
| `{typography.stat}` | 56px | 700 | 1.0 | -1px | Marketing metric numbers |
| `{typography.title-lg}` | 24px | 700 | 1.2 | 0 | Card titles, pricing plan names |
| `{typography.title-md}` | 20px | 600 | 1.3 | 0 | FAQ questions, AI-card titles |
| `{typography.title-sm}` | 16px | 600 | 1.4 | 0 | Small card titles, footer column heads |
| `{typography.lead}` | 18px | 400 | 1.55 | 0 | Sub-heads, FAQ answers |
| `{typography.body-md}` | 16px | 400 | 1.5 | 0 | Default running-text |
| `{typography.body-muted}` | 16px | 300 | 1.5 | 0 | Muted copy under stats, footer contact |
| `{typography.body-sm}` | 14px | 500 | 1.5 | 0 | Nav-pill labels, table cells |
| `{typography.caption}` | 12px | 400 | 1.4 | 0 | Metadata, fine-print |
| `{typography.button}` | 14px | 700 | 1.0 | 0 | Button labels |
| `{typography.nav-link}` | 14px | 500 | 1.4 | 0 | Top-nav menu items |
| `{typography.badge}` | 11px | 700 | 1.0 | 0.06em | Badge labels (UPPERCASE) |

### Principles
The hero display is the brand voice: ALL CAPS, weight 800, -2px tracking, split across two stacked lines (left-aligned top, right-aligned bottom). Everything below the hero reverts to sentence case. The boundary is by case and weight: never set body copy in 800, never set the hero claim in lowercase.

The Light weight (300) is not optional — it is the dominant weight by raw count, carrying muted copy under stats and in the footer. Skipping it reads as off-brand. Body never goes above weight 400 except the small 14px UI label, which uses 500. Headlines never go below 700; display jumps to 800. Numbers always present larger and bolder than their labels.

### Note on Font Substitutes
Plus Jakarta Sans is a free Google Font and is the canonical face — load all of 300/400/500/600/700/800. If unavailable, the nearest substitute is **Lexend** at matching weights, which preserves the slightly-rounded geometric character and the negative display tracking. **Manrope** at weight 700/800 is another close alternative. Do not substitute Inter — its humanist metrics flatten the brand's display character.

## Layout

### Spacing System
- **Base unit:** 4px.
- **Tokens:** `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.huge}` 64px · `{spacing.section}` 96px · `{spacing.section-lg}` 120px.
- **Section padding:** `{spacing.section}` (96px) to `{spacing.section-lg}` (120px) — the vertical rhythm between editorial bands.
- **Card internal padding:** `{spacing.xl}` (32px) for feature and pricing cards; `{spacing.lg}` (24px) for testimonial and AI cards.
- **Gutters:** `{spacing.lg}` (24px) between cards in feature grids; `{spacing.xs}`–`{spacing.sm}` between FAQ rows.

### Grid & Container
- **Max content width:** ~1216px centered on a 1280–1920 canvas.
- **Editorial body:** Hero band is left-aligned within the wrapper; the dashboard device centers below at max-width 1100px.
- **Feature blocks:** 2-up content blocks alternating text/image; the "Built for Scale" sub-grid is 2-up with one full-width span card.
- **Pricing grid:** 3-up at desktop, 2-up at tablet, 1-up at mobile.
- **Testimonials:** 3-up over the Indigo wall.
- **FAQ:** 2-column — a sticky side column (heading + Contact button) beside a single-column accordion list.
- **Footer:** 4-column link list at desktop, wrapping to 2-up at tablet, 1-up at mobile.

### Whitespace Philosophy
Zapmail breathes. Section rhythm sits at 96–120px, headlines are centered with `text-wrap: balance`, and sub-heads cap at ~700px so lines never run wide. Bands alternate white → tinted → Indigo → white so no two consecutive sections share a surface mode. The result reads as confident-not-shouting.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Body sections, top nav, feature cards, FAQ rows (closed) |
| Soft hairline | 1px `{colors.hairline}` border | Dashboard device frame |
| Card | `{shadow.card}` | Open FAQ rows, white floating cards, search popover |
| Button | `{shadow.button}` | Primary / indigo / white CTAs |
| Popover | `{shadow.popover}` | Floating messenger button, elevated menus |
| Device | `{shadow.device}` via `drop-shadow()` | Hero dashboard frame |
| Featured tier | `{colors.indigo-700}` background, no shadow needed | The featured pricing tier inverts to Indigo — color contrast does the elevation work |

The elevation philosophy is **soft and quiet** — small drop shadows on elevated cards, color-block contrast for emphasis. No heavy shadows, no neumorphism, no glassmorphism — except the deliberate glass nav over the hero.

### Decorative Depth
- The hero dashboard uses a `mask-image` alpha fade at its bottom edge plus a `drop-shadow()` filter (not `box-shadow`) so the dissolving bottom casts no hard shadow line — the screenshot melts into the white below.
- Glass nav pills layer `backdrop-filter: blur(16px)` over the gradient.
- Product UI fragments embedded inside marketing cards carry their own internal shadows from the product chrome — these are not system tokens, they're product chrome shown as content.
- Avatar circles in testimonial sections carry pastel fill colors — a small chromatic flourish without breaking the monochrome brand voice.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.sm}` | 8px | Smallest elements; inline chips, mock cards |
| `{rounded.md}` | 12px | Text inputs, integration chips, DNS chips |
| `{rounded.lg}` | 20px | Notification card, AI cards, FAQ rows, testimonials |
| `{rounded.xl}` | 28px | Content cards, feature cards, pricing tiers, hero device |
| `{rounded.xxl}` | 40px | Hero shell, large device frames |
| `{rounded.pill}` | 9999px | Buttons, nav pills, badges, toggles |
| `{rounded.full}` | 9999px / 50% | Avatars, the floating messenger button |

There is no 4px radius in the system — even the smallest elements round at 8px. The large baseline radius is what makes the brand feel approachable-not-corporate.

### Photography Geometry
Avatar photos use `{rounded.full}` (perfect circles) at 40px. Product screenshots retain native aspect ratios inside `{rounded.xl}` frames. The hero device rounds its top corners at 28px and dissolves (no bottom corners) into the canvas. Imagery is warm and un-desaturated — screenshots keep their Indigo accents; no grain, noise, or duotone.

## Components

### Top Navigation

**`top-nav`** — Transparent bar over the hero, 96px tall, `{colors.on-indigo}` text. Carries the Zapmail logo (lightning-bolt-in-circle glyph + wordmark, white fills) at left, a center cluster of glass nav pills (Features, Pricing, Resources, Tutorials), and a black `{component.button-primary}` ("Login") at right. Menu items in `{typography.nav-link}` (Plus Jakarta 14px / 500).

**`nav-pill`** — Glass menu item: `{colors.glass-fill}` + `backdrop-filter: blur(16px)`, `{rounded.pill}`, 8px × 20px padding, white label. Brightens to `{component.nav-pill-active}` (`{colors.glass-fill-hover}`) on hover. The translucent-pill-over-gradient is one of the system's signature interactive components.

### Buttons

**`button-primary`** — The signature primary CTA. Background `{colors.primary}` (#000000), text `{colors.on-primary}`, type `{typography.button}` (Plus Jakarta 14px / 700), padding 14px × 28px, fully `{rounded.pill}`, shadow `{shadow.button}`. Active state `button-primary-active` shifts to `{colors.primary-active}` (#1a1a1a); press scale 0.98. Used for "Login" and top-level actions — never blue, never indigo.

**`button-indigo`** — Brand-action variant. Background `{colors.indigo}`, same geometry as primary. Pressed/hover deepens to `{colors.indigo-700}` (`button-indigo-active`). Used for "Buy Now" and secondary brand actions, never the top-level nav action.

**`button-white`** — White pill on the hero. Background `{colors.canvas}`, text `{colors.primary}`, `{shadow.card}`. Used for "Get Started" over the gradient.

**`button-ghost`** — Glass button over imagery: `{colors.glass-fill}` + blur(16px), white text, `{rounded.pill}`. Used for "Book a Call" on the hero.

**`button-buy`** — White pill inside pricing cards; full-width, centered label, `{rounded.pill}`.

### Cards & Containers

**`hero-band`** — Full-bleed `{gradient.hero}` with a cloud texture layered over it and 140px top padding. Holds the `{typography.display}` claim, a ~460px sub-line, a trust strip (star row + "Trusted by 50K+"), the CTA pair, and the `{component.hero-device-card}` centered below.

**`hero-device-card`** — The product dashboard screenshot. Background `{colors.canvas}`, top corners `{rounded.xl}` (28px), `{shadow.device}` via `drop-shadow()`. Its bottom is alpha-masked to transparent so it dissolves into the white the hero gradient fades to — the screenshot appears to emerge from behind the clouds. The marquee component of the system.

**`feature-card`** — Used in the "Built for Scale" grid. Background `{colors.surface-tinted}` (#f7f7f7), rounded `{rounded.xl}` (28px), internal padding `{spacing.xl}` (32px). Carries an `{typography.title-lg}` headline and a body description in `{typography.body-md}`, plus an embedded product fragment.

**`product-mockup-card`** — A `{colors.surface-tinted}` frame holding real Zapmail dashboard fragments (warmup table, domain list, DNS panel). Rounded `{rounded.xl}`, `{shadow.card}`, zero padding so the chrome bleeds to the edge. These cards display the product, they don't decorate around it.

**`ai-band`** — The "AI-Powered Workflow Tools" section: a `{gradient.ai-card}` (violet→lavender) panel with cloud overlay, rounded `{rounded.xl}`, 56px padding, holding three white `{component.ai-card}` tiles (Instant Domain Oracle, Smart Mailbox Namer, Persona Snapshots).

**`ai-card`** — White tile inside the AI band. Rounded `{rounded.lg}` (20px), 20px padding, a small product mock at top and an `{typography.title-md}` title below.

**`testimonial-card`** — Used in the customer-quote grid over the Indigo wall. Background `{colors.canvas}`, rounded `{rounded.lg}` (20px), padding `{spacing.lg}` (24px). Top row carries a `{component.avatar-circle}` + name + @handle; below sits the quote in `{typography.body-sm}`.

**`pricing-tier-card`** — Standard tier card. Background `{colors.surface-tinted}`, rounded `{rounded.xl}` (28px), padding `{spacing.xl}` (32px). Carries the plan name in `{typography.title-lg}`, price in 48px/700, a `{component.button-buy}`, and a feature checklist with `{component.check-circle}` markers.

**`pricing-tier-card-featured`** — The featured tier ("Growth / POPULAR"). Background flips to `{colors.indigo-700}` (#4338ca), text inverts to `{colors.on-indigo}`, and check circles invert to white-on-indigo. The dark Indigo surface IS the featured-tier signal — paired with a `{component.badge-popular}` chip.

**`pre-footer-cta`** — "Email Infrastructure That Delivers. Literally." A `{gradient.hero}` card with cloud overlay, rounded `{rounded.xl}`, 64px padding, a white CTA, and a dashboard screenshot anchored to the bottom edge.

### Inputs & Forms

**`text-input`** — Login-style field. Background `{colors.surface-input}` (#f4f4f4), no border, rounded `{rounded.md}` (12px), padding 16px × 18px, height ~56px, placeholder in `{colors.muted}`. Password fields carry a trailing eye toggle; search renders as a white `{shadow.card}` popover variant.

**`text-input-focused`** — Focus state. Border or ring shifts toward `{colors.ink}` for emphasis.

**`provider-toggle`** + **`provider-toggle-active`** — A `{rounded.pill}` `{colors.surface-tinted}` wrapper holding Google Workspace / Microsoft 365 / Pre-warmed segments. The active segment renders as a black pill (`provider-toggle-active`, `{colors.primary}` background, white text). A second identical toggle switches billing cadence and carries a `{colors.warning}` "2 months free" flag above the Yearly option.

### Tags / Badges

**`badge-popular`** — UPPERCASE `{typography.badge}` chip, `{colors.warning}` fill, white text, `{rounded.pill}`, padding 4px × 12px. Marks the featured pricing tier.

**`badge-soft`** — `{colors.warning-soft}` chip for "Get 2 months free" flags.

**`badge-admin`** — In-app neutral pill: `{colors.surface-tinted}` background, charcoal text. For "G ADMIN", mailbox counts.

**`count-badge`** — `{colors.error}` notification dot, white numeral, 9px radius. On the messenger button and nav alerts.

**`check-circle`** — 18px filled circle, `{colors.primary}` (white check), used as the pricing checklist marker. Inverts to white-on-indigo on the featured tier.

**`avatar-circle`** — 40px diameter, rounded `{rounded.full}`. Either holds a photo or a pastel fill (orange / green / blue / violet / pink) with initials in `{typography.caption}`. The only place chromatic pastels appear.

**`rating-stars`** — Inline star rating in `{colors.success}` (#19bb7d). Used near the "4.5 on TrustPilot" stat to display a satisfaction score.

### Tab / Filter

**`provider-toggle`** (cross-referenced) — Zapmail's segmented control plays the role of Cal.com's category tabs: a `{rounded.pill}` wrapper with segments that swap an active black pill on selection. Both the provider switch (Google / Microsoft / Pre-warmed) and the billing-cadence switch (Monthly / Quarterly / Yearly) use this pattern. There is no separate small `{rounded.md}` tab in the system — the pill-segment IS the filter primitive.

### CTA / Footer

**`pre-footer-cta`** (cross-referenced) — The pre-footer Indigo gradient card; see Cards & Containers. It is the page's last bright moment before the white footer.

**`footer`** — White footer (the brand does NOT use a dark footer). Background `{colors.canvas}`, text `{colors.muted}` / weight 300. Four link columns covering Quick Links / Features / Comparison / Support & resources, a contact line, a `{colors.divider}` hairline rule, a social + company row, and a giant outline-thin "Zapmail" wordmark (`-webkit-text-stroke: 1px {colors.muted-soft}` over transparent fill) that closes the page as a graphic. The light footer with the stroked wordmark — not a dark inversion — is the deliberate page-closing move.

## Do's and Don'ts

### Do
- Reserve `{colors.primary}` (#000000) for the top-level primary CTA and headings. Zapmail's primary button is black, not indigo.
- Use `{colors.indigo}` flat for brand moments — the hero gradient, the featured tier, links, the logo.
- Default hero moments to `{gradient.hero}` + the cloud texture overlay, fading to white at the bottom. When a screenshot meets the hero, dissolve its bottom edge with an alpha mask so it appears to emerge from behind the clouds.
- Set the hero claim in ALL CAPS `{typography.display}`, two stacked lines, with -2px tracking.
- Load and use Plus Jakarta Sans weight 300 for muted copy — it is part of the voice.
- Present metrics in `{typography.stat}` — big number, small `{colors.muted}` label. Numbers are headline material.
- Use `{component.feature-card}` (tinted gray) and `{component.product-mockup-card}` (real chrome) deliberately — gray cards signal "abstract capability claim", chrome cards signal "look at the actual product".
- Keep avatar circles at 40px, perfect circles, sometimes with pastel fills. Avatars are the only place where chromatic pastels appear.
- Use `{component.nav-pill}` glass treatment for any UI that sits over the gradient. The translucent-pill-over-imagery is signature.
- Keep radii large (28px cards, pill buttons) and shadows soft (`{shadow.card}` / `{shadow.popover}`).

### Don't
- Don't make the top-level CTA indigo or any color other than black. The system is monochrome at the primary-action layer.
- Don't render the Indigo as a soft blue-purple "AI gradient" trope — it is a flat, confident hot indigo.
- Don't use emoji in marketing copy. The Intercom 👋 is third-party and out of system.
- Don't add a dark footer — Zapmail's footer is white with the outline wordmark. The only dark surface on a light page is the featured pricing tier.
- Don't go below weight 700 on headlines, below weight 800 on the display claim, or below 8px on radii.
- Don't use heavy shadows; never exceed the `{shadow.popover}` tier.
- Don't pad pages with stat-slop — every number must be a real, load-bearing proof point.
- Don't repeat the same surface mode in two consecutive bands; alternate white → tinted → indigo → white.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | Hamburger nav; hero display 115→44px; CTA pair stacks; feature blocks 1-up; pricing 1-up; testimonials 1-up; footer 4 cols → 1 |
| Tablet | 768–1024px | Top nav tightens / pills wrap; feature blocks stay 2-up but narrow; pricing 2-up; stats 2×2 |
| Desktop | 1024–1440px | Full glass nav; alternating 2-up feature blocks; 3-up pricing + testimonials; 4-stat row |
| Wide | > 1440px | Same as desktop; content caps at 1216px and outer gutters absorb the rest |

### Touch Targets
- `{component.button-primary}` ≥ 44px tall (14px × 28px padding clears it).
- `{component.text-input}` height ~56px.
- `{component.nav-pill}` effective tap area ≥ 44px with padding.
- `{component.messenger-button}` at 48px meets WCAG.

### Collapsing Strategy
- Top nav collapses to a hamburger below 768px; the glass pills move into a sheet.
- The hero display scales down aggressively (115→44px) and the two stacked lines may merge to left-aligned.
- The hero dashboard device scales proportionally; the bottom alpha-fade is preserved at every width.
- Feature text/image blocks stack image-below-text on mobile.
- Pricing tiers collapse 3 → 2 → 1; the featured Indigo tier stays visually distinct at every breakpoint.
- The provider/cadence toggles wrap to multi-row on mobile if the segments don't fit horizontally.
- The FAQ two-column layout drops the sticky side column above the accordion on mobile.

### Image Behavior
- Product dashboard fragments inside cards retain native aspect ratios; the cards themselves resize.
- The hero device's bottom alpha-fade scales with the image so the dissolve-into-white reads at every breakpoint.
- Avatar photos crop to circles at every breakpoint.
- The cloud texture overlay re-anchors per band (hero ≈ 0.85 opacity, testimonials ≈ 0.5) and never tiles visibly.

## Iteration Guide

1. Focus on ONE component at a time. Reference its YAML key directly (`{component.feature-card}`, `{component.pricing-tier-card-featured}`).
2. Variants of an existing component (`-active`, `-focused`) live as separate entries in `components:`.
3. Use `{token.refs}` everywhere — never inline hex.
4. Never document hover. Default and Active/Pressed states only.
5. The hero display stays ALL CAPS Plus Jakarta 800 with -2px tracking. Body stays Plus Jakarta 400 (muted copy 300). The case boundary does not blur.
6. The primary CTA is black; brand-action buttons are indigo. The only dark surface on a light page is the featured pricing tier — don't add other dark cards casually.
7. When in doubt about emphasis: bigger number or a real screenshot before more color.

## Known Gaps

- **Logo:** `assets/logo-full.svg` (white-fill glyph + wordmark) is the canonical mark, sourced from the live site. An indigo/black variant for light surfaces is produced via `filter: brightness(0)` rather than a dedicated file.
- **Source fidelity:** the system is reconstructed from a FREE-tier `html.to.design` Figma export (flattened, no component instances) plus screenshot ground-truth. Token values come from raw style-usage counts; the `components:` block is reconstructed, not extracted from a live component library.
- **Cloud texture:** the hero `hero-clouds.png` overlay is a raster asset; its exact blend mode and opacity vary by band and are documented approximately.
- **Iconography:** the system ships no icon font. In-app sidebar icons are thick-stroke rounded line icons; substitute **Lucide** at stroke width 2 and flag it. Pricing checkmarks are filled circles, not Lucide.
- **In-app product surface:** the full dashboard, settings, and mailbox-detail screens are shown only as marketing screenshots — their component specs are out of scope.
- **Animation & transition timings** (warmup chart, slot picker, FAQ expand) are inferred (fade-up 240ms, press 0.98 / 80ms), not extracted.
- **Form validation states** beyond default/focus are not captured — error / success states would need a live sign-up flow to confirm.
- **Testimonial content** in the kit is synthetic; the live wall is screenshot-based, with both photo avatars and pastel-fill initials coexisting on the same page.
