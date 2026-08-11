---
name: Obsidian Technical
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#918fa0'
  outline-variant: '#464554'
  surface-tint: '#c2c1ff'
  primary: '#c2c1ff'
  on-primary: '#1800a7'
  primary-container: '#5e5ce6'
  on-primary-container: '#f4f1ff'
  inverse-primary: '#4d4ad5'
  secondary: '#c6c6c8'
  on-secondary: '#2f3132'
  secondary-container: '#454749'
  on-secondary-container: '#b4b5b7'
  tertiary: '#c7c6cb'
  on-tertiary: '#2f3034'
  tertiary-container: '#6e6e73'
  on-tertiary-container: '#f3f2f7'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c2c1ff'
  on-primary-fixed: '#0c006b'
  on-primary-fixed-variant: '#332dbc'
  secondary-fixed: '#e2e2e4'
  secondary-fixed-dim: '#c6c6c8'
  on-secondary-fixed: '#1a1c1d'
  on-secondary-fixed-variant: '#454749'
  tertiary-fixed: '#e3e2e7'
  tertiary-fixed-dim: '#c7c6cb'
  on-tertiary-fixed: '#1a1b1f'
  on-tertiary-fixed-variant: '#46464b'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display:
    fontFamily: Geist
    fontSize: 72px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
  section-padding: 120px
---

## Brand & Style

This design system is engineered for high-end personal portfolios that bridge the gap between creative excellence and technical rigor. The personality is disciplined, premium, and quietly confident, favoring functional elegance over decorative excess.

The design style is **Modern Minimalist with Technical Accents**. It utilizes high-quality whitespace and a strict adherence to a grid to convey organization. Subtle glassmorphic layers provide a sense of depth and physical presence, while precise borders and monospaced typography introduce a "built-with-care" aesthetic. The emotional response should be one of trust, sophistication, and professional authority.

## Colors

The palette is anchored in a "Deep Obsidian" spectrum to ensure maximum contrast and visual comfort in dark environments.

- **Backgrounds**: The base is `#0A0A0A` (Obsidian), providing a true-black foundation. Elevated surfaces use `#121212` (Ink) to create subtle separation.
- **Typography**: Primary content uses `#F5F5F7` (Pearl) for high legibility. Secondary information and metadata utilize `#86868B` (Slate) to establish a clear visual hierarchy.
- **Accent**: `#5E5CE6` (Electric Indigo) is used sparingly for calls-to-action, status indicators, and interactive highlights.
- **Overlays**: Glassmorphic elements utilize a 60% opacity fill of the surface color combined with a background blur.

## Typography

Typography is the primary engine of this design system. It balances the editorial feel of **Geist** for large headings with the utilitarian precision of **Inter** for body text.

- **Display & Headings**: Use Geist with tight letter spacing for a compact, modern look. For hero statements, use the `display` role to command attention.
- **Body**: Inter is the workhorse for all long-form content, ensuring readability through generous line heights.
- **Technical Metadata**: Use JetBrains Mono for tags, dates, and technical specifications. This should always be in uppercase or sentence case with increased letter spacing to emphasize the technical nature of the work.

## Layout & Spacing

The layout follows a **Fixed-Fluid Hybrid** model. Content is contained within a 1200px maximum width on desktop, centered with fluid margins.

- **Grid**: A 12-column grid is used for desktop layouts, collapsing to 4 columns for mobile.
- **Rhythm**: All spacing is derived from an 8px base unit. Section-to-section transitions should feel expansive; use `section-padding` to give the portfolio items room to breathe.
- **Mobile Adaptivity**: On mobile, horizontal margins reduce to 20px and vertical stack spacing is halved to maintain momentum while scrolling.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Subtle Glassmorphism** rather than heavy shadows.

- **Level 0 (Base)**: `#0A0A0A`. The "canvas" of the portfolio.
- **Level 1 (Cards/Navigation)**: `#121212` with a 1px solid border of `rgba(255,255,255,0.1)`. 
- **Level 2 (Hover/Active)**: Elements "lift" using a subtle glow effect (box-shadow: `0 0 0 1px rgba(94, 92, 230, 0.3)`) and a background-color shift to a slightly lighter neutral.
- **Glass Effects**: Sticky navigation and floating modals must use `backdrop-filter: blur(20px)` and a semi-transparent fill to maintain a sense of context and luxury.

## Shapes

The shape language is "Soft-Technical." Elements use a small 4px (0.25rem) base radius to appear intentional and precise without being sharp or aggressive.

- **Buttons & Tags**: Use `rounded-lg` (8px) to provide a tactile feel.
- **Project Cards**: Use `rounded-xl` (12px) for larger surface areas.
- **Status Indicators**: Status dots and decorative pills should be fully rounded (circle/pill) to contrast against the structured grid.

## Components

### Interactive Project Cards
Cards feature a 1px border. On hover, the border color transitions to the primary accent color, and the background image/content undergoes a subtle scale (1.02x). Use a "Technical Tag" in the corner using the `label-mono` typography.

### Sticky Navigation
A minimal top-bar navigation with a blurred background. It includes a "Status Indicator"—a small pulsing dot in the accent color next to a "Available for work" label in monospaced font.

### Buttons
- **Primary**: Solid accent color with white text. No gradients.
- **Ghost**: Transparent background with a 1px border. On hover, fill with 10% opacity of the accent color.

### Timeline Elements
A vertical line (1px width) in `border_color_hex`. Events are marked by a small 8px circle. Dates and roles should be in monospaced typography, while descriptions use `body-md`.

### Input Fields
Dark backgrounds (`#0A0A0A`) with a subtle bottom border. On focus, the border animates to the full width in the accent color.