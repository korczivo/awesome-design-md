---
version: alpha
name: n8n
description: A developer-first automation interface anchored on a deep violet-black canvas with white Inter display headlines set at regular weight and tight tracking. The brand carries almost no decorative voltage in its layout — energy comes from two signature gradients (a warm orange→red "Fire" on the single primary action, a cooler blue→purple "Cosmos" on secondaries), photo-real cinematic hero renders (the lightning bolt), and a two-tone two-line headline trick (grey first line, white second). Type stays regular weight even at huge sizes to feel engineered, never bombastic; surfaces are dark-only with light-on-dark borders, and a floating glass capsule nav is the defining structural motif.

colors:
  canvas: "#0E0918"
  surface-card: "#1F192A"
  surface-elevated: "#2A2633"
  hairline: "rgba(255,255,255,0.08)"
  hairline-strong: "#3A3447"
  ink: "#FFFFFF"
  body: "#C1C8D5"
  muted-display: "#B6B5B9"
  muted-soft: "#B6B5B9"
  muted: "#9D9797"
  faint: "#6E6976"
  on-dark: "#FFFFFF"
  accent: "#FD8925"
  pink: "#E41E5A"
  orange: "#FD8925"
  red: "#FF0C00"
  blue: "#077AC7"
  purple: "#6B21EF"
  violet-soft: "#8F87F7"
  glass-fill: "rgba(255,255,255,0.05)"
  glass-fill-hi: "rgba(255,255,255,0.10)"
  glass-fill-md: "rgba(255,255,255,0.15)"
  glass-border: "rgba(255,255,255,0.20)"
  success: "#2FB67C"
  info: "#36C5F1"
  warn: "#ECB22D"
  danger: "#FF0C00"

gradients:
  fire: "linear-gradient(180deg, #FD8925 0%, #FF0C00 100%)"
  fire-flat: "linear-gradient(135deg, #FD8925 0%, #FF0C00 100%)"
  cosmos: "linear-gradient(180deg, #077AC7 0%, #6B21EF 100%)"
  cosmos-h: "linear-gradient(90deg, #077AC7 0%, #6B21EF 100%)"
  aurora: "radial-gradient(60% 60% at 50% 100%, rgba(253,152,37,0.65) 0%, rgba(253,152,37,0) 60%), radial-gradient(60% 60% at 50% 100%, rgba(228,30,90,0.30) 0%, rgba(228,30,90,0) 70%)"
  nebula: "radial-gradient(circle at 30% 20%, rgba(175,106,140,0.46) 0%, rgba(98,65,83,0) 55%), radial-gradient(circle at 70% 80%, rgba(122,57,109,0.29) 0%, rgba(42,25,41,0) 100%), linear-gradient(180deg, rgba(13,10,25,0.4) 0%, #0E0918 100%)"
  protect: "linear-gradient(180deg, #0E0918 0%, rgba(14,9,24,0) 30%, rgba(14,9,24,0) 75%, #0E0918 100%)"

typography:
  hero:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 60px
    fontWeight: 400
    lineHeight: 64px
    letterSpacing: -0.02em
  h1:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 45px
    fontWeight: 400
    lineHeight: 48px
    letterSpacing: -0.02em
  h2:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: -0.01em
  h3:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 24px
    fontWeight: 500
    lineHeight: 29px
    letterSpacing: -0.01em
  h4:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 18px
    fontWeight: 600
    lineHeight: 23px
  body:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 23px
  meta:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 18px
  label:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 11px
    fontWeight: 500
    lineHeight: 14px
    letterSpacing: 0.04em
  button:
    fontFamily: "'Inter', ui-sans-serif, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 21px
  mono:
    fontFamily: "'JetBrains Mono', ui-monospace, monospace"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.55

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  2xl: 24px
  pill: 999px

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
  space-32: 128px
  space-40: 160px
  space-48: 192px

elevation:
  sm: "0 1px 2px rgba(8,8,8,0.20)"
  md: "0 4px 12px rgba(8,8,8,0.26), inset 0 1px 0 rgba(255,255,255,0.04)"
  lg: "0 16px 40px rgba(8,8,8,0.44), inset 0 1px 0 rgba(255,255,255,0.06)"
  cta: "0 8px 24px rgba(255,12,0,0.28), inset 0 1px 0 rgba(255,255,255,0.30)"
  glow: "0 0 80px rgba(253,137,37,0.35)"
  ring-focus: "0 0 0 3px rgba(228,30,90,0.40)"

components:
  button-primary:
    backgroundColor: "{gradients.fire}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 0 20px
    height: 40px
    shadow: "{elevation.cta}"
  button-primary-active:
    transform: scale(0.98)
  button-secondary:
    backgroundColor: "{gradients.cosmos}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 0 20px
    height: 40px
  button-ghost:
    backgroundColor: "{colors.glass-fill-md}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 0 20px
    height: 40px
    border: 1px solid "{colors.glass-border}"
  button-small:
    backgroundColor: "{gradients.fire}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.md}"
    padding: 0 12px
    height: 32px
  button-icon:
    backgroundColor: "{colors.glass-fill-hi}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.md}"
    size: 32px
    border: 1px solid rgba(255,255,255,0.18)
  glass-capsule-nav:
    backgroundColor: "{colors.glass-fill}"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.xl}"
    height: 58px
    border: 1px solid "{colors.glass-border}"
    backdropFilter: blur(24px)
  pill:
    backgroundColor: "{colors.glass-fill-hi}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: 0 10px
    height: 26px
    border: 1px solid rgba(255,255,255,0.14)
  pill-fire:
    backgroundColor: rgba(255,12,0,0.12)
    textColor: "#FF8567"
    rounded: "{rounded.pill}"
    padding: 0 10px
    height: 26px
    border: 1px solid rgba(255,12,0,0.35)
  pill-cosmos:
    backgroundColor: rgba(107,33,239,0.18)
    textColor: "#B49AFF"
    rounded: "{rounded.pill}"
    padding: 0 10px
    height: 26px
    border: 1px solid rgba(107,33,239,0.5)
  pill-hiring:
    backgroundColor: "{colors.pink}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: 0 10px
    height: 26px
  pill-success:
    backgroundColor: rgba(47,182,124,0.14)
    textColor: "#7FE1B4"
    rounded: "{rounded.pill}"
    padding: 0 10px
    height: 26px
    border: 1px solid rgba(47,182,124,0.40)
  text-input:
    backgroundColor: rgba(255,255,255,0.04)
    textColor: "{colors.on-dark}"
    typography: "{typography.meta}"
    rounded: "{rounded.md}"
    padding: 0 12px
    height: 38px
    border: 1px solid rgba(255,255,255,0.12)
  text-input-focused:
    border: 1px solid "{colors.pink}"
    shadow: "{elevation.ring-focus}"
  toggle:
    backgroundColor: "{colors.glass-fill-md}"
    rounded: "{rounded.pill}"
    width: 34px
    height: 20px
    border: 1px solid rgba(255,255,255,0.18)
  toggle-on:
    backgroundColor: "{gradients.fire}"
  checkbox:
    rounded: 5px
    size: 18px
    border: 1.5px solid rgba(255,255,255,0.40)
  checkbox-on:
    backgroundColor: "{gradients.fire}"
  feature-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.on-dark}"
    titleTypography: "{typography.h3}"
    bodyTypography: "{typography.body}"
    rounded: "{rounded.2xl}"
    padding: 24px
    border: 1px solid rgba(255,255,255,0.06)
    shadow: "{elevation.lg}"
---

## Overview

n8n's marketing surface is a deep violet-black canvas (`{colors.canvas}` — #0E0918) holding white **Inter** headlines set at **regular weight with tight `-0.02em` tracking**. The brand is dark-first and single-theme — there is no light-mode marketing surface anywhere. UI chrome stays minimal: light-on-dark borders rendered as `rgba(255,255,255,0.x)` rather than solid grey, generous negative space between sections, and copy that addresses the reader directly.

Brand energy comes from **two signature gradients** rather than from layout decoration. **Fire** (`{gradients.fire}` — orange→red) carries the single most important action on any view and the emotional core of the hero illustration. **Cosmos** (`{gradients.cosmos}` — blue→purple) carries secondary CTAs and info/case-study surfaces. The discipline is strict: one Fire action per view, never two warm gradients competing in the same eyeful, and the gradients live on *objects* (buttons, the hero core, a glow) — never as page wallpaper.

Type voice runs **Inter** as the single typeface for display, UI, and body, with **JetBrains Mono** reserved for code, star counts, and technical chips. The display effect is achieved through size and tight tracking at **regular (400) weight** — n8n never bolds a hero. The single most identifiable type pattern is the **two-tone two-line headline**: the first line muted grey (`{colors.muted-display}` — #B6B5B9), the second line pure white.

**Key Characteristics:**
- Deep violet-black canvas (`{colors.canvas}` — #0E0918) with a faint star-field overlay and white type. The system inverts nothing — no light-mode surface exists.
- Display headlines in Inter at **weight 400** with `-0.02em` tracking. Large size, not weight, creates the display feel.
- Two-tone two-line headlines (grey first line `{colors.muted-display}` → white second line) are the dominant section-header pattern and the strongest brand tell.
- Two signature gradients: **Fire** (`{gradients.fire}`) on the one primary action; **Cosmos** (`{gradients.cosmos}`) on secondaries and info surfaces. Used on objects, never as backgrounds.
- The **glass capsule nav** — a floating, `{rounded.xl}` capsule with `blur(24px)` backdrop, `rgba(255,255,255,0.05)` fill, and `rgba(255,255,255,0.20)` border — is the defining structural motif. Blur is reserved for things that float.
- Borders on dark surfaces are always `rgba(255,255,255,0.x)`, never a solid colour. This light-on-dark hairline is what gives the UI its "lit from above" feel.
- Generous vertical rhythm: `{spacing.48}` (192px) at hero, `{spacing.32}` (128px) between major sections, `{spacing.24}` (96px) between sub-sections; tight `{spacing.6}`/`{spacing.4}` inside cards.

## Colors

### Brand & Accent
- **Fire Start** (`{colors.fire-start}` — #FD8925): The warmer top stop of the primary CTA gradient and the spectral core of the lightning hero.
- **Fire End** (`{colors.fire-end}` — #FF0C00): The terminal bottom stop of the Fire gradient. Also `{colors.danger}`.
- **Cosmos Start** (`{colors.cosmos-start}` — #077AC7): Top stop of the secondary CTA gradient.
- **Cosmos End** (`{colors.cosmos-end}` — #6B21EF): Bottom stop of the Cosmos gradient.
- **n8n Pink** (`{colors.n8n-pink}` — #E41E5A): The brand pink — used on the logo mark, the `Hiring` tag, and the focus ring. The rarest accent; appears roughly once per page.
- **Violet Soft** (`{colors.violet-soft}` — #8F87F7): Tag and link tint on dark surfaces.

### Surface
- **Canvas** (`{colors.canvas}` — #0E0918): The default page floor across every surface. Deep violet-black.
- **Surface Card** (`{colors.surface-card}` — #1F192A): One step up from the field — cards, panels, side rails.
- **Surface Elevated** (`{colors.surface-elevated}` — #2A2633): Two steps up — hovered tiles, input fills.

### Hairlines & Borders
- **Hairline** (`{colors.hairline}` — rgba(255,255,255,0.08)): The default light-on-dark divider/border. Borders are *never* solid grey — translucent white is what reads as "lit."
- **Hairline Strong** (`{colors.hairline-strong}` — #3A3447): The opaque equivalent for stronger separators on dark surfaces.

### Text
- **On Dark / Body Strong** (`{colors.on-dark}` — #ffffff): Headlines, key numbers, and the second (white) line of two-tone headlines.
- **Body** (`{colors.body}` — #C1C8D5): Default running-text colour.
- **Muted** (`{colors.muted}` — #9D9797): Meta, labels, captions.
- **Muted Display** (`{colors.muted-display}` — #B6B5B9): The grey first line of a two-tone headline. A dedicated display tone, not a body grey.
- **Faint** (`{colors.faint}` — #6E6976): Disabled / faint only.

### Semantic (node canvas)
- **Success** (`{colors.success}` — #2FB67C): Successful node-execution highlight in the workflow editor.
- **Info** (`{colors.info}` — #36C5F1): Info node accent.
- **Warning** (`{colors.warning}` — #ECB22D): Warning chip.
- **Danger** (`{colors.danger}` — #FF0C00): Error states; shares the Fire terminal hex.

> Semantic node colours are **product-canvas only** — never apply success green or info cyan to marketing chrome.

## Typography

### Font Family
**Inter** is the single typeface across display, UI, and body. **JetBrains Mono** is reserved for code blocks, live star counts, and technical chips. The fallback stack walks `ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`.

The display look is achieved through **size + tight tracking at regular weight (400)**, not bold. Headings use `letter-spacing: -0.02em`; only `{typography.title-lg}` (h3) and below step up in weight (500/600) for UI legibility at smaller sizes.

### Hierarchy

| Token | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.hero}` | 60px | 400 | 1.04 | -0.02em | The one hero h1 at the top of a landing page |
| `{typography.display-lg}` | 45px | 400 | 1.07 | -0.02em | Section headers (the two-tone workhorse) |
| `{typography.display-md}` | 36px | 400 | 1.1 | -0.01em | Sub-section headers |
| `{typography.title-lg}` | 24px | 500 | 1.2 | -0.01em | Card titles, feature names |
| `{typography.title-md}` | 18px | 600 | 1.3 | 0 | Small headings, labels in UI |
| `{typography.body-md}` | 15px | 400 | 1.55 | 0 | Default body — colour `{colors.body}` |
| `{typography.meta}` | 13px | 400 | 1.4 | 0 | Labels, captions, tags — colour `{colors.muted}` |
| `{typography.button}` | 13px | 400 | 21px | 0 | All button labels — sentence case |
| `{typography.nav-link}` | 14px | 400 | 1.4 | 0 | Top-nav menu items, white @ ~70% opacity |
| `{typography.mono}` | 13px | 400 | 1.4 | 0 | Code, star counts, technical chips only |

### Principles
The display effect is **size, not weight** — heroes and section heads stay at regular (400). Bolding a hero reads as off-brand. Tight `-0.02em` tracking on large headlines does the optical work; body and meta sit at 0 tracking.

The **two-tone two-line headline** is the system's signature type pattern. Every major section header splits across two lines — the first muted grey, the second white — kept roughly parallel in length:

```
AI agents and workflows         ← grey  {colors.muted-display}
you can see and control         ← white {colors.on-dark}
```

Casing is **sentence case** everywhere (headings, buttons, nav) — the exception is title-cased single-word nav items (`Product`, `Pricing`, `Docs`). The brand name `n8n` is **always lowercase**, even at sentence start.

### Note on Font Substitutes
The Figma export uses Inter for everything. The live site may render a custom display face (Degular Display) at the very largest sizes — if the official brand kit is available, drop the `.woff2` files in `fonts/` and wire them in. Inter at 400 with `-0.02em` tracking is the canonical fallback.

## Layout

### Spacing System
- **Base unit:** 4px.
- **Tokens:** `{spacing.1}` 4 · `{spacing.2}` 8 · `{spacing.3}` 12 · `{spacing.4}` 16 · `{spacing.5}` 20 · `{spacing.6}` 24 · `{spacing.8}` 32 · `{spacing.10}` 40 · `{spacing.12}` 48 · `{spacing.16}` 64 · `{spacing.20}` 80 · `{spacing.24}` 96 · `{spacing.32}` 128 · `{spacing.40}` 160 · `{spacing.48}` 192.
- **Hero top padding:** `{spacing.48}` (192px).
- **Between major sections:** `{spacing.32}` (128px).
- **Between sub-sections:** `{spacing.24}` (96px).
- **Card internal padding:** `{spacing.6}` (24px) / `{spacing.4}` (16px).

### Grid & Container
- **Max content width:** ~1120–1200px centered on a 1920 viewport.
- **Feature & testimonial grids:** 2-up — `grid-template-columns: 1fr 1fr; gap: 24px`.
- **Integration tiles:** `56×56` rounded squares (`{rounded.lg}`) drifting in two staggered horizontal rows.
- **Always use flex/grid with `gap`** for any row of siblings (buttons, chips, tiles, nav) — never bare inline-block with margin hacks.

### Whitespace Philosophy
n8n trusts negative space and lets the dark field *be* the separator between sections. Generous outside, tight inside — the breathing room between bands is doing brand work. Where the brand adds atmosphere it's a single restrained aurora glow at a transition edge, never a full-bleed gradient wallpaper or repeating tile pattern.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| Flat | No shadow; light-on-dark hairline border only | Body sections, nav, footer, integration rows |
| Soft (`{elevation.md}`) | `0 4px 12px rgba(8,8,8,0.26)` + inset top highlight | Hovered tiles, small cards |
| Card (`{elevation.lg}`) | `0 16px 40px rgba(8,8,8,0.44)` + `inset 0 1px 0 rgba(255,255,255,0.06)` | Feature/testimonial cards |
| CTA (`{elevation.cta}`) | `0 8px 24px rgba(255,12,0,0.28)` warm glow + inset white | Primary Fire buttons only |
| Glow (`{elevation.glow}`) | `0 0 80px rgba(253,137,37,0.35)` | Hero illustration / signature moments |

The system uses **soft warm shadows** and never floats cards dramatically — the brand prefers flatness with a subtle inner highlight. The `inset 0 1px 0 rgba(255,255,255,0.06)` top-edge highlight (baked into `{elevation.lg}`/`{elevation.md}`) is what sells "lit from above." There are no light surfaces, so inner shadows for depth are never used.

### Decorative Depth
- **Aurora glow** (`{gradients.aurora}`): A soft orange→pink radial that bleeds up from the footer edge or a section transition. The only place the brand pink shows up on the page besides the footer logo. Used at most once per section.
- **Star-field**: A faint, low-opacity white-dot overlay on the violet-black field. Implied depth, never a foreground element.
- **Photo-real hero**: The lightning-bolt render (`assets/hero/hero-lightning.png`) with motion blur and chromatic aberration is the brand's signature visual — cinematic lighting does the elevation work that drop shadows would in a flat SaaS system.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.xs}` | 4px | Inputs and very small UI |
| `{rounded.sm}` | 6px | Small UI controls |
| `{rounded.md}` | 8px | **All buttons** + small cards — the default action radius |
| `{rounded.lg}` | 12px | Icon tiles, node tiles, integration tiles |
| `{rounded.xl}` | 16px | The glass capsule nav, medium cards |
| `{rounded.2xl}` | 24px | Large feature cards |
| `{rounded.3xl}` | 32px | Hero containers |
| `{rounded.pill}` | 999px | Pill tags |

The radius language is "generously rounded." Unlike a sharp-cornered brand, n8n leans into `12–24px` as the default and reserves `999px` for tags. Buttons live at `{rounded.md}` (8px) consistently.

### Photography Geometry
Hero photography fills full-width and bleeds into the page edge via protection gradients (`linear-gradient(0deg, #0E0918 5%, transparent 40%)`). App renders are dark-screen captures of the node canvas with nodes glowing — never bright, flat product shots. Avatars in testimonials are warm-toned, mid-tone portraits.

## Components

### Top Navigation

**`glass-capsule-nav`** — The defining structural motif. A floating `1360×58px` capsule with `{rounded.xl}` corners, `rgba(255,255,255,0.05)` fill, `rgba(255,255,255,0.20)` border, and `backdrop-filter: blur(24px)`. Sits ~8px from the top edge with 40px horizontal page margin. Carries the n8n logo at left, sentence-case nav items (white @ ~70% opacity) in `{typography.nav-link}`, a live GitHub star count with the octocat mark, and Fire/ghost CTAs at right. **Blur is reserved for things that float** — never sprinkled elsewhere.

### Buttons

**`button-primary`** — The signature Fire CTA. Background `{gradients.fire}`, white text, `{rounded.md}`, padding `0 20px`, height 40px, `{elevation.cta}` warm shadow. Type `{typography.button}` — sentence case, never uppercase. **One per view.** Hover brightens via an `rgba(255,255,255,0.08)` overlay; press scales to `0.98`; focus shows `{elevation.ring-focus}`.

**`button-secondary`** — The Cosmos CTA. Same geometry as primary but `{gradients.cosmos}` fill. Used for "Read case study", "Explore AI", "Browse all integrations". When two buttons sit side by side it's Fire + Cosmos — never Fire + Fire.

**`button-ghost`** — Transparent action over dark surfaces. `rgba(255,255,255,0.15)` fill, `rgba(255,255,255,0.20)` border, white text. Hover raises fill to `rgba(255,255,255,0.20)`.

**`button-small`** — 32px-tall compact variant with `5px 12px 6px` padding. Used in dense chrome.

### Cards & Containers

**`hero-band`** — Full-width canvas band carrying the photo-real lightning render and the hero h1 in `{typography.hero}` (60px / 400), set as a two-tone two-line headline. Top padding `{spacing.48}` (192px). No card frame — the photography and the field are the band.

**`feature-card`** — The consistent n8n card. Background `{colors.surface-card}`, `1px solid rgba(255,255,255,0.08)` border, `{rounded.2xl}`, padding 24px, `{elevation.lg}` (includes the inner top-edge highlight). Holds a `{typography.title-lg}` title and `{typography.body-md}` body. Flat, not floating.

**`node-tile`** / **`integration-tile`** — `56×56` rounded squares (`{rounded.lg}`) on `{colors.surface-card}`. Carry a branded integration logo, or a generic tile with the integration's first letter as fallback. Drift in two staggered rows in the "500+ integrations" band.

**`testimonial-card`** — 2-up grid card. `{colors.surface-card}`, hairline border, `{rounded.2xl}`, 24px padding. Carries a quote in `{typography.body-md}`, a warm-toned avatar, name, and role. The `I`/`you` voice rule: "I" only ever appears inside a quoted testimonial.

**`stat-pill`** — Social-proof pill carrying specific numbers (`4.9/5 on G2`, `200k+ community`, `Top 50 GitHub`). `rgba(255,255,255,0.05)` background, `{rounded.pill}`, `{typography.meta}`.

**`code-callout`** — The "Code when you need it" chip/block. `{colors.surface-card}`, `{rounded.lg}`, `{typography.mono}` body. The `</>` glyph is a real text composition, not an icon.

### Inputs & Forms

**`text-input`** — Standard input on dark surfaces. Background `{colors.surface-elevated}`, white text, `1px solid rgba(255,255,255,0.08)` border, `{rounded.md}`, `0 16px` padding, height 40px. Focus thickens the border toward white and may add `{elevation.ring-focus}`.

### Signature Components

**`pill-tag`** — `{rounded.pill}` tag with `{typography.meta}` text on a `rgba(255,255,255,0.05)` fill. The standard label chip.

**`hiring-tag`** — The rare exception that earns a solid `{colors.n8n-pink}` fill. The brand pink shows up here and on the footer logo — almost nowhere else.

### Footer

**`footer`** — Canvas-coloured footer closing every page. Background `{colors.canvas}`, body text `{colors.body}`, 64px padding. Often capped with the `{gradients.aurora}` glow bleeding up from the bottom edge — the one place brand pink appears in the page body. Carries the pink n8n logo mark.

## Do's and Don'ts

### Do
- Anchor every screen on the deep violet-black field (`{colors.canvas}`). Let negative space and the dark field separate sections — not heavy dividers.
- Make the biggest headline a **two-tone two-line** pattern: grey first line (`{colors.muted-display}`), white second line. Keep both lines roughly parallel in length.
- Keep display type at **regular weight (400)** with `-0.02em` tracking. The size creates the display feel, not the weight.
- Choose exactly **one** primary action per view and give it Fire (`{gradients.fire}`). Secondaries get Cosmos.
- Render borders as light-on-dark `rgba(255,255,255,0.x)`. This is what makes the UI read as "lit."
- Reserve `backdrop-filter: blur(24px)` for things that float — the nav capsule and modal headers.
- Use the 90/8/2 colour split: ~90% ink scale, ~8% one gradient per region, ~2% true accent (pink / a node status / aurora).

### Don't
- Don't introduce a light surface or light mode. There is none.
- Don't bold a hero or section head. Regular weight only — bolding reads as bombastic.
- Don't run two warm gradients competing in one eyeful, or use a gradient as full-page wallpaper. Gradients live on objects.
- Don't use solid grey borders, invent new greys, or use saturated whites. Borders are translucent white.
- Don't apply node-status colours (success green, info cyan) to marketing chrome — they're product-canvas only.
- Don't add emoji, exclamation points, Title Case buttons, or uppercase `N8N`. The name is always lowercase `n8n`.
- Don't hand-draw SVG illustrations or use bright flat product shots. App imagery is dark renders with glowing nodes; missing art uses a striped placeholder with a mono caption.
- Don't sprinkle blur outside floating elements — it kills the "this floats above the page" signal.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | Glass capsule collapses to a hamburger sheet; hero scales 60→~36px; 2-up grids stack 1-up; integration rows scroll horizontally |
| Tablet | 768–1024px | Capsule nav tightens; 2-up card grids hold; section padding eases toward `{spacing.24}` |
| Desktop | 1024–1440px | Full glass capsule nav; 2-up feature grids; content max ~1120px |
| Wide | > 1440px | Same as desktop centered within ~1200px max; more field around content |

### Touch Targets
- `{component.button-primary}` renders at 40px tall; bump to 44px minimum on touch surfaces.
- `{component.text-input}` height is 40px; raise to 44px on mobile forms.
- `{component.node-tile}` and `{component.integration-tile}` are 56×56 — comfortably above the 44px minimum.

### Collapsing Strategy
- The glass capsule collapses to a hamburger at < 768px; the menu opens as a full-screen dark overlay over the violet-black field.
- Hero photography crops responsively — wider crops at desktop, taller crops on mobile — and stays full-bleed via protection gradients.
- 2-up card grids reduce to 1-up rather than scaling cards down.
- The two-tone headline keeps its two-line structure at every breakpoint; only the font size scales.

### Image Behavior
- The lightning hero crops responsively and never letterboxes — it bleeds into the field via `{gradients.protect}`-style fades.
- Integration tiles retain their `56×56` size and scroll horizontally rather than shrinking on mobile.
- The aurora glow scales with viewport width and stays anchored to the bottom edge.

## Iteration Guide

1. Focus on ONE component at a time. Reference its YAML key (`{component.glass-capsule-nav}`, `{component.feature-card}`).
2. New buttons default to `{rounded.md}` (8px); cards to `{rounded.2xl}` (24px). Never invent a new radius outside the scale.
3. Variants (`-secondary`, `-ghost`, `-small`) live as separate entries in `components:`.
4. Use `{token.refs}` everywhere — never inline hex; reach for `{gradients.fire}` before hard-coding stops.
5. Default and focus/press states only — n8n's hover is a short `160ms ease-out` brighten, documented once here.
6. Display headlines stay regular-weight two-tone; body stays `{colors.body}` at 400. Never blur the contrast.
7. Fire is the one primary action; Cosmos is everything secondary. Never extend Fire to two buttons in one view.
8. When in doubt about emphasis: more negative space and a sharper headline before more colour.

## Known Gaps

- **Font Awesome → Lucide substitution.** The workflow editor uses Font Awesome Pro for chrome glyphs; this kit ships Lucide (CDN, 1.5px stroke, rounded caps) as the closest open match (~95% visual). Swap to Font Awesome and re-verify icon names if pixel parity with the product is required.
- **Display face.** The Figma export renders Inter for everything, but the live site may use a custom face (Degular Display) at the very largest headline sizes. Treat Inter 400 `-0.02em` as canonical until the official `.woff2` files are supplied.
- **Workflow editor** is reconstructed from public marketing illustrations and screenshots, not the open-source editor source. Node-data side panel and edge routing are best-effort approximations within a few pixels.
- **Integration tile icons** in the "500+ integrations" row are generic glyphs; the live site references hundreds of branded SVGs from `https://n8n.io/integrations/`.
- **Ambient background video** (`home-intro.mp4`) is not included; it's approximated with the hero still + aurora gradient + star-field.
- **Product motion** (node-execution flash, animated `stroke-dashoffset` wires, spring pan/zoom) is documented qualitatively only — exact timing curves are not extracted. Marketing motion is limited to `160ms ease-out` hovers and a slow looping ambient glow.
- **No slide template** was provided; deck/presentation tokens (slide scale, larger min type) are not defined here — scale hero ≥ 72px and body ≥ 24px when adapting to 1920×1080 slides.
