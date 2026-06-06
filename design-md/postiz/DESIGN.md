---
version: alpha
name: Postiz
description: A dark, AI-product-first interface anchored on a near-black canvas with saturated jewel-tone card gradients and white pill CTAs. The system reads as a modern open-source automation tool — high contrast, friendly 32px-radius cards, a signature hot-pink accent with hand-drawn squiggle underlines, and product UI screenshots shown directly inside gradient cards. Brand voltage comes from the Plus Jakarta Sans display headline, the rotating violet/magenta/blue card gradients, and the pink scribble motif rather than from a busy palette.

colors:
  canvas: "#0E0E0E"
  surface: "#1A1919"
  surface-2: "#242424"
  surface-3: "#2E2E2E"
  hairline: "rgba(255,255,255,0.10)"
  hairline-strong: "rgba(255,255,255,0.20)"
  ink: "#FFFFFF"
  body: "#D1D1D1"
  muted: "rgba(255,255,255,0.80)"
  muted-soft: "rgba(255,255,255,0.55)"
  on-primary: "#0E0E0E"
  brand-pink: "#FF4CE2"
  brand-pink-soft: "#FC7CFF"
  brand-violet: "#B491FF"
  brand-violet-core: "#7B08D5"
  brand-magenta: "#B611B0"
  brand-blue: "#164CD9"

gradients:
  grad-violet: "linear-gradient(180deg, #7B08D5 0%, #390053 100%)"
  grad-violet-2: "linear-gradient(180deg, #4C27E1 10%, #2F007B 76%)"
  grad-violet-3: "linear-gradient(180deg, #9033ED 0%, #3C0078 100%)"
  grad-indigo: "linear-gradient(180deg, #5608D5 0%, #24005E 100%)"
  grad-blue: "linear-gradient(180deg, #164CD9 4%, #002584 75%)"
  grad-magenta: "linear-gradient(180deg, #B611B0 0%, #4A0047 100%)"
  grad-pink: "linear-gradient(180deg, #DD1499 0%, #7D0069 100%)"
  grad-stat: "linear-gradient(180deg, #9110DF 0%, #4B0086 100%)"
  grad-hero: "linear-gradient(120deg, #8217C3 0%, #4C27E1 50%, #B611B0 100%)"
  scrim-down: "linear-gradient(180deg, #0E0E0E 0%, rgba(14,14,14,0) 100%)"
  scrim-up: "linear-gradient(0deg, #0E0E0E 0%, rgba(14,14,14,0) 100%)"

typography:
  hero:
    fontFamily: "'Plus Jakarta Sans', system-ui, sans-serif"
    fontSize: 70px
    fontWeight: 700
    lineHeight: 77px
    letterSpacing: -0.01em
  display-cta:
    fontFamily: "'Plus Jakarta Sans', system-ui, sans-serif"
    fontSize: 60px
    fontWeight: 700
    lineHeight: 66px
  display:
    fontFamily: "'Plus Jakarta Sans', system-ui, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 53px
  card-title:
    fontFamily: "'Plus Jakarta Sans', system-ui, sans-serif"
    fontSize: 38px
    fontWeight: 700
    lineHeight: 42px
  sub-title:
    fontFamily: "'Plus Jakarta Sans', system-ui, sans-serif"
    fontSize: 34px
    fontWeight: 700
    lineHeight: 37px
  lead:
    fontFamily: "'Inter', system-ui, sans-serif"
    fontSize: 21.5px
    fontWeight: 400
    lineHeight: 29px
  body:
    fontFamily: "'Inter', system-ui, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 24px
  small:
    fontFamily: "'Inter', system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 21px
  caption:
    fontFamily: "'Inter', system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 18px
  button:
    fontFamily: "'Inter', system-ui, sans-serif"
    fontSize: 19px
    fontWeight: 500
    lineHeight: 25px
  button-sm:
    fontFamily: "'Inter', system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 21px
  banner:
    fontFamily: "'Inter', system-ui, sans-serif"
    fontSize: 15.8px
    fontWeight: 400
    lineHeight: 24px

