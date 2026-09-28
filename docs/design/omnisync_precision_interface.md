---
name: OmniSync Precision Interface
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c2c6d8'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#8c90a1'
  outline-variant: '#424656'
  surface-tint: '#b3c5ff'
  primary: '#b3c5ff'
  on-primary: '#002b75'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#0054d6'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb95f'
  on-tertiary: '#472a00'
  tertiary-container: '#a06500'
  on-tertiary-container: '#fff7f1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  data-tabular:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
  label-caps:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  container-max: 1440px
---

## Brand & Style
The design system is engineered for high-stakes financial environments where data density and clarity are paramount. The brand personality is authoritative, precise, and technologically advanced, targeting professional traders and financial analysts. 

The aesthetic blends **Modern Corporate** reliability with **Glassmorphism** accents. It utilizes a deep "Obsidian" foundation to reduce eye strain during long sessions, while employing translucent layers and subtle backdrop blurs to establish a sophisticated spatial hierarchy. The emotional response is one of controlled power—users should feel they are operating a high-performance instrument where every pixel serves a functional purpose.

## Colors
The palette is rooted in a deep-space navy (`#020617`) to provide a high-contrast backdrop for critical data points. 

- **Primary (Electric Blue):** Used for primary actions, focus states, and growth indicators.
- **Secondary (Emerald):** Reserved exclusively for profit, positive delta, and "Success" system states.
- **Tertiary (Soft Amber):** Used for warnings, pending states, and low-priority alerts.
- **Neutrals:** A range of Slate and Steel grays are used to categorize information hierarchy, with `#1E293B` serving as the standard border color for high-tech precision.

## Typography
This design system utilizes **Inter** for all UI and body text to ensure maximum readability at small sizes. For financial figures, ticker symbols, and timestamps, **JetBrains Mono** is employed to ensure character alignment in data-heavy tables, allowing users to scan vertical columns of numbers with ease.

Typography scaling is conservative to maintain high information density. Headers use a tighter letter-spacing to feel more "engineered" and impactful. All labels for data points use an uppercase style with increased tracking to differentiate metadata from primary content.

## Layout & Spacing
The layout follows a **Fluid Grid** model based on a 4px baseline shift. 

- **Desktop:** 12-column grid with 16px gutters. Sidebars are fixed at 240px to maximize the central data-dashboard area.
- **Tablet:** 8-column grid with 16px gutters.
- **Mobile:** 4-column grid with 16px margins.

The spacing rhythm is tight. Use `8px` (2 units) for related elements and `24px` (6 units) for section blocks. This "tight-but-aligned" approach emphasizes a professional, "tool-first" environment.

## Elevation & Depth
This design system uses a **Glassmorphism** approach to depth. 

- **Level 0 (Base):** Deepest navy background (`#020617`).
- **Level 1 (Cards/Panels):** Semi-transparent surface (`#0F172A` at 80% opacity) with a `1px` stroke in `#1E293B`. A `24px` backdrop blur (saturate 150%) is applied to differentiate the layer from the base.
- **Level 2 (Popovers/Modals):** Lighter surface with a soft, diffused glow shadow: `0 8px 32px 0 rgba(0, 0, 0, 0.4)`.
- **Level 3 (Active Interactors):** Elements being dragged or high-priority alerts use a Primary Color tinted shadow to suggest a "powered-on" state.

## Shapes
Shapes in the design system are "Soft" (`0.25rem` base radius). This maintains a professional, geometric rigor while avoiding the harshness of sharp 90-degree corners. 

Buttons and input fields share this radius. Smaller components like tooltips and tags use the `rounded-sm` (2px) variation to appear more precise and aligned with the monospaced data font.

## Components

### Buttons
- **Primary:** Solid Electric Blue with white text. On hover, a subtle inner glow (white at 10% opacity) increases the "active" feel.
- **Secondary/Ghost:** Transparent background with a 1px border of `#1E293B`. Text is Slate-200.
- **Tertiary:** Text-only with an underline appearing on hover.

### Data Tables
Tables are the core component. Use alternating row highlights (zebra striping) at very low opacity (2%). Headers are sticky and use the `label-caps` typography style. Profit/Loss columns must use the Secondary (Green) and Red (System Error) colors respectively.

### Input Fields
Dark backgrounds (`#020617`) with `#1E293B` borders. Upon focus, the border transitions to Primary Electric Blue with a `0 0 0 2px` outer ring at 20% opacity.

### Chips & Tags
Used for status and categories. They feature a desaturated background of their status color (e.g., Emerald at 10% opacity) with a high-contrast text color of the same hue.

### Real-Time Charts
Charts should use 2px line weights for stroke charts and subtle gradients for area charts. Grid lines within charts must be minimal, using `#1E293B` at 50% opacity.