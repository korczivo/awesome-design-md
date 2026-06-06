---
version: alpha
name: claude-marketing
description: >
  A warm oat editorial canvas where serif display type at modest weight carries
  every headline, coral accents the asterisk and send button only, and hand-drawn
  ink illustrations sit in generous whitespace — no gradients, no shadows, no
  atmospheric meshes.
colors:
  primary: "#141413"
  primary-press: "#0D1218"
  coral: "#D97757"
  coral-press: "#C96442"
  canvas: "#FAF9F5"
  canvas-2: "#F5F4ED"
  surface-card: "#FFFFFF"
  surface-tan: "#F0EEE6"
  surface-strong: "#E8E6DC"
  chip-rest: "#DEDCD1"
  chip-hover: "#E8E6DC"
  surface-dark: "#141413"
  surface-dark-2: "#262624"
  border-hairline: "#E8E6DC"
  border-strong: "#DEDCD1"
  border-dark: "#3D3D3A"
  ink: "#141413"
  body: "#5E5D59"
  muted: "#87867F"
  placeholder: "#B0AEA5"
  on-dark: "#FAF9F5"
  on-dark-muted: "#B0AEA5"
  on-coral: "#FAF9F5"
  sage-tile: "#BCD1CA"
rounded:
  xs: 2px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  pill: 9999px
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section-sm: 96px
  section: 128px
  section-lg: 160px
typography:
  display-xl:
    fontFamily: "'EB Garamond', Georgia, serif"
    fontSize: 64px
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: -1.5px
  display-lg:
    fontFamily: "'EB Garamond', Georgia, serif"
    fontSize: 48px
    fontWeight: 400
    lineHeight: 1.10
    letterSpacing: -1px
  display-md:
    fontFamily: "'EB Garamond', Georgia, serif"
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1.15
    letterSpacing: -0.5px
  display-sm:
    fontFamily: "'EB Garamond', Georgia, serif"
    fontSize: 28px
    fontWeight: 400
    lineHeight: 1.20
    letterSpacing: -0.3px
  title-lg:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.3
    letterSpacing: 0
  title-md:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 18px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  title-sm:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  body-md:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body-sm:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
  caption-uppercase:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 1.5px
  code:
    fontFamily: "'JetBrains Mono', ui-monospace, monospace"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  button:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1
    letterSpacing: 0
  nav-link:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: 14px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0
components:
  top-nav:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.nav-link}"
    height: 72px
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 10px 16px
  button-primary-press:
    backgroundColor: "{colors.primary-press}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 10px 16px
  button-outline:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    border: "1px {colors.border-hairline}"
    padding: 10px 16px
  button-coral:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.on-coral}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 9px 14px
  button-coral-press:
    backgroundColor: "{colors.coral-press}"
    textColor: "{colors.on-coral}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 9px 14px
  button-text:
    backgroundColor: transparent
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
  chip:
    backgroundColor: "{colors.chip-rest}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 0 12px
    height: 32px
  segmented-tabs:
    backgroundColor: "{colors.surface-tan}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.pill}"
  composer-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    border: "1px {colors.border-hairline}"
    height: 52px
    padding: 8px
  composer-dark:
    backgroundColor: "{colors.surface-dark-2}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.lg}"
    border: "1px {colors.border-dark}"
    height: 52px
    padding: 8px
  hero-band:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-xl}"
    padding: "{spacing.section-lg}"
  model-tier-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.lg}"
    border: "1px {colors.border-hairline}"
    padding: 52px 64px
  news-toast:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.title-md}"
    rounded: "{rounded.xl}"
    border: "1px {colors.border-strong}"
    shadow: "0 12px 24px rgba(0,0,0,0.08)"
    padding: 16px
  video-player:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.lg}"
  signature-cta-section:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-lg}"
    padding: "{spacing.section-lg}"
  footer:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body-sm}"
    padding: 96px 64px
  asterisk-mark:
    color: "{colors.coral}"
  wordmark:
    textColor: "{colors.ink}"
    typography: "{typography.display-sm}"
---

## Overview

Claude's marketing surface — the [Product Overview page](https://claude.com/product/overview) — is a quiet, editorial system. Read it as a printed magazine, not a SaaS template. The atmosphere is a **warm oat canvas** (`{colors.canvas}` — #FAF9F5, never pure white), a serif display voice (Copernicus / EB Garamond, weight 400) at large sizes, a single coral accent (`{colors.coral}` — #D97757) reserved for the asterisk mark and the coral primary CTA, and hand-drawn black-ink illustrations sitting in whitespace. There are **no gradients, no atmospheric meshes, no decorative shadows**. Voltage comes from confident type sitting in 160px of breathing room.