rounded:
  sm: 12px
  md: 20px
  card: 32px
  pill: 9999px

spacing:
  space-1: 4px
  space-2: 8px
  space-3: 12px
  space-4: 16px
  space-5: 24px
  space-6: 32px
  space-7: 40px
  space-8: 64px
  section: 90px

shadow:
  pop: "0 12px 32px rgba(0,0,0,0.45)"
  card: "0 24px 60px -20px rgba(0,0,0,0.7)"
  text: "2px 2px 6px rgba(0,0,0,0.6)"
  glow-violet: "0 0 0 1px rgba(180,145,255,0.45), 0 0 40px rgba(180,145,255,0.25)"

components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 16px 24px 16px 32px
    icon: arrow-right
  button-primary-hover:
    transform: translateY(-1px)
    shadow: "0 10px 28px rgba(255,255,255,0.18)"
  button-primary-active:
    transform: scale(0.985)
  button-primary-sm:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-sm}"
    rounded: "{rounded.pill}"
    padding: 12px 18px 12px 24px
    icon: arrow-right
  button-ghost:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.small}"
    rounded: "{rounded.pill}"
    padding: 12px 24px
    border: 1px solid rgba(255,255,255,0.85)
  button-ghost-hover:
    backgroundColor: "rgba(255,255,255,0.08)"
    border: 1px solid "{colors.ink}"
  announcement-banner:
    backgroundColor: "{colors.brand-pink}"
    textColor: "{colors.ink}"
    typography: "{typography.banner}"
    textShadow: "{shadow.text}"
    padding: 4px 16px
  badge-role:
    backgroundColor: "{colors.brand-violet-core}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    fontWeight: 600
    rounded: "{rounded.pill}"
    padding: 6px 14px
  badge-admin:
    backgroundColor: "{colors.brand-pink}"
    textColor: "{colors.ink}"
    typography: "{typography.caption}"
    fontWeight: 600
    rounded: "{rounded.pill}"
    padding: 6px 14px
  feature-card:
    backgroundColor: "{gradients.grad-violet}"
    textColor: "{colors.ink}"
    descriptionColor: "{colors.muted}"
    titleTypography: "{typography.card-title}"
    bodyTypography: "{typography.caption}"
    rounded: "{rounded.card}"
    shadow: "{shadow.card}"
    padding: 28px
  audience-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    descriptionColor: "{colors.muted}"
    titleTypography: "{typography.card-title}"
    bodyTypography: "{typography.caption}"
    rounded: "{rounded.card}"
    shadow: "{shadow.card}"
    padding: 28px
---

## Overview

Postiz's marketing surface is a dark, high-contrast, AI-product interface — a near-black canvas (`{colors.canvas}` — #0E0E0E) with white pill CTAs (`{colors.primary}` — #FFFFFF), custom-feeling **Plus Jakarta Sans** display typography, and saturated jewel-tone gradient cards (`{gradients.grad-violet}`, `{gradients.grad-magenta}`, `{gradients.grad-blue}`) holding real product UI screenshots. The system reads as a confident open-source automation tool — generous 90px section rhythm, big friendly 32px-radius cards, and a single white primary action per band.

Type voice splits cleanly into two roles: **Plus Jakarta Sans** (the bold geometric display face — used for the hero, h2/h3, and card titles at weight 700) and **Inter** (used for everything else — body, buttons, nav, captions). Display sizes are big and tight (70px hero, 48px section heads) with slight negative tracking — it feels modern, engineered, distinctly Postiz.

Component voltage comes from two places: **jewel-tone gradient cards** that rotate through violet → magenta → blue → pink, and **real product UI screenshots shown directly inside those cards** — scheduling calendars, AI assistant panels, analytics dashboards. Postiz doesn't paint marketing illustrations of the product; it shows the actual dark-UI chrome at small scale embedded in the marketing flow. A signature **hot-pink (`{colors.brand-pink}` — #FF4CE2) hand-drawn squiggle** underlines section headings — the one deliberately human, casual mark against the polished gradients.

