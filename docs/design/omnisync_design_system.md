---
name: OmniSync Design System
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#424656'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#727687'
  outline-variant: '#c2c6d8'
  surface-tint: '#0054d6'
  primary: '#0050cb'
  on-primary: '#ffffff'
  primary-container: '#0066ff'
  on-primary-container: '#f8f7ff'
  inverse-primary: '#b3c5ff'
  secondary: '#545f73'
  on-secondary: '#ffffff'
  secondary-container: '#d5e0f8'
  on-secondary-container: '#586377'
  tertiary: '#4b5a70'
  on-tertiary: '#ffffff'
  tertiary-container: '#63738a'
  on-tertiary-container: '#f6f8ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#001849'
  on-primary-fixed-variant: '#003fa4'
  secondary-fixed: '#d8e3fb'
  secondary-fixed-dim: '#bcc7de'
  on-secondary-fixed: '#111c2d'
  on-secondary-fixed-variant: '#3c475a'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
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
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: '0'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style
The design system is rooted in **Modern Minimalism**, prioritizing clarity, precision, and a premium "Apple-style" aesthetic. It is engineered for an e-commerce aggregator where data density must be balanced with visual breathing room. The brand personality is professional and high-trust, utilizing expansive whitespace and high-quality typography to reduce cognitive load. 

The emotional response should be one of effortless efficiency. By stripping away unnecessary decorative elements, the system directs all focus toward product data and actionable insights. The style utilizes a "Surface-on-Surface" approach, where subtle shifts in background value and soft elevation create a sense of organized hierarchy.

## Colors
The palette is intentionally restrained to maintain a "clean" and "airy" atmosphere. 

- **Primary (Electric Blue):** Reserved exclusively for primary actions, active states, and critical wayfinding. It should be used sparingly to maintain its impact.
- **Surface & Background:** The foundation is Pure White (#FFFFFF) for interactive cards and containers, set against a Very Light Grey (#F8FAFC) canvas to provide soft contrast without the harshness of a pure white-on-white layout.
- **Typography:** Deep Charcoal (#1E293B) provides high-contrast legibility for headings, while Slate Grey (#64748B) reduces the visual weight of secondary body text and metadata.
- **Borders:** Low-contrast Slate (#E2E8F0) is used for structural definition where shadows are not appropriate.

## Typography
This design system utilizes **Inter** for its systematic, neutral, and highly legible qualities. The hierarchy is established through significant size stepping and weight shifts rather than color. 

- **Headlines:** Use Semi-Bold (600) or Bold (700) with slight negative letter-spacing to create a compact, premium feel. 
- **Body Text:** Standardized at 16px for optimal readability. Use "Body-sm" for metadata and secondary descriptions.
- **Labels:** Use Medium (500) or Semi-Bold (600) weights with increased tracking for all-caps or small-scale UI elements like category tags or button text.

## Layout & Spacing
The layout follows a **Fluid Grid** model with strict adherence to an 8px spacing rhythm. 

- **Desktop:** A 12-column grid with 24px gutters and a maximum container width of 1280px. Large 64px (xl) vertical spacing is used between major sections to maintain an "airy" feel.
- **Tablet:** 8-column grid with 16px gutters.
- **Mobile:** 4-column grid with 16px margins. Content should primarily stack vertically, utilizing full-width cards with 16px internal padding.
- **Alignment:** All elements must align to the baseline grid. Consistent internal padding (24px for cards) ensures a cohesive look across different content types.

## Elevation & Depth
Depth is conveyed through **Ambient Shadows** and **Tonal Layering**. 

- **Resting State:** Cards and primary containers use a soft, diffused shadow: `0px 10px 30px rgba(30, 41, 59, 0.04)`. This creates a subtle lift without appearing heavy.
- **Hover/Active State:** For interactive elements, elevation increases: `0px 20px 40px rgba(30, 41, 59, 0.08)`.
- **Flat Borders:** Use the #E2E8F0 border for secondary elements (like input fields or inactive chips) where shadow-based elevation would cause too much visual noise.
- **Background Blurs:** For navigation bars or overlays, use a background blur (20px) with a semi-transparent white fill (80% opacity) to maintain context.

## Shapes
The shape language is defined by **large, smooth radii** to soften the professional tone and align with a modern, friendly tech aesthetic.

- **Standard (8px):** Used for smaller components like checkboxes, small buttons, and tags.
- **Large (16px):** The default for cards, main action buttons, and input fields.
- **Extra Large (24px):** Reserved for featured hero sections or modal containers.
- **Full (Pill):** Used for specific search bars or "Status" indicators to differentiate them from functional buttons.

## Components
- **Buttons:** Primary buttons use the Electric Blue fill with white text and a 12px-16px corner radius. Secondary buttons should use a subtle grey ghost style or a border-only approach.
- **Cards:** Cards are the primary organizational unit. They must feature a white background, 16px corner radius, and the defined "Resting" ambient shadow. Internal padding is strictly 24px.
- **Input Fields:** Use a 1px border (#E2E8F0) and a subtle #F8FAFC background. On focus, the border transitions to Electric Blue with a faint blue outer glow.
- **Chips/Tags:** Used for filtering and categorization. They should be pill-shaped with a light grey background (#F1F5F9) and 14px "Label-md" typography.
- **Lists:** Clean, borderless list items separated by 1px horizontal dividers (#E2E8F0). Use generous vertical padding (16px) for high-trust readability.
- **Checkboxes & Radios:** Should be custom-styled with the 4px roundedness and Electric Blue active state to match the brand aesthetic.