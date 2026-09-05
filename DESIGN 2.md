---
name: Baroque Opulence
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4e4639'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#7f7667'
  outline-variant: '#d1c5b4'
  surface-tint: '#775a1b'
  primary: '#715516'
  on-primary: '#ffffff'
  primary-container: '#8c6d2d'
  on-primary-container: '#fff7ee'
  inverse-primary: '#e8c178'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#705524'
  on-tertiary: '#ffffff'
  tertiary-container: '#8b6d3a'
  on-tertiary-container: '#fff7ef'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea4'
  primary-fixed-dim: '#e8c178'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5c4203'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#ffdeab'
  tertiary-fixed-dim: '#e6c186'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5b4213'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: 0.08em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0.06em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0.06em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0.04em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0.03em
  body-lg:
    fontFamily: EB Garamond
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.015em
  body-md:
    fontFamily: EB Garamond
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0.01em
  body-sm:
    fontFamily: EB Garamond
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Playfair Display
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.15em
  label-md:
    fontFamily: Playfair Display
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.18em
  label-sm:
    fontFamily: EB Garamond
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  space-3xs: 0.125rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4.5rem
  space-4xl: 6rem
---

## Brand & Style

This design system draws inspiration from historic high-Victorian royal stationery, late Baroque copperplate engravings, and bespoke letterpress craftsmanship. It blends antique ceremonial grandeur with digital refinement, creating an ambiance of aristocratic heritage, timeless romance, and tactile indulgence.

The visual style is **Tactile & Skeuomorphic with Classical Editorial Discipline**. It relies on delicate linework, antique gilded accents, acanthus flourishes, and debossed or embossed paper physicalities. Symmetry, ornate framing, generous tracking in Roman display typography, and warm parchment surfaces form the foundational design grammar. The goal is to evoke the ceremonial intimacy and gravitas of receiving a hand-embossed royal decree or heirloom invitation.

## Colors

The palette reproduces the tactile warmth of heavy archival cotton paper, illuminated by antique burnished gold and deep sepia ink tones.

- **Parchment Ivory & Creams (`#FDFBF7`, `#F7F2E7`, `#EDE4CE`):** The primary canvas layers. These tones simulate time-seasoned vellum and fine cotton rag paper, eliminating harsh optical whites.
- **Burnished Antique Gold (`#C5A059`):** Used for filigree borders, foil stamped emblems, divider flourishes, and interactive state focus highlights.
- **Deep Metallic Bronze (`#8C6D2D`):** Primary actionable tone and prominent heading color, reflecting pressed metallic pigment.
- **Aged Umber & Sepia Bronze (`#5C4314`, `#2E220C`):** High-contrast typographic ink values for long-form prose and formal body copy, grounding the layout with engraved depth.

## Typography

Typography acts as both narrative prose and architectural ornament.

- **Display & Headlines (Playfair Display):** Provides theatrical contrast between hairline serifs and thick vertical stems, referencing 18th-century copperplate titles. Headlines are paired with generous tracking (0.04em to 0.15em) and are often rendered in small caps or Roman uppercase for crest headers.
- **Editorial Body (EB Garamond):** Classical French Old-style serif optimized for immersive editorial reading. It holds generous line heights to preserve the breath and cadence of ceremonial announcements.
- **Accents & Labels:** Micro-copy, metadata, and badges leverage tracked uppercase serifs with subtle letterpress debossing effects (`text-shadow: 0 1px 0 rgba(255, 255, 255, 0.7)`).

## Layout & Spacing

The layout model is anchored by **axial symmetry and fixed ornamental frames**. Rather than continuous full-bleed modular layouts, content is organized into self-contained cartouches, vellum cards, and bordered panels.

- **Desktop Framework:** A centralized 12-column grid constrained to a maximum width of `1140px` or `960px`, allowing deep outer margins (`space-4xl`) that simulate formal table linens or archival mats.
- **Parchment Framing Rhythm:** All primary surfaces feature concentric inner paddings (`space-2xl` to `space-3xl`) within nested ornamental borders, giving the text breathing room akin to royal proclamations.
- **Breakpoints:**
  - `Desktop (> 1024px)`: Centered bilateral layouts, dual column crests, generous ceremonial gutters (`space-xl`).
  - `Tablet (768px – 1023px)`: Fluid frame containment with scaled-down filigree borders, outer margin at `space-2xl`.
  - `Mobile (< 768px)`: Single vertical axis, simplified single-line gold ruling, reduced internal card padding (`space-md` to `space-lg`).