Unlike a light-canvas system, Postiz is **dark end-to-end**: the page never flips to white. Contrast and elevation come from the gradient cards glowing against the near-black floor, and the footer steps up only slightly to `{colors.surface}` (#1A1919) to close the page.

**Key Characteristics:**
- Near-black canvas (`{colors.canvas}` — #0E0E0E) with a **white** pill primary CTA (`{colors.ink}` — #FFFFFF). Buttons are `{rounded.pill}` with a trailing → arrow and weight-500 labels. Press state shrinks slightly (scale 0.985).
- Bold `Plus Jakarta Sans` display typeface for headlines (weight 700, slight negative tracking). Inter for all supporting type.
- **Gradient card surfaces** (`{gradients.*}`) for feature, integration, and stat cards — a rotating jewel palette of violet / magenta / blue / pink. The audience and testimonial cards instead use flat `{colors.surface}` (#1A1919) dark fills.
- Real product UI screenshots embedded directly in gradient cards — Postiz shows actual scheduling calendars, AI panels, and analytics dashboards. Brand voltage from real dark-UI chrome at small scale.
- Hot-pink accent (`{colors.brand-pink}` — #FF4CE2): the announcement banner fill, hand-drawn **squiggle underlines** beneath headings, and small highlight strokes. The signature pop against the violet/dark.
- Toggle-pill-group (`{component.toggle-pill-group}`) — a pill-radius wrapper around 2 hero segments ("I need normal scheduling" / "I want AI agents"). The active segment renders as a white pill. One of the system's signature interactive components.
- Social platform chips are full-color brand glyphs in rounded squares (`{rounded.sm}`–`{rounded.md}`), 48–60px, used in the hero row and channels grid.
- Spacing rhythm is `{spacing.section}` (90px) between major bands — generous, modern-SaaS pacing.
- Border radius is large and friendly: `{rounded.sm}` (12px) for inputs/chips, `{rounded.md}` (20px) for stat cards, `{rounded.card}` (32px) for feature cards + hero stage, `{rounded.pill}` for buttons + badges.

## Colors

### Brand & Accent
- **Pink** (`{colors.brand-pink}` — #FF4CE2): The signature accent. The announcement banner fill, hand-drawn squiggle underlines, small highlight strokes. Never used as a button fill.
- **Pink Soft** (`{colors.brand-pink-soft}` — #FC7CFF): Thinner pink glow / secondary squiggle stroke.
- **Violet** (`{colors.brand-violet}` — #B491FF): Purple outline glow on featured/interactive elements; input focus border.
- **Violet Core** (`{colors.brand-violet-core}` — #7B08D5): Core brand violet — role badges, top of the primary card gradient.
- **Magenta** (`{colors.brand-magenta}` — #B611B0): Card gradient anchor.
- **Blue** (`{colors.brand-blue}` — #164CD9): Integration / accent card gradient anchor.

### Gradients (the defining motif)
Cards use **top→bottom linear gradients** in a rotating jewel palette. Pick from `{gradients.*}` — never invent new ones, and never use gradients on full-section backgrounds (they are reserved for cards + the hero stage):
- `{gradients.grad-violet}`, `{gradients.grad-violet-2}`, `{gradients.grad-violet-3}` — purple feature cards.
- `{gradients.grad-blue}` / `{gradients.grad-indigo}` — integration & "design" cards.
- `{gradients.grad-magenta}` / `{gradients.grad-pink}` — accent feature & stat cards.
- `{gradients.grad-stat}` — the trusted-by stat marquee cards.
- `{gradients.grad-hero}` — the 3-stop violet→blue→magenta diagonal behind the hero product mockup.
- `{gradients.scrim-down}` / `{gradients.scrim-up}` — fade-to-canvas scrims used over media edges and under the sticky header.

### Surface
- **Canvas** (`{colors.canvas}` — #0E0E0E): The default page floor — flat near-black, used on every band.
- **Surface** (`{colors.surface}` — #1A1919): Flat dark cards (audience, testimonial), and the footer panel.
- **Surface-2** (`{colors.surface-2}` — #242424): Inner card surface.
- **Surface-3** (`{colors.surface-3}` — #2E2E2E): Inputs, hover surfaces.
- **Hairline** (`{colors.hairline}` — rgba(255,255,255,0.10)): 1px dividers / card borders on dark surfaces.
- **Hairline Strong** (`{colors.hairline-strong}` — rgba(255,255,255,0.20)): Slightly stronger divider.

### Text
- **Ink** (`{colors.ink}` — #FFFFFF): All headlines and primary text.
- **Body** (`{colors.body}` — #D1D1D1): Default running-text color on dark.
- **Muted** (`{colors.muted}` — rgba(255,255,255,0.80)): Secondary text — subtitles, card descriptions.
- **Muted Soft** (`{colors.muted-soft}` — rgba(255,255,255,0.55)): Tertiary text — captions, placeholders, fine-print.
- **On Primary** (`{colors.on-primary}` — #0E0E0E): Near-black text on the white primary button.

### Semantic
- **Success** (`{colors.success}` — #1F8A5B): Confirmation states in product UI.
- **Warning** (`{colors.warning}` — #F5A623): Warning callouts.
- **Error** (`{colors.error}` — #E5484D): Validation errors.

## Typography

### Font Family
The system runs **Plus Jakarta Sans** for display + brand wordmark and **Inter** for everything else. Plus Jakarta Sans is a bold geometric display face — weight 700, slight negative letter-spacing on the largest sizes. Inter handles body, buttons, navigation, and captions. The fallback stack walks `system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif` for both families.

The split is functional:
- Plus Jakarta Sans (display, 700 weight) — hero, h2, h3, card titles, stat numbers, the `postiz` wordmark.
- Inter (body + UI, 400–600 weight) — paragraphs, labels, buttons, nav.

### Hierarchy

| Token | Size | Line Height | Weight | Use |
|---|---|---|---|---|
| `{typography.hero}` | 70px | 77px | 700 | Homepage h1 — Plus Jakarta Sans, -0.01em tracking |
| `{typography.display-cta}` | 60px | 66px | 700 | Footer "Ready to get started?" — Plus Jakarta Sans |
| `{typography.display}` | 48px | 53px | 700 | Section headings ("Who is Postiz for?") — Plus Jakarta Sans |
| `{typography.card-title}` | 38px | 42px | 700 | Feature card titles — Plus Jakarta Sans |
| `{typography.sub-title}` | 34px | 37px | 700 | Sub-section heads, stat numbers — Plus Jakarta Sans |
| `{typography.lead}` | 21.5px | 29px | 400 | Hero & section lead paragraphs — Inter |
| `{typography.body}` | 18px | 24px | 400 | Default running-text, card descriptions — Inter |
| `{typography.small}` | 16px | 21px | 400 | Nav links, small body — Inter |
| `{typography.caption}` | 14px | 18px | 400 | Footer body, fine-print — Inter |
| `{typography.button}` | 19px | 25px | 500 | Primary button labels — Inter |
| `{typography.button-sm}` | 16px | 21px | 500 | Compact nav button labels — Inter |
| `{typography.banner}` | 15.8px | 24px | 400 | Announcement banner text — Inter |

### Principles
Plus Jakarta Sans is the brand voice — every display headline and the wordmark use it. Inter handles the supporting type. The boundary is strict: never put body copy in Plus Jakarta Sans, never put a display headline in Inter.

Display weight stays at **700** across all sizes — never 800 in body contexts, never lighter than 700 for headlines. The wordmark `postiz` pushes to 800 for extra geometric punch, but headlines hold at 700.

### Note on Font Substitutes
Both families are genuine and available on **Google Fonts** — no substitution is required. If Plus Jakarta Sans is unavailable, **Manrope** at weight 700 or **Inter** at weight 700 with -0.01em tracking are usable approximations that preserve the geometric, slightly condensed feel.

## Layout

### Spacing System
- **Base unit:** 4px.
- **Tokens:** `{spacing.space-1}` 4px · `{spacing.space-2}` 8px · `{spacing.space-3}` 12px · `{spacing.space-4}` 16px · `{spacing.space-5}` 24px · `{spacing.space-6}` 32px · `{spacing.space-7}` 40px · `{spacing.space-8}` 64px · `{spacing.section}` 90px.
- **Section padding:** `{spacing.section}` (90px) — the universal vertical rhythm between editorial bands.
- **Card internal padding:** `{spacing.space-7}` (40px) for feature / audience / integration cards; `{spacing.space-5}` (24px) for stat and testimonial cards.
- **Gutters:** `{spacing.space-3}` (12px) between cards in multi-card rows — a notably tight gutter that lets gradient cards sit close together.

### Grid & Container
- **Max content width:** ~1280px centered (inside a 1440 container with 80px gutters).
- **Editorial body:** Centered single column for most bands; the hero is centered (headline + icon row + lead + CTA stacked) with the product mockup on the gradient hero stage below.
- **Feature card grids:** 3-up at desktop with occasional 2-column spans for emphasis; 2-up at tablet; 1-up at mobile.
- **Integration cards:** 2-up at desktop.
- **Channels grid:** flex-wrap grid of 60px chips, centered, max ~760px.
- **Footer:** 1 brand column + 3 link columns (Tools / Resources / Company) at desktop.

### Whitespace Philosophy
Postiz uses generous vertical rhythm (90px section padding) but **tight 12px gutters** between cards — the gradient cards are meant to cluster into a glowing block against the dark floor. Card interiors are roomy at 40px. The result reads as confident and modern, never cramped.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Body sections, top nav, hero band — the near-black canvas |
| Hairline | 1px `{colors.hairline}` border | Inputs, FAQ dividers, footer divider, toggle-pill-group outline |
| Gradient card | `{gradients.*}` fill + `{shadow.card}` | Feature, integration, stat cards — color + deep shadow does the elevation |
| Dark card | `{colors.surface}` fill + `{shadow.card}` | Audience, testimonial cards |
| Pop | `{shadow.pop}` | Modals, the video play button |
| Glow | `{shadow.glow-violet}` | Featured / interactive ring on select elements |

The elevation philosophy is **deep, soft drop shadows only** (`{shadow.card}` — `0 24px 60px -20px rgba(0,0,0,0.7)`). No neumorphism, no glassmorphism. A subtle `{shadow.text}` (`2px 2px 6px rgba(0,0,0,0.6)`) keeps the bright pink banner legible.

### Decorative Depth
- Product UI screenshots embedded inside gradient cards carry their own internal chrome shadows — these are not system tokens, they're product UI shown as content.
- Scrim gradients (`{gradients.scrim-down}` / `{gradients.scrim-up}`) fade media edges and sit under the sticky header.
- The hand-drawn pink squiggle under headings adds a flat, human decorative layer — never shadowed.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.sm}` | 12px | Text inputs, small social chips, inner blocks |
| `{rounded.md}` | 20px | Stat cards, media tiles, large social chips |
| `{rounded.card}` | 32px | Feature cards, hero stage, CTA panel, footer top corners |
| `{rounded.pill}` | 9999px | Buttons, badges, toggle-pill-group, role pills, avatars |

### Photography Geometry
Avatar photos use `{rounded.pill}` (perfect circles). Product UI screenshots inside cards retain their native chrome and sit at `{rounded.sm}`–`{rounded.md}` inner radii. The hero product mockup sits on a `{rounded.card}` (32px) gradient stage and bleeds to the bottom edge. The footer panel uses an asymmetric `32px 32px 0 0` top radius to "close" the page.

## Components

### Top Navigation & Banner

**`announcement-banner`** — A full-width hot-pink (`{colors.brand-pink}`) bar pinned above the nav. Centered Inter body text with `{shadow.text}` for legibility. Carries product news with a lobster 🦞 emoji ("NEW: Generate UGC video with your OpenClaw 🦞").

**`top-nav`** — Near-black (`{colors.canvas}`) nav bar, sticky under the banner. Carries the `postiz` wordmark at left (Plus Jakarta Sans 800), a horizontal menu center (AI Agents CLI, Dev Docs, Channels, News, Blog, Pricing), and a right cluster with a `{component.button-ghost}` "Log In" + a `{component.button-primary-sm}` "Start for $0". Menu items in `{typography.small}` (Inter 16px / 400).

**`toggle-pill-group`** — A pill-radius wrapper around 2 hero segments ("I need normal scheduling" / "I want AI agents"). Background `rgba(255,255,255,0.08)` with a `{colors.hairline}` outline, 4px internal padding, rounded `{rounded.pill}`. Active segment renders as a white pill (`{component.toggle-pill-active}`). The pill-in-pill treatment is one of Postiz's signature interactive components.

### Buttons

**`button-primary`** — The signature primary CTA. Background `{colors.ink}` (#FFFFFF), text `{colors.on-primary}` (#0E0E0E), type `{typography.button}` (Inter 19px / 500), asymmetric padding 16px 24px 16px 32px (room for the trailing → arrow), rounded `{rounded.pill}`. Hover state lifts slightly (`button-primary-hover`). Active state shrinks to scale 0.985 (`button-primary-active`). Always paired with a trailing arrow and price-forward copy ("Start for $0").

**`button-primary-sm`** — Compact nav variant. Same white pill, `{typography.button-sm}` label, tighter 12px 18px 12px 24px padding.

**`button-ghost`** — Transparent pill with a 1px white (`rgba(255,255,255,0.85)`) outline, `{colors.ink}` text. Hover fills to `rgba(255,255,255,0.08)`. Used for "Log In".

**`text-link`** — Inline body links in `{colors.ink}` — the brand keeps inline links monochrome white on dark.

### Cards & Containers

**`hero-band`** — Centered hero on the `{colors.canvas}` floor: social-icon row + h1 (`{typography.hero}`) + pink squiggle + lead + primary CTA, then the `{component.hero-stage-card}` below. Vertical padding 120px top.

**`hero-stage-card`** — A large gradient stage (`{gradients.grad-hero}`) holding the actual Postiz product screenshot (hero chat mockup / scheduling calendar). Rounded `{rounded.card}` (32px), `{shadow.card}`, 64px top padding with the screenshot bleeding to the bottom edge. Carries the `{component.toggle-pill-group}` at the top.

**`feature-card`** — Used in the 3-up feature grid ("All the tools required for social media growth"). Background a rotating `{gradients.*}` fill, rounded `{rounded.card}` (32px), `{shadow.card}`, internal padding 28px. Carries a `{typography.card-title}` title, a body description in `{typography.caption}` at `{colors.muted}`, and a product screenshot filling the lower area. Some cards span 2 columns.

**`audience-card`** — Used in the 3-up "Who is Postiz for?" grid. Background flat `{colors.surface}` (#1A1919), rounded `{rounded.card}`, padding 28px. Carries a line-icon chip, a `{typography.card-title}` title (Agentic / Developers / Automation Teams), and a description. The flat-dark card signals "abstract audience claim"; the gradient card signals "look at the product".

**`product-mockup-card`** — A gradient card (`{gradients.grad-blue}` etc.) showing actual Postiz product UI fragments (scheduling calendar, AI assistant, analytics). The product UI inside has its own chrome — these cards display the product, they don't decorate around it.

**`stat-card`** — Used in the "Trusted by customers" auto-scrolling marquee. Background a `{gradients.*}` fill, rounded `{rounded.md}` (20px), padding 24px, fixed ~270px width. Carries a big stat number in `{typography.sub-title}` ("x4", "+50%"), a label, and a customer attribution in `{typography.caption}` ("— Cindy Goodman").

**`testimonial-card`** — Customer-quote card. Background `{colors.surface}`, rounded `{rounded.card}`, padding 24px. Top row carries an avatar + name + role; below sits the quote in `{typography.body}`. Coexists with video testimonial cards.

**`video-thumb-card`** — The "See Postiz in Action" / "GROW YOUR SOCIALS FAST" thumbnail. A `{colors.surface}` card holding a high-contrast thumbnail with a centered `{rounded.pill}` white play button (`{shadow.pop}`). Clicking dims the thumbnail to "play".

### Inputs & Forms

**`text-input`** — Standard text input (auth modal). Background `{colors.surface-3}` (#2E2E2E), text `{colors.ink}`, type `{typography.body}`, rounded `{rounded.sm}` (12px), padding 14px 16px. 1px `{colors.hairline}` border.

**`text-input-focused`** — Focus state. Border shifts to `{colors.brand-violet}` (#B491FF) for emphasis.

### Tags / Badges

**`badge-role`** — Small role pill (Owner / Moderator) used in product UI. Background `{colors.brand-violet-core}`, text `{colors.ink}`, type `{typography.caption}` at weight 600, rounded `{rounded.pill}`, padding 6px 14px.

**`badge-admin`** — Administrator variant. Background `{colors.brand-pink}` instead of violet-core. Same shape and type spec as `{component.badge-role}`.

### FAQ

**`faq-item`** — Accordion row. Transparent background, `{typography.body}` question in `{colors.ink}`, a pink (`{colors.brand-pink}`) "+" toggle that rotates 45° when open, `{colors.hairline}` bottom border. One item open at a time; the answer sits in `{typography.body}` / `{colors.body}`.

### CTA / Modal / Footer

**`cta-band`** — A pre-footer "Ready to get started?" panel. Background `{gradients.grad-violet-2}`, rounded `{rounded.card}`, padding 80px 40px, centered. Carries an h2 in `{typography.display}`, a sub-line, and a centered `{component.button-primary}`.

**`auth-modal`** — Login / Sign-up overlay. Background `{colors.surface}` (#1A1919) with a `{colors.hairline}` border, rounded `{rounded.md}` (20px–24px), `{shadow.card}`, 40px padding. Carries the `postiz` wordmark, GitHub/Google OAuth buttons, email + password `{component.text-input}`s, a full-width `{component.button-primary}`, and a 🦞 "You're in!" success state.

**`footer`** — The page-closing panel. Background steps up to `{colors.surface}` (#1A1919) with an asymmetric `32px 32px 0 0` top radius — the only surface shift on the page. Carries a centered "Ready to get started?" CTA, a giant pink-gradient `postiz` wordmark, a brand column + 3 link columns (Tools / Resources / Company), and a "Proudly open-source ❤️" bar. Text in `{colors.body}`.

## Do's and Don'ts

### Do
- Keep the canvas near-black (`{colors.canvas}` — #0E0E0E) end-to-end. Postiz never flips to a white body.
- Reserve `{colors.ink}` (#FFFFFF) for the primary pill CTA — Postiz's button is white-on-dark, always with a trailing → arrow.
- Use Plus Jakarta Sans 700 for every display headline. Pair with Inter body. Never blur the boundary.
- Pull card backgrounds from the `{gradients.*}` set and rotate through them (violet → magenta → blue → pink) so adjacent cards differ.
- Use the hot-pink squiggle (`{colors.brand-pink}`) under section headings — it's the signature human mark.
- Use `{component.feature-card}` (gradient) and `{component.audience-card}` (flat dark) deliberately — gradient signals "see the product", flat-dark signals "abstract claim".
- Embed real product UI screenshots inside gradient cards. Don't paint marketing illustrations when you can show the product itself.
- Render social platform chips in **full color**, never monochrome.
- Keep card gutters tight (12px) so gradient cards cluster into a glowing block.
- End every page with the slightly-lighter `{colors.surface}` footer and the giant `postiz` wordmark.

### Don't
- Don't use gradients on full-section backgrounds — they are reserved for cards and the hero stage. The page floor stays flat near-black.
- Don't put the pink accent on a button fill. Pink is for the banner, squiggles, and small strokes only.
- Don't bold display weight past 700 in headlines (the wordmark is the only 800 exception).
- Don't use a radius larger than `{rounded.card}` (32px) on cards.
- Don't introduce a third type family — Plus Jakarta Sans + Inter only.
- Don't add bluish-purple "AI slop" gradients on backgrounds, emoji decoration on cards, or rounded-corner-plus-left-border-accent cards. None of these appear in the system.
- Don't repeat the exact same gradient on two adjacent cards — rotate the palette.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | Hamburger nav; hero h1 70→36px; hero stage stacks; feature grids 1-up; stat marquee continues; footer columns → 1 |
| Tablet | 768–1024px | Top nav tightens; toggle-pill-group wraps; feature cards 2-up; integration cards 1-up |
| Desktop | 1024–1440px | Full top-nav; 3-up feature cards with 2-col spans; 2-up integration cards |
| Wide | > 1440px | Same as desktop with more outer breathing room; max content width caps at ~1280px |

### Touch Targets
- `{component.button-primary}` at ~57px height — comfortably above 44px.
- `{component.text-input}` height ~48px.
- `{component.toggle-pill-active}` padding 9px 20px — effective tap area meets 44px+ with the surrounding pill.

### Collapsing Strategy
- Top nav collapses to a hamburger at < 768px; menu opens as a full-screen sheet.
- Hero stays centered and stacks the gradient stage below the headline on mobile.
- Feature grids reduce columns (and drop 2-col spans) rather than scaling cards down.
- The stat marquee keeps auto-scrolling at every breakpoint.
- The channels grid re-wraps its 60px chips.
- Footer link columns collapse 3 → 1; the giant wordmark scales with `clamp()`.

### Image Behavior
- Product UI screenshots inside cards retain native aspect ratios; the cards resize around them.
- The hero product mockup bleeds to the bottom edge of its gradient stage and scales proportionally.
- Avatar photos crop to circles at every breakpoint.

## Iteration Guide

1. Focus on ONE component at a time. Reference its YAML key directly (`{component.feature-card}`, `{component.stat-card}`).
2. Variants of an existing component (`-hover`, `-active`, `-focused`) live as separate entries in `components:`.
3. Use `{token.refs}` everywhere — never inline hex. Pull card backgrounds from `{gradients.*}`.
4. Display headlines stay Plus Jakarta Sans 700. Body stays Inter 400. The split does not blur.
5. The canvas stays near-black; gradients live on cards only. Don't gradient a section background.
6. Rotate the gradient palette across adjacent cards — never repeat the same gradient twice in a row.
7. When in doubt about emphasis: bigger Plus Jakarta Sans, or a gradient card, before any new color.

## Known Gaps

- The source is the Postiz marketing **homepage only** (Figma reconstruction `postiz.com.fig`, 1920w light frame). The product/app surface (calendar, composer, analytics dashboards) is shown only as in-card screenshots — its full component spec is out of scope.
- **Plus Jakarta Sans** and **Inter** are both genuine and on Google Fonts; no local TTFs were provided, so exact hinting/metrics are assumed from Google's builds.
- **Social platform icons** are documented as full-color chips; the brand's own icon SVGs are vector-split in the `.fig` and were substituted with Simple Icons CDN glyphs in the UI kit.
- The **`postiz` wordmark** is stored as per-letter vector paths, not a clean SVG — reproduced as styled Plus Jakarta Sans 800 text. Exact letterforms may differ slightly.
- Gradient stops are read from the Figma fills and rounded; seasonal/marketing variations may shift them.
- Animation and transition timings (marquee speed, toggle swap, modal entrance, FAQ expand) are inferred from web convention, not extracted from the source.
- Semantic colors (success / warning / error) are reasonable brand-aligned values, not directly observed on the marketing homepage.
- The OpenClaw lobster mascot appears only as a raster inside the hero chat mockup; no standalone vector was extractable.