The brand has two display moves and one accent move:

1. The **serif at weight 400** doing the heavy lifting at 48–64px. Headlines never go bolder than 400; emphasis comes from size and whitespace, not from weight.
2. The **near-black primary CTA** (`{colors.primary}` — #141413) with white text and a small `{rounded.sm}` (6px) corner. Final, never decorative.
3. The **coral accent** (`{colors.coral}` — #D97757) appearing only on the asterisk logomark and the "Ask Claude" send-button. Never as a background tint, gradient, or wash.

**Key characteristics:**
- Surface is **always oat** (`{colors.canvas}`) — even the topnav stays oat over dark sections.
- Primary CTA is `{component.button-primary}` (ink) — the "Try Claude" / "Get started" button visible on every viewport.
- Coral is used **only** on `{component.asterisk-mark}` and `{component.button-coral}` (the chat "Ask Claude" send button).
- Body text is one tone (`{colors.body}` — #5E5D59) — there is no warm/cool body split.
- Section rhythm: oat hero → oat connection band → oat tabbed demo card → oat model list → oat video → oat CTA → oat release list → **dark footer**. The dark footer is the only signature surface; everything above it lives on the same warm cream.
- Hand-drawn line illustrations (single-color black, 2–3px stroke, deliberately imperfect) anchor every section. **This is the brand's strongest visual signature.**
- Vertical rhythm is `{spacing.section-lg}` (160px) for hero/CTA bands and `{spacing.section}` (128px) for body sections.
- Border radius is hierarchical: `{rounded.sm}` (6px) for buttons; `{rounded.md}` (8px) for chips and icon buttons; `{rounded.lg}` (12px) for the composer and content cards; `{rounded.xl}` (16px) for the news toast; `{rounded.pill}` for the segmented tab track.

## Colors

### Brand & accent
- **Primary** (`{colors.primary}` — #141413): Near-black with a slight warm cast. Used for h1/h2 text, primary CTA background, and the footer's dark band. Same hex serves type and surface — they are the same role expressed at different layers.
- **Coral** (`{colors.coral}` — #D97757): The brand accent. Used **only** on `{component.asterisk-mark}` and the coral "Ask Claude" send button. Press state is `{colors.coral-press}` (#C96442).

### Surface
- **Canvas** (`{colors.canvas}` — #FAF9F5): Oat off-white. The default surface of every page on the marketing site.
- **Surface 2** (`{colors.canvas-2}` — #F5F4ED): Slightly cooler oat, used inside some grouped cards.
- **Surface Card** (`{colors.surface-card}` — #FFFFFF): The pure-white plate used for the three model tier cards.
- **Chip Rest** (`{colors.chip-rest}` — #DEDCD1): The default chip background (`{component.chip}`). Press state darkens to `{colors.chip-hover}` (#E8E6DC).
- **Surface Dark** (`{colors.surface-dark}` — #141413): Footer band. Same hex as `{colors.primary}` because the system treats ink and dark surface as one role.
- **Sage Tile** (`{colors.sage-tile}` — #BCD1CA): The soft sage square that sits behind the Opus model-card image in the news toast. The only cool-cast color anywhere in the system.

### Text
- **Ink** (`{colors.ink}` — #141413): h1/h2 display, primary CTA text-on-dark replacement.
- **Body** (`{colors.body}` — #5E5D59): Every paragraph of body copy.
- **Muted** (`{colors.muted}` — #87867F): Section labels, eyebrows, footer link headers.
- **Placeholder** (`{colors.placeholder}` — #B0AEA5): Composer placeholder text.
- **On Dark** (`{colors.on-dark}` — #FAF9F5): Text on the footer's dark band — note this is oat, **not** pure white, to keep the warmth consistent.

### Borders
- **Hairline** (`{colors.border-hairline}` — #E8E6DC): 1px borders on the composer, model cards, and section dividers.
- **Strong** (`{colors.border-strong}` — #DEDCD1): The slightly denser 1px line used on outline buttons.
- **Dark** (`{colors.border-dark}` — #3D3D3A): 1px borders inside the dark footer composer.

## Typography

### Font Family
The system runs **EB Garamond** (Google Fonts) for display and **Inter** (Google Fonts) for UI sans. EB Garamond is a classical garalde — strong bracketed serifs, humanist proportions — that holds up at large sizes and reads beautifully at weight 400.

The substitution preserves the brand's most important quality: a strong-serif display face that does the heavy lifting at 28–64px and reads as editorial, not corporate. Anthropic's production site uses the licensed **Copernicus** — if that becomes available, edit `colors_and_type.css` and swap `'EB Garamond'` for `'Copernicus', 'EB Garamond'` in `--font-display`.

### Hierarchy

| Token | Size | Weight | Line height | Letter spacing | Use |
|---|---|---|---|---|---|
| `{typography.display-xl}` | 64px | 400 | 1.05 | -1.5px | Hero h1 "Meet your thinking partner" |
| `{typography.display-lg}` | 48px | 400 | 1.10 | -1.0px | Section h2 ("Claude models", "Keep thinking with Claude") |
| `{typography.display-md}` | 36px | 400 | 1.15 | -0.5px | Sub-section h2, the "Opus 4.7" plan-name slot |
| `{typography.display-sm}` | 28px | 400 | 1.20 | -0.3px | h3, the model description ("Most powerful model for…"), large release titles |
| `{typography.title-lg}` | 22px | 500 | 1.3 | 0 | Editorial section titles |
| `{typography.title-md}` | 18px | 500 | 1.4 | 0 | Block headings ("Break down problems together"), toast title |
| `{typography.title-sm}` | 16px | 500 | 1.4 | 0 | Card titles |
| `{typography.body-md}` | 16px | 400 | 1.55 | 0 | Default body copy, paragraphs |
| `{typography.body-sm}` | 14px | 400 | 1.55 | 0 | Secondary copy, composer placeholder, footer links |
| `{typography.caption}` | 13px | 500 | 1.4 | 0 | Eyebrows, meta labels (e.g. "Announcement · Product") |
| `{typography.caption-uppercase}` | 12px | 500 | 1.4 | 1.5px | Footer column titles, "© 2026 ANTHROPIC PBC", "BY ANTHROP\C" |
| `{typography.code}` | 14px | 400 | 1.6 | 0 | The terminal screenshot block |
| `{typography.button}` | 14px | 500 | 1.0 | 0 | All button labels (primary, outline, coral, link) |
| `{typography.nav-link}` | 14px | 500 | 1.4 | 0 | Top-nav items |

### Principles
- **Display is serif at weight 400.** A 64px hero is set at weight 400 — emphasis comes from size and letter-spacing tightening (-1.5px on the largest headline), not from bolder weight. The system never goes above 400 on display type.
- **UI is sans at weight 500.** Titles, buttons, chips, captions, and nav links all use Inter at medium weight (500). Body running text is the only sans element at weight 400.
- **There is no weight 600 or 700 in the system.** Boldness lives in the contrast between large serif at 400 vs. small sans at 500 — never in heavier weight values.
- **Negative letter-spacing is reserved for display sizes**, scaled to the size: -1.5px at 64px, -1px at 48px, -0.5px at 36px, -0.3px at 28px. UI sans (titles, body, captions) is set at letter-spacing 0. The single exception is `{typography.caption-uppercase}`, which uses **+1.5px** spacing to give uppercase tracking room.

### Note on substitutes
This kit runs **EB Garamond** + **Inter** from Google Fonts as the production font pair. Anthropic's licensed brand fonts are **Copernicus** (display) and **Styrene B** (sans). If you have either licensed, prepend them to the `--font-display` / `--font-sans` stacks in `colors_and_type.css`:

```css
--font-display: 'Copernicus', 'EB Garamond', Georgia, serif;
--font-sans:    'Styrene B', 'Inter', system-ui, sans-serif;
```

## Layout

### Spacing system
- **Base unit:** 4px (all spacing snaps to 4-multiples).
- **Tokens:** `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section-sm}` 96px · `{spacing.section}` 128px · `{spacing.section-lg}` 160px.
- **Section padding (vertical):** `{spacing.section-lg}` (160px) is the hero/CTA constant; `{spacing.section}` (128px) is the standard body-band constant.
- **Card internal padding:** `{spacing.xxl}` (48px) inside the three model tier cards; `{spacing.lg}` (24px) inside the news toast; `{spacing.md}` (16px) inside chips and composer.
- **Gutters:** `{spacing.lg}` (24px) between grid items; `{spacing.xs}` (8px) between chips in a row.

### Grid & container
- **Max content width:** ~1280px–1440px centered, with `{spacing.xxl}` (48–64px) horizontal breathing room.
- **Editorial body:** A loose 12-column grid. Most sections collapse to two columns (left text, right art) at desktop.
- **Top nav:** 72px tall, sticky, oat — never inverts.
- **Footer link grid:** 5 columns at desktop.

### Whitespace philosophy
Claude uses whitespace as the dominant atmospheric tool. The hero sits in 160px of pure whitespace above and below the headline + sub-headline + composer cluster, with no decoration in that whitespace. There is no gradient, no aurora, no spotlight, no mesh. The system trusts whitespace alone to do the framing.

## Elevation & depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow, no border | Hero, body sections, footer |
| Soft hairline | 1px `{colors.border-hairline}` border | Inputs, model tier cards, news toast outline, outline buttons |
| Toast | `0 12px 24px rgba(0,0,0,0.08)` | **Only** the bottom-right news toast |
| Card flat | No shadow; depth via color contrast against the oat surface | Model tier cards, lilac demo card |

**The elevation philosophy is "almost nothing."** Depth is delegated to color contrast and whitespace, not shadows. The toast is the single exception, and it's deliberately the only floating element in the system.

### Decorative depth
- **Hand-drawn illustrations** in single-color black ink with a 2–3px wobble stroke — the megaphone above "Keep thinking with Claude", the cloud above "Claude models", the party-popper next to "Explore the latest releases", the cable above "The AI for problem solvers". These render at 48–56px and read as drawn-by-hand on paper.
- **The hero scribble** — a tangled black line wrapping a single coral disc. The most recognizable composition in the brand vocabulary.

## Shapes

### Border radius scale

| Token | Value | Use |
|---|---|---|
| `{rounded.xs}` | 2px | (reserved — not used on this surface) |
| `{rounded.sm}` | 6px | Primary CTAs, coral "Ask Claude" button |
| `{rounded.md}` | 8px | Chips, icon buttons, the asterisk's mask-square in the news toast |
| `{rounded.lg}` | 12px | Composer, content cards |
| `{rounded.xl}` | 16px | News toast |
| `{rounded.pill}` | 9999px | The segmented "Tasks / Learn / Code …" tab track |

## Components

> **No hover states documented.** Per the global no-hover policy, every spec below covers only Default and Active/Pressed states.

### Navigation

**`top-nav`** — A 72px-tall oat bar pinned to the top of every page. Asterisk + Claude wordmark at left; primary horizontal menu (Meet Claude, Platform, Solutions, Pricing, Resources) center-aligned in `{typography.nav-link}`; the right cluster carries "Login" text link, `{component.button-outline}` "Contact sales", and `{component.button-primary}` "Try Claude". The nav stays light on every page — Claude does not invert the nav over the dark footer.

### Buttons

**`button-primary`** — The signature primary CTA. Background `{colors.primary}` (ink), text `{colors.on-dark}` (oat), `{typography.button}`, padding 10×16, rounded `{rounded.sm}` (6px). The "Try Claude" / "Get started" button visible on every hero.

**`button-primary-press`** — Press state for `{component.button-primary}`. Background `{colors.primary-press}` (#0D1218), text `{colors.on-dark}`, same type and padding as default.

**`button-outline`** — Oat with a hairline outline. Background `{colors.canvas}`, text `{colors.ink}`, `{typography.button}`, rounded `{rounded.sm}`, 1px `{colors.border-hairline}`. Sits next to `{component.button-primary}` as the "less-committed" choice ("Contact sales").

**`button-coral`** — The single coral action. Background `{colors.coral}` (#D97757), text `{colors.on-coral}` (oat), rounded `{rounded.sm}` (6px), padding 9×14. Used **only** for the "Ask Claude" send button inside `{component.composer-light}` and `{component.composer-dark}`. Never used elsewhere.

**`button-coral-press`** — Press state for `{component.button-coral}`. Background `{colors.coral-press}` (#C96442), text `{colors.on-coral}`, same type and padding as default.

**`button-text`** — Inline link-style buttons in `{colors.ink}` ("Login", "Explore here"). No underline by default. Inherits `{typography.body-md}`.

### Chips

**`chip`** — The prompt chip used in three places: under the hero composer (Write / Learn / Code), inside the dark footer composer, and on the "Download the desktop app" row (macOS / Windows / Windows arm64). Background `{colors.chip-rest}` (#DEDCD1), text `{colors.ink}`, rounded `{rounded.md}` (8px), height 28–32px, padding 0×12px.

**`segmented-tabs`** — The "Tasks / Learn / Code / Research / Analyze / Create" pill row above the lilac demo card. Track is a `{rounded.pill}` (9999px) capsule of `{colors.surface-tan}`; active tab gets a `{colors.canvas}` background pill inside the track with a 1px hairline shadow. Type is `{typography.body-sm}`.

### Forms

**`composer-light`** — The hero chat composer. Background `{colors.canvas}`, 1px `{colors.border-hairline}` border, `{rounded.lg}` (12px), height 52px, padding 8px. Left holds an unstyled text input with `{typography.body-sm}` placeholder; right holds `{component.button-coral}` "Ask Claude" with a trailing arrow-up.

**`composer-dark`** — Same shape as `{component.composer-light}` but inverted. Background `{colors.surface-dark-2}` (#262624), 1px `{colors.border-dark}`, `{rounded.lg}`. Used in the dark footer's brand column. The send button becomes a square `{rounded.md}` 28px coral icon button (no "Ask Claude" label).

### Cards

**`hero-band`** — Full-width oat hero. No border, no shadow. Two-column grid: left holds h1 + `{typography.body-md}` subhead + composer + chip row; right holds the hand-drawn scribble + coral disc. Vertical padding `{spacing.section-lg}` (160px).

**`model-tier-card`** — White plate for the three Claude tiers (Opus / Sonnet / Haiku). Background `{colors.surface-card}` (#FFFFFF), `{rounded.lg}` (12px) — actually a touch larger (14px) in the live spec — padding 52×64px. Grid: plan name `{typography.display-md}` (36px serif 400) on the left; description in `{typography.display-sm}` (28px serif 400) on the right with a chip-meta row below and a "Model details →" button.

**`news-toast`** — A 384px floating card fixed to bottom-right. Background `{colors.canvas}`, 1px `{colors.border-strong}`, `{rounded.xl}` (16px), padding 16px, the **only** elevated surface in the system (`shadow: 0 12px 24px rgba(0,0,0,0.08)`). Header is a "↗ Latest news" pin + a 28px hairline close-button. Body is a text column ("Claude Opus 4.7" + body + a dark "Learn more" button) and a 96×96 sage-tile-backed product image at right.

**`video-player`** — A 16:9 dark plate (`{colors.surface-dark}` fallback) with the cover image, a centered 68×68 oat play button (`{rounded.lg}`, contains a 26px ink play triangle). No controls overlay by default.

**`signature-cta-section`** — The "The AI for problem solvers" band: centered `{typography.display-lg}` headline, `{component.button-primary}` desktop-app CTA, and a bottom `{component.composer-light}` prompt input. Full-width oat surface with `{spacing.section-lg}` vertical padding.

### Footer

**`footer`** — Full-bleed dark band (`{colors.surface-dark}`). Padding 96×64. Two-row layout:
- **Top row:** Brand column (asterisk + wordmark + dark composer + 3 chips) on the left; 5-column link grid on the right. Column titles use `{typography.caption-uppercase}` in `{colors.on-dark-muted}` (#B0AEA5); links use `{typography.body-sm}` in `{colors.on-dark}` (oat).
- **Bottom row:** "BY ANTHROP\C" wordmark in oat-muted with a "© 2026 ANTHROPIC PBC" subline; X / LinkedIn / Instagram social icons; a "English (US)" language picker (`{component.button-outline}` styling but on the dark band — border becomes `{colors.border-dark}`).

### Signature components

**`asterisk-mark`** — The hand-drawn eight-pointed star. Always `{colors.coral}`. Sits to the left of the "Claude" wordmark in the topnav, the footer, and the constellation center. **The single most recognizable brand asset.** See `assets/claude-asterisk.svg` (or `claude-asterisk-coral.svg` for the pre-colored variant).

**`wordmark`** — The "Claude" serif logotype. Rendered in `{colors.ink}` on light, `{colors.on-dark}` on dark. The letter shapes match Copernicus exactly. See `assets/claude-wordmark.svg` / `claude-wordmark-ink.svg` / `claude-wordmark-white.svg`.

## Do's and Don'ts

### Do
- Keep `{component.button-primary}` near-black. The brand's primary CTA is `{colors.primary}`, not coral.
- Use coral **only** on `{component.asterisk-mark}` and `{component.button-coral}`. Coral is not a brand fill, not a tint, not a divider.
- Trust whitespace as the hero atmosphere. Hero bands are intentionally calm — no gradient, no mesh, no atmospheric backdrop.
- Use `{component.news-toast}` sparingly. It's the only elevated surface in the system; promoting other cards to shadow-bearing surfaces breaks the language.
- Keep the topnav oat on every page, including over the dark footer.
- Anchor every editorial band with `{spacing.section}` (128px) or `{spacing.section-lg}` (160px) vertical padding.

### Don't
- Don't add a gradient backdrop to the hero. Claude's hero is oat, full stop. Mesh, aurora, spotlight gradients all read as "another AI template" — not Claude.
- Don't bold display-weight type. `{typography.display-xl}` and `{typography.display-lg}` are weight 400 — emphasis comes from size and letter-spacing, not from going to 500/600/700. Going heavier reads as marketing-page-template.
- Don't repeat coral across multiple elements in a viewport. There's one coral asterisk and one coral send-button. That's it.
- Don't add hover state styling beyond what the system already encodes. The system documents Default and Active/Pressed only.
- Don't add new accent colors. The system's voltage already lives in the coral / oat / ink trio. Adding a blue or a green breaks the visual signature instantly.
- Don't use rounded-pill on buttons — the segmented tab track is the only place pill-shape appears.
- Don't redraw the hand-drawn glyphs with vector tools. They have a deliberate marker-on-paper wobble. If you don't have the originals, leave the glyph slot empty and document the gap.

## Responsive Behavior

### Breakpoints

| Name | Width | Key changes |
|---|---|---|
| Mobile | < 768px | Top nav collapses to hamburger; hero stacks 1-column with art above text; news toast becomes full-width sticky bottom card; demo card drops to 1-up |
| Tablet | 768–1024px | 2-up demo grid; top nav stays horizontal but tightens; model tier cards stack vertically |
| Desktop | 1024–1440px | 3-up + 2-column hero (text left, art right); 5-column footer grid |
| Wide | > 1440px | Same as Desktop with more outer breathing room; content max caps at ~1280px |

### Touch targets
- `{component.button-primary}` renders at ≥40px height — comfortably above the recommended 44 × 44 once padding is included.
- `{component.chip}` is 28–32px tall. On mobile, expand to 40px hit area via outer padding without changing visual size.
- `{component.composer-light}` is 52px tall, which gives the embedded `{component.button-coral}` plenty of touch surface.

## Iteration guide

1. Focus on ONE component at a time. Reference its YAML key directly (`{component.button-primary}`, `{component.composer-light}`).
2. When adding a new component, decide first which role it plays: editorial body (oat, serif, hairline borders) or footer/dark (ink, sans, dark borders).
3. Variants of an existing component (`-press`, `-disabled`, `-focus`) live as separate entries in `components:` — never as nested state objects.
4. Use `{token.refs}` everywhere prose mentions a color, a radius, a typography role, or a spacing value. Hex codes appear at most once next to the reference.
5. Never document hover. The system documents Default and Active/Pressed states only.
6. When in doubt about emphasis: bigger type before bolder type, more whitespace before more color.

## Known gaps

- The exact hex values of the lilac demo-card surface and the smaller hand-drawn glyphs are inferred from screenshot pixel sampling. Some seasonal launches may swap these.
- The pricing-page sub-system (pill buttons, Inter Display) is NOT in scope for this surface. The product-overview page lives entirely in the editorial dialect.
- Animation and transition timings are documented only at the system level (240ms standard ease) — per-component motion specs are not extracted.
- The cover image of the "Keep thinking" video reel (the green "PROBLEMS" pixel-art still) is included in `assets/video-curiosity-thumb.jpg`. The "Cowork" demo card art is not extracted — placeholder lives in `Icons.jsx`.
- Mobile breakpoint specifics (hamburger drawer behavior, the bottom-sheet news toast variant) are described structurally but not formalized.
- Anthropic's licensed brand fonts (Copernicus, Styrene B) are substituted with EB Garamond and Inter. Swap if you have the originals.
