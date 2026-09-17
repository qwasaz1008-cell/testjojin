---
name: Atelier Editorial
colors:
  surface: '#faf9f7'
  surface-dim: '#dadad8'
  surface-bright: '#faf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeec'
  surface-container-high: '#e9e8e6'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1b'
  on-surface-variant: '#47464b'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#77767b'
  outline-variant: '#c8c5cb'
  surface-tint: '#5f5e61'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1b1e'
  on-primary-container: '#858387'
  inverse-primary: '#c8c5ca'
  secondary: '#a0401c'
  on-secondary: '#ffffff'
  secondary-container: '#fe875d'
  on-secondary-container: '#722200'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1d1c15'
  on-tertiary-container: '#87837b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e1e6'
  primary-fixed-dim: '#c8c5ca'
  on-primary-fixed: '#1b1b1e'
  on-primary-fixed-variant: '#47464a'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59c'
  on-secondary-fixed: '#390c00'
  on-secondary-fixed-variant: '#802a05'
  tertiary-fixed: '#e7e2d7'
  tertiary-fixed-dim: '#cbc6bc'
  on-tertiary-fixed: '#1d1c15'
  on-tertiary-fixed-variant: '#49473f'
  background: '#faf9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e3e2e0'
typography:
  display-hero:
    fontFamily: Bodoni Moda
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Bodoni Moda
    fontSize: 38px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 34px
    letterSpacing: 0em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0em
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: 0em
  title-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Manrope
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 0.75rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

This design system channels high-fashion print editorial through a precise, digital interface. Inspired by luxury archival platforms and minimalist art journals, the aesthetic balances austere restraint with tactile warmth. It prioritizes generous negative space, deliberate typographic tension, and quiet, assured elegance.

- **Brand Personality**: Discerning, cerebral, tailored, cultured, effortless.
- **Target Audience**: Fashion-forward curators, stylists, and collectors who prioritize aesthetic integrity over commercial noise.
- **Visual Style**: Modern Editorial Luxury. High-contrast typography, warm monochromatic canvases, precise 1px architectural dividers, and subdued seasonal accenting.

## Colors

The color palette centers on a soft paper background and deep ink typography, deliberately avoiding sterile pure whites or harsh jet blacks.

- **Primary (`#18181B`)**: Architectural Charcoal. Applied to primary typography, core iconography, and dominant CTA buttons.
- **Secondary (`#D96B43`)**: Muted Terracotta. Reserved for curated highlights, AI confidence badges, active bookmark markers, and dynamic lookbook selections.
- **Tertiary (`#C7C2B8`)**: Sand Stone. Utilized for secondary text, subtle dividers, structural hair lines, and disabled states.
- **Neutral (`#F9F8F6`)**: Warm Alabaster Canvas. Serves as the primary surface across all responsive viewports, providing an editorial publication feel.
- **Surface Variant (`#E8E5DF`)**: Raw Canvas. Used for image backdrop fills, card containers, and active input backgrounds.

## Typography

The type system pairs the high-contrast elegance of **Bodoni Moda** with the structural geometry of **Manrope**.

- **Headlines & Display**: Bodoni Moda delivers a bespoke, editorial gravitas. Use standard font weights (400–500) to keep the serifs delicate and razor-sharp.
- **Body & Captions**: Manrope provides maximum readability for sizing recommendations, brand metadata, and AI styling rationales.
- **Labels & Micro-copy**: Render small labels in uppercase with wide letter-spacing (`0.08em` to `0.1em`) to mimic luxury garment tags and catalog numbering.

## Layout & Spacing

The layout relies on an asymmetric 12-column desktop grid and a high-density 4-column mobile grid.

- **Desktop (1024px+)**: 12 columns with generous `margin` (3rem) and dynamic `gutter` (1.5rem). Modules embrace varied aspect ratios (3:4 portrait for lookbooks, 1:1 for garment details).
- **Tablet (768px - 1023px)**: 8 columns with 2rem margins. Content drops complex multi-column layering to prioritize stacked editorial spreads.
- **Mobile (Below 768px)**: 4 columns with tight edge margins (1.25rem). Lookbook rails overflow via smooth horizontal snapping cards with 0.75rem gaps.

## Elevation & Depth

Visual hierarchy uses physical paper layering, hairline boundaries, and ambient illumination rather than dramatic drop shadows.

- **Layering Philosophy**: Flat surfaces stacked sequentially. Modals and floating sheets emerge as crisp physical panels over the neutral `#F9F8F6` base.
- **Outlines**: Fine borders (`1px solid #E8E5DF` or `rgba(24, 24, 27, 0.08)`) frame image cards, filter trays, and metadata boxes.
- **Floating Controls**: Floating navigation bars and pinned styling tools utilize high-density background filtration (`backdrop-filter: blur(16px)` with 85% opacity of `#F9F8F6`) accompanied by an ambient shadow: `0 8px 32px -4px rgba(24, 24, 27, 0.04)`.

## Shapes

The interface adopts a disciplined soft geometry (`roundedness: 1`). Radii are kept subtle to maintain an elevated, architectural look rather than an overly bubbly app aesthetic.

- **Base Components (Inputs, Chips, Small Buttons)**: `4px` (`0.25rem`).
- **Cards & Visual Containers**: `8px` (`0.5rem`).
- **Overlays, Drawers & Modals**: `12px` (`0.75rem`).
- **Circular Indicators (Avatars, Color Swatches)**: Fully rounded (`9999px`).

## Components

### Buttons
- **Primary**: Solid Charcoal (`#18181B`) fill with Alabaster (`#F9F8F6`) text. Rectangular with soft 4px radius. Monospaced or uppercase tracking for labels. Hover state transitions gracefully to `#2A2A2A`.
- **Secondary / Ghost**: Transparent fill, 1px border (`#C7C2B8`), and `#18181B` typography. Hover transforms background to `#E8E5DF`.
- **Terracotta Accent**: Reserved for primary curation actions (e.g., "Style Me", "Accept Capsule"). Background `#D96B43` with pure off-white text.

### Lookbook Cards & Garment Tiles
- Ratio primarily constrained to 3:4 portrait.
- Background tone `#E8E5DF` provides a warm neutral base for cut-out photography.
- Encased in a discrete 1px border (`#E8E5DF`). Information below image includes: Designer (Label-SM in uppercase), Item Name (Body-MD), and Styling Match % badge.

### Chips & Filters
- Compact horizontal tags with 4px border radius.
- Inactive state: `#F9F8F6` background, 1px border `#E8E5DF`, text `#18181B`.
- Active state: `#18181B` fill, `#F9F8F6` text, no border.
- Category attribute counts displayed in subtle `#C7C2B8`.

### Form Controls (Inputs, Checkboxes, Radios)
- **Text Inputs**: Flat background `#F9F8F6`, bottom border only (1.5px `#C7C2B8`) transitioning to 1.5px `#18181B` on focus. No harsh focus rings.
- **Checkboxes & Radios**: Minimalist square and circle geometries. Unchecked: 1px border in `#C7C2B8`. Checked: `#18181B` fill with a white hairline mark.

### Curated AI Outfit Stack
- Modular card decks that allow vertical scrolling with sticky metadata pinning.
- Includes an AI rationale banner: subtle `#E8E5DF` tinted container featuring a `#D96B43` hairline accent and italicized editorial notes.