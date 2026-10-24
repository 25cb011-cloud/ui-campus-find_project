---
name: Academic Trust Modern
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a1700'
  on-tertiary-container: '#b87500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system projects integrity, speed, and empathetic reliability for higher-education environments. It balances institutional authority with the approachable ease of modern consumer software.

- **Audience:** University students, campus police, student center staff, and university administrators.
- **Emotional Response:** Relief, trust, clarity, and social responsibility.
- **Aesthetic Direction:** Modern Utility with Soft Minimalism. The interface relies on generous white space, structured card grids, subtle delineation rather than aggressive borders, and pill-shaped interactive anchors to reduce stress during high-friction moments of item loss and recovery.

## Colors

The palette establishes an authoritative base with lively, clear status signaling.

- **Primary Canvas & Surfaces:** Background runs on soft off-white (`#F8FAFC`). Surfaces and elevated containers utilize pure white (`#FFFFFF`) with subtle structural borders (`#E2E8F0`).
- **Primary Navy:** `#0F172A` provides institutional grounding for text, primary headers, and high-priority action states; `#1E293B` serves as a softer alternative for secondary headings and deep interactive panels.
- **Teal Accent:** Vibrant teal (`#0D9488` default, `#14B8A6` interactive hover) anchors successful interactions, key verification triggers, and primary progress bars.
- **Status Ecosystem:**
  - **Lost Status:** Muted Rose/Amber pairing (`#BE123C` text on `#FFE4E6` background for urgent; `#B45309` text on `#FEF3C7` background for default review).
  - **Found Status:** Crisp Emerald/Teal pairing (`#0F766E` text on `#CCFBF1` background).
  - **Resolved / Archived:** Calm Slate (`#475569` text on `#F1F5F9` background).
- **Text Tiers:** Headlines and primary content resolve at `#0F172A`, supporting body copy at `#334155`, and metadata or captions at `#64748B`.

## Typography

The type hierarchy uses Inter across all levels to maintain systematic clarity and legibility at diverse screen scales.

- **Weight Discipline:** Restrict usage to weights 400 (Regular) for body and descriptive content, and 600 (Semi-Bold) or 700 (Bold) for headings, actions, and status badges.
- **Letter Spacing:** Headlines utilize tight negative tracking to create a modern editorial feel, while labels under 14px utilize slightly expanded tracking to preserve readability when rendered in upper or title case.
- **Contextual Line Heights:** Compact line heights are preserved on headlines to anchor card headers; open line heights (1.5–1.6x) are maintained on body levels to ensure scan-friendly parsing of item descriptions and physical identifiers.

## Layout & Spacing

The system implements a responsive 12-column fluid grid on desktop viewports, transitioning through an 8-column layout on tablet to a single-column stacked layout on mobile devices.

- **Breakpoints:**
  - `sm` (Mobile): &lt; 640px — 16px margins, 16px gutters, full-width feed cards. Minimum touch targets measure 48px vertically.
  - `md` (Tablet): 640px–1024px — 32px margins, 24px gutters, dual-column feed layout.
  - `lg` (Desktop): &gt; 1024px — max-width container capped at 1280px, 48px margins, 32px gutters, 3 to 4 column item grids.
- **Vertical Rhythm:** Interior card layouts maintain strict internal spacing via `space-md` (16px), separating media thumbnails, descriptive text, and metadata rows with absolute uniformity.

## Elevation & Depth

Visual depth is achieved through quiet layering rather than stark dropped shadows, preserving a light, non-distracting visual field.

- **Flat Surface Tier (Level 0):** Pure background canvas (`#F8FAFC`). No elevation, no border.
- **Card Tier (Level 1):** Main content cards and panels sit on pure `#FFFFFF`, bounded by a single-pixel border of `#E2E8F0` with an ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.02)`.
- **Interactive / Hover Tier (Level 2):** Applied when cards or floating filter pills receive focus or hover. The border shifts to `#CBD5E1`, with shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`.
- **Overlay Tier (Level 3):** Modal sheets, campus map overlays, and drop-down filters use: `0 20px 25px -5px rgba(15, 23, 42, 0.08), 0 8px 10px -6px rgba(15, 23, 42, 0.04)` with a subtle matching backdrop blur (`backdrop-blur-sm` over `rgba(15, 23, 42, 0.4)`).

## Shapes

The design system incorporates full pill-shaped radius tokens for actionable controls and soft geometric radiuses for content containers, creating an inviting, non-rigid campus utility.

- **Pills (`rounded-full`):** Reserved for buttons, search bars, filter chips, and status badges.
- **Cards & Visual Containers (`rounded-xl` / 1.5rem):** Standard for item inventory cards, report forms, and campus map frames.
- **Media Thumbnails (`rounded-lg` / 1rem):** Used for uploaded photos of recovered property within feed cards.
- **Form Controls (`rounded-lg` or Pill):** Text inputs adopt a modern soft-rectangle curvature (`rounded-lg` / 0.75rem to 1rem) to pair harmoniously with pill CTA buttons.

## Components

### Buttons
- **Primary:** Deep navy background (`#0F172A`), white text, pill shape, 48px height on touch devices, 40px on desktop. Hover: `#1E293B`.
- **Secondary Accent:** Teal background (`#0D9488`), white text, pill shape. Hover: `#14B8A6`.
- **Tertiary / Outline:** White background with `#E2E8F0` border, `#0F172A` text. Hover: `#F8FAFC` background with `#CBD5E1` border.
- **Ghost:** Transparent background, `#475569` text. Hover: `#F1F5F9`.

### Chips & Badges
- **Status Badges:** Compact pill-shaped containers using `label-sm` or `label-md`.
  - *Lost:* `#FFE4E6` background, `#BE123C` text, paired with a small solid red/amber indicator dot.
  - *Found:* `#CCFBF1` background, `#0F766E` text, paired with an emerald dot.
  - *Resolved:* `#F1F5F9` background, `#475569` text.
- **Filter Chips:** Pill shape with border `#E2E8F0`, `#334155` text. When selected: Navy `#0F172A` fill with white text, or Teal `#0D9488` fill with white text.

### Cards
- **Feed Item Cards:** Constructed from `#FFFFFF` with a 1px `#E2E8F0` border and Level 1 elevation. Includes an aspect-ratio-locked image slot with `rounded-lg` corners, title in `headline-sm`, metadata lines (location, timestamp) in `body-sm`, and an anchored pill badge in the top-right corner.
- **Card Hover:** Subtle elevation lift to Level 2 accompanied by a slight border transition to `#CBD5E1`.

### Input Fields
- **Search Bar:** Pill-shaped, 48px height, containing an inset search icon, `#F8FAFC` background resting state, shifting to `#FFFFFF` with a 1.5px `#0D9488` ring on focus.
- **Standard Text Fields:** `rounded-lg` (0.75rem), 1px `#E2E8F0` border, 14px padding. Label positioned in `label-sm` directly above with `#334155` coloration.

### Checkboxes & Radio Buttons
- **Radios:** Circular with teal (`#0D9488`) accent when active.
- **Checkboxes:** 20px boxes with 4px border radius. In active state, filled with `#0D9488` showing a sharp white checkmark.

### Additional Specialty Components
- **Campus Location Tag:** A small pill containing a geo-pin icon, campus building abbreviation (e.g., "LIB-2F"), rendered in `#F1F5F9` neutral slate for rapid contextual filtering.
- **Match Indicator Bar:** A thin dual-tone progress strip appearing on claimed items showing algorithmic match confidence between lost reports and found submissions.