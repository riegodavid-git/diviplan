---
name: Luminous Equity
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#39393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#4de082'
  on-secondary: '#003919'
  secondary-container: '#00b55d'
  on-secondary-container: '#003e1c'
  tertiary: '#ffbbd9'
  on-tertiary: '#620040'
  tertiary-container: '#ff8fc6'
  on-tertiary-container: '#831258'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#6dfe9c'
  secondary-fixed-dim: '#4de082'
  on-secondary-fixed: '#00210c'
  on-secondary-fixed-variant: '#005227'
  tertiary-fixed: '#ffd8e7'
  tertiary-fixed-dim: '#ffafd3'
  on-tertiary-fixed: '#3d0026'
  on-tertiary-fixed-variant: '#85145a'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

This design system embodies a high-end, sophisticated financial atmosphere tailored for precision dividend planning. The aesthetic is a fusion of **Corporate Modern** and **Glassmorphism**, leaning into a "Dark Mode First" philosophy. It targets serious investors who value clarity, data density, and a premium digital experience. 

The visual narrative is built on the contrast between a deep, "obsidian" environment and vibrant, glowing data indicators. It evokes feelings of institutional security, technical mastery, and enlightened financial foresight. Soft backdrop blurs and subtle glass reflections provide depth without compromising the utilitarian nature of a professional dashboard.

## Colors

The palette is anchored by **Neutral Obsidian (#0F0F10)** to provide an infinite-depth background. Primary actions use a refined gold/mustard tone, while the functional "heart" of the system relies on high-chroma semantic colors:

- **Primary (Gold):** Used for branding and high-level portfolio milestones.
- **Success (Emerald):** A vibrant, glowing green for positive returns and dividend growth.
- **Alert (Pink/Red):** A soft but punchy pink-red for risk indicators and negative trends.
- **Surface:** A slightly lighter charcoal used for card containers to create separation through tonal layering.
- **Glow Effects:** All data colors should utilize a 15-20% opacity glow (drop-shadow) to simulate an emissive light source, as seen in the reference dashboard.

## Typography

The typography strategy balances high-end editorial feel with technical precision. 

- **Hanken Grotesk** is used for headlines and primary data points, offering a sharp, contemporary look that feels institutional yet fresh.
- **Inter** provides maximum legibility for body text, descriptions, and list items.
- **JetBrains Mono** is reserved for specific financial metrics, ticker symbols, and secondary data labels to emphasize a "data-first" technical precision.

Large numeric values should use tighter letter-spacing to feel more compact and impactful within cards. Use high-contrast white (#FFFFFF) for primary headers and muted grey (#9CA3AF) for secondary labels.

## Layout & Spacing

The system employs a **Fluid Grid** model with a maximum content width of 1440px. 

- **Desktop:** 12-column grid with 24px gutters. Dashboard modules should span 3, 4, 6, or 12 columns.
- **Tablet:** 8-column grid with 16px gutters. Sidebar navigation collapses into a bottom bar or hamburger menu.
- **Mobile:** 4-column grid with 16px margins. Cards stack vertically, and complex data charts should allow horizontal scrolling or simplified "sparkline" views.

Spacing follows a strict 4px/8px baseline rhythm to ensure mathematical harmony across dense data sets.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.

- **Level 0 (Background):** Solid Obsidian (#0F0F10).
- **Level 1 (Cards):** Surface color (#1A1A1C) with a subtle 1px inner border (white at 10% opacity) to simulate a glass edge.
- **Level 2 (Modals/Popovers):** Semi-transparent background with a 20px backdrop-filter blur. This allows the vibrant chart colors to bleed through softly when scrolling.
- **Glows:** Interactive elements and status indicators use an external glow (e.g., `0px 0px 12px rgba(74, 222, 128, 0.3)`) to signify activity or health.

## Shapes

The design system uses a **Rounded** shape language to soften the intensity of the dark theme and high-contrast colors. 

- **Cards & Containers:** 1rem (16px) radius to create a friendly, modern container for dense data.
- **Buttons & Inputs:** 0.5rem (8px) radius for a more precise, actionable feel.
- **Status Chips:** Full pill-shape (32px+) to distinguish them from actionable buttons.

## Components

### Buttons
- **Primary:** Solid Gold (#D4AF37) with dark text. No border.
- **Secondary:** Transparent with a 1px border of the primary color.
- **Ghost:** Minimal padding, white text, appearing only on hover with a subtle background tint.

### Cards
Cards are the core of the dashboard. They feature a 1px "glass" stroke at the top and left edges to catch the light. Inside, data is grouped logically with `label-mono` used for descriptors and `headline-lg` for primary values.

### Chips/Badges
Small, pill-shaped indicators for "Risks" or "Rewards." These should use a semi-transparent background of the semantic color (Success/Alert) with a solid-colored icon and text inside.

### Input Fields
Darker than the card surface (#0F0F10) with a 1px border that glows when focused. Use `jetbrainsMono` for numeric inputs to ensure digit alignment.

### Charts & Graphs
Line charts should use a "glow-path" — a 2px stroke with a 4px blur underneath in the same color. Area charts should use a vertical gradient from the semantic color at 30% opacity to 0% at the baseline.