---
name: Botanical Science Corporate
colors:
  surface: '#f7f9ff'
  surface-dim: '#cbdcef'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#edf4ff'
  surface-container: '#e3efff'
  surface-container-high: '#d9eafe'
  surface-container-highest: '#d3e4f8'
  on-surface: '#0c1d2b'
  on-surface-variant: '#45464e'
  inverse-surface: '#223241'
  inverse-on-surface: '#e8f2ff'
  outline: '#75777f'
  outline-variant: '#c5c6cf'
  surface-tint: '#505e83'
  primary: '#00020a'
  on-primary: '#ffffff'
  primary-container: '#0b1b3d'
  on-primary-container: '#7684ac'
  inverse-primary: '#b7c6f1'
  secondary: '#2f6954'
  on-secondary: '#ffffff'
  secondary-container: '#b0ecd2'
  on-secondary-container: '#346d58'
  tertiary: '#030200'
  on-tertiary: '#ffffff'
  tertiary-container: '#281a00'
  on-tertiary-container: '#a17f3c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b7c6f1'
  on-primary-fixed: '#0a1a3c'
  on-primary-fixed-variant: '#38466a'
  secondary-fixed: '#b3efd5'
  secondary-fixed-dim: '#98d3b9'
  on-secondary-fixed: '#002116'
  on-secondary-fixed-variant: '#13503d'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#f7f9ff'
  on-background: '#0c1d2b'
  surface-variant: '#d3e4f8'
typography:
  display-xl:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 68px
  display-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-md:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
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
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the union of botanical natural purity and rigorous industrial chemistry. Tailored for enterprise B2B buyers, food technologists, cosmetic formulators, and pharmaceutical procurement teams, it blends scientific credibility with organic elegance.

The visual mood strikes an executive balance: prestigious, reliable, certified, and forward-thinking. It draws inspiration from **Corporate Modernism** with an **Editorial Heritage** accent. Structural interfaces utilize disciplined grid structures, generous white space, and sharp typographic hierarchies, softened by organic forest green tones, champagne gold borders, and warm alabaster porcelain surfaces.

## Colors

The palette establishes corporate authority through deep oceanic navy, grounded by botanical forest greens that signal high-purity natural extracts and food-grade safety.

- **Primary (`#0B1B3D`)**: Deep Maritime Navy. Anchors navigation headers, hero titles, primary interaction states, and prominent structural frames.
- **Secondary (`#0E4D3A`)**: Deep Botanical Green. Highlights certified ingredient badges, sustainability metrics, natural sourcing highlights, and secondary callouts.
- **Tertiary (`#C5A059`)**: Champagne Gold. Reserved for subtle hairline dividing rules, certification seal accents, premium category labels, and focused hover interactions.
- **Neutral (`#5B6B7C`)**: Slate Grey. Provides measured contrast for secondary body typography, input labels, disabled states, and fine architectural lines.
- **Surface Canvas (`#FBFBF9` / `#F4F6F4`)**: Alabaster and pale porcelain tints that soften pure white while maintaining scientific cleanliness.

## Typography

The typographic strategy pairs **Playfair Display**—reflecting legacy, corporate prestige, and editorial refinement—with **Inter**, a neutral, hyper-legible sans-serif engineered for specifications, technical datasheets, chemical tables, and enterprise workflows.

- **Editorial Headlines**: All `display` and `headline` levels utilize Playfair Display. They convey authority and heritage. Always maintain tight tracking for large display headers.
- **Operational Data & UI**: All `body`, `title`, and `label` roles leverage Inter. High-density data tables, chemical formulas, and batch numbers use tabular numbers for precise vertical scanning.
- **Micro-Copy & Eyebrows**: Uppercase label styles with elevated letter-spacing (`0.05em` to `0.08em`) are used for category tags, batch codes, and regulatory pill text.

## Layout & Spacing

A structured 12-column responsive layout anchors the desktop viewport, condensing to 8 columns on tablet and 4 columns on mobile. 

- **Outer Margins**: Desktop layouts observe generous 48px (`margin: 3rem`) gutters to provide breathability for dense technical catalogues and high-resolution ingredient photography. Mobile viewports compress margins to 16px (`1rem`).
- **Internal Rhythm**: Component spacing scales strictly along an 8-point vertical grid. Micro-elements like chips and small inputs use `space-xs` and `space-sm`, while catalogue listing cards use `space-lg` and `space-xl` for expansive separation between product imagery and specifications.

## Elevation & Depth

This system avoids aggressive, dark dropshadows, relying instead on **warm ambient diffusion** combined with **subtle metallic and hairline structural borders**.

- **Level 0 (Flat / Canvas)**: Sits directly on `#FBFBF9` or `#F4F6F4` backgrounds with no shadow. Structural dividers utilize a 1px border colored in `#E5E7EB` or semi-transparent gold `#C5A059` (18% opacity).
- **Level 1 (Card & Container Resting)**: Soft elevation featuring a dual shadow structure: `0 1px 3px rgba(11, 27, 61, 0.04), 0 6px 16px -4px rgba(11, 27, 61, 0.06)` combined with a 1px outline in `#EAEBE7`.
- **Level 2 (Active / Hover / Dropdown)**: Deepened ambient shadow: `0 12px 32px -6px rgba(11, 27, 61, 0.1), 0 4px 12px rgba(14, 77, 58, 0.04)`.
- **Accent Glow**: Focus rings and active highlight states apply a delicate 2px ring colored in `#C5A059` at 40% opacity, signalling gold leaf delicacy without visual noise.

## Shapes

The interface balances sharp industrial discipline with modern humanized curves using medium curvature (`roundedness: 2`).

- **Inputs, Buttons, and Badges**: Use standard `rounded` (0.5rem / 8px) to retain structural alignment with data fields and text inputs.
- **Product & Category Cards**: Utilize `rounded-xl` (1.5rem / 24px) to create framed vignettes reminiscent of high-end consumer packaged goods and ingredient packaging.
- **Status Pills and Badges**: Rendered in full pill-shape (`rounded-full`) to contrast against rectangular data grids.

## Components

### Buttons
- **Primary**: Deep Navy background (`#0B1B3D`), pure white text, Inter SemiBold. Subtle 1px gold border on hover (`#C5A059`). Height: 44px (Desktop).
- **Secondary (Botanical)**: Forest Green (`#0E4D3A`), white text, used for primary sustainability or formulation CTAs.
- **Tertiary / Outlined**: Transparent background, 1.5px solid Navy or Gold border, navy text. Hover fills with 4% Navy or Gold tint.

### Product & Chemical Cards
- Structured with horizontal or vertical layouts. Enclosed in `rounded-xl` frames with 1px border (`#E5E9E7`).
- Features a split presentation: high-resolution ingredient photography on one flank, backed by an alabaster surface (`#FBFBF9`), paired with a Playfair Display product title, chemical CAS numbers in monospaced/Inter labels, and botanical certification badges.
- Includes a subtle warm gold accent bar (2px height) under category headers.

### Badges & Chips
- **Certification Badges** (USP Grade, Non-GMO, Organic): Pill-shaped (`rounded-full`), padded `0.25rem 0.75rem`. Pale botanical background (`rgba(14, 77, 58, 0.08)`), rich green text (`#0E4D3A`), and 1px border (`rgba(14, 77, 58, 0.2)`).
- **Grade Chips**: Pale navy background with gold border accent for premium purity rankings.

### Input Fields
- Solid crisp white background (`#FFFFFF`), 1px slate-grey border (`#D1D5DB`), `rounded` (8px).
- Focus state switches border to `#0B1B3D` with a subtle 3px outer halo in `#C5A059` (25% opacity).
- Labels are rendered in `label-md` Inter uppercase, slate grey.

### Tables & Datasheets
- Minimal horizontal hairline dividers (`#E5E7EB`). Headers in navy Inter SemiBold over a porcelain tint (`#F4F6F4`).
- Alternating subtle rows for readability when displaying complex chemical assay breakdowns, purity percentages, and packing specifications.