## Elevation & Depth

Elevation is tactile and tangible, rejecting modern synthetic drop shadows in favor of **letterpress debossing, gold leaf foil burnishing, and warm layered deckle edges**.

- **Level 0 (Parchment Foundation):** The base background (`#FDFBF7`) layered with an ultra-fine grain or paper tooth simulation.
- **Level 1 (Card & Suite Panels):** `#F7F2E7` parchment cards floating above the base. Depth is formed using dual-tone physical shadows: a soft contact shadow (`0 2px 4px rgba(92, 67, 20, 0.04)`) combined with an ambient amber-tinted spread (`0 12px 36px rgba(92, 67, 20, 0.08)`).
- **Embossing & Debossing:** Dividers, crests, and key interactive borders use an inset highlight shadow pair:
  - *Debossed / Letterpress (Text & Inset rules):* `box-shadow: inset 0 1px 2px rgba(46, 34, 12, 0.15), 0 1px 0 rgba(255, 255, 255, 0.8)`.
  - *Raised Foil (Seals, Crests, Emblems):* `box-shadow: 0 4px 12px rgba(140, 109, 45, 0.25), inset 0 1px 0 rgba(255, 255, 255, 0.6)`.
- **Borders as Structure:** Visual layers are delimited by concentric double-line borders: an outer 1px solid rule in `#C5A059` spaced 4px from an inner 0.5px hairline rule in `#8C6D2D`.

## Shapes

The shape system draws from traditional hand-cut cardstock and classical cartouche frames.

- **Corner Radii:** Set to a restrained soft level (`0.25rem` / `4px`). Sharp corners and slight bevels are favored over modern playful circles to reflect the precision of guillotined antique card stock.
- **Architectural Motifs:** Cards, modal dialogs, and hero containers utilize shaped header treatments: gentle Baroque arched tops, scalloped crown crests, or inverted corner notches (bracket corners) framing elaborate corner filigree ornaments.
- **Wax Seals & Medallions:** Interactive circular seals maintain pure round geometry (`rounded-full`), anchored by uneven cast-wax borders or scalloped edges.

## Components

### Buttons
- **Primary (Gilded Seal):** Deep bronze `#8C6D2D` to `#5C4314` subtle gradient background with a 1px solid `#C5A059` border, uppercase Playfair Display text tracked at 0.15em in ivory `#FDFBF7`. Features an inner 1px inset highlight for a pressed metallic plate effect.
- **Secondary (Engraved Parchment):** Ivory vellum background with a double hairline border in antique gold (`#C5A059`), text rendered in umber `#5C4314`. On hover, the border tone deepens and shifts with a subtle warm glow (`0 0 12px rgba(197, 160, 89, 0.3)`).

### Input Fields & Controls
- **Inputs:** Ivory cream surface (`#F7F2E7`) with a recessed bottom-line or thin enclosed hairline border in `#C5A059`. Typographic placeholders set in italicized EB Garamond. Active focus is signaled by a deepening bronze border and an ambient gold foil ring.
- **Checkboxes & Radios:** Ornate diamond or square cartouche frames with engraved gold filigree checkmarks. Radio buttons utilize circular medallion seals with centered gold wax dot indicators.

### Cards & Cartouches
- Central invitation cards feature multi-tiered framing: an outer antique gold border, a 4px gap showing the parchment ground, followed by an inner thin decorative frame capped by acanthus corner ornaments.
- Cards host a centered royal crest or monogram seal at the top apex, anchoring the bilateral text symmetry below.

### Dividers & Flourishes
- Dividers replace standard flat horizontal rules with engraved flourishes: a central fleur-de-lis, botanical acanthus knot, or diamond cartouche tapering into delicate hairline rules on either flank.

### Chips & Badges
- Slender parchment ribbons with swallowtail or bracket ends, bounded by a 1px border in `#C5A059`, containing tracked small-cap typography.