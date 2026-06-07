---
name: Atelier Wusat
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1b1b'
  on-surface-variant: '#414847'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#717977'
  outline-variant: '#c0c8c6'
  surface-tint: '#3d6660'
  primary: '#002521'
  on-primary: '#ffffff'
  primary-container: '#103b36'
  on-primary-container: '#7ca59e'
  inverse-primary: '#a4cfc8'
  secondary: '#735a36'
  on-secondary: '#ffffff'
  secondary-container: '#fddaac'
  on-secondary-container: '#785e39'
  tertiary: '#221f18'
  on-tertiary: '#ffffff'
  tertiary-container: '#37342d'
  on-tertiary-container: '#a29c93'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c0ebe3'
  primary-fixed-dim: '#a4cfc8'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#254d48'
  secondary-fixed: '#ffddb0'
  secondary-fixed-dim: '#e2c195'
  on-secondary-fixed: '#281800'
  on-secondary-fixed-variant: '#594320'
  tertiary-fixed: '#e8e2d7'
  tertiary-fixed-dim: '#ccc6bb'
  on-tertiary-fixed: '#1e1b15'
  on-tertiary-fixed-variant: '#4a463e'
  background: '#fcf9f8'
  on-background: '#1b1b1b'
  surface-variant: '#e5e2e1'
  luxury-white: '#F8F6F2'
  soft-beige: '#EFE8DD'
  deep-emerald: '#103B36'
  champagne-gold: '#C8A97E'
  charcoal: '#1B1B1B'
  glass-fill: rgba(255, 255, 255, 0.4)
typography:
  display-xl:
    fontFamily: ebGaramond
    fontSize: 96px
    fontWeight: '400'
    lineHeight: 100px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: ebGaramond
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-md:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
  label-caps:
    fontFamily: inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
  label-md:
    fontFamily: inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
spacing:
  section-xp: 10rem
  section-lg: 8rem
  gutter: 2rem
  margin-edge: 4rem
  stack-xl: 4rem
  stack-md: 1.5rem
---

## Brand & Style
The design system embodies "Architectural Editorial"—a synthesis of high-end property publication aesthetics and cinematic digital interfaces. The personality is prestigious and exclusive, aimed at high-net-worth investors who value formal sophistication and structural clarity.

The visual direction utilizes a refined **Minimalism** blended with **Glassmorphism**. Layouts are treated like canvas spaces, prioritizing large-scale photography of architectural details over dense information. Interaction design is deliberate and smooth, mirroring the quiet confidence of a luxury physical gallery. The interface avoids standard "web" tropes in favor of an asymmetrical, intentional placement of elements that suggests bespoke craftsmanship.

## Colors
The palette is rooted in organic, high-end materials: stone, precious metal, and deep forest hues. 

- **Primary (Deep Emerald):** Used for primary calls to action, brand iconography, and high-impact structural elements. It provides the "weight" and "prestige" of the palette.
- **Secondary (Champagne Gold):** Reserved for delicate accents, interactive states, and thin borders. It signifies craftsmanship.
- **Background (Luxury White/Beige):** These warm neutrals replace clinical white to create a soft, gallery-like atmosphere.
- **Neutral (Rich Charcoal):** The exclusive color for all primary typography to maintain a soft but high-contrast legibility.

Avoid all default blue tones or synthetic gradients. Transparency should be used to create depth rather than color shifts.

## Typography
The typographic hierarchy is intentionally dramatic. **EB Garamond** (standing in for editorial serif requirements) is used for headlines to convey history and prestige. **Inter** provides a functional, modern counter-balance for body copy, ensuring the platform remains highly usable for investment data.

- **Display Levels:** Should be used sparingly for hero sections, often overlapping imagery or as semi-transparent watermarks.
- **Line Heights:** Body copy uses generous leading (line-height) to maintain the "airy" luxury feel.
- **Case Styling:** Use `label-caps` for eyebrows and category labels to add a structural, architectural quality to the page.

## Layout & Spacing
The layout follows a **12-column asymmetrical grid**. Unlike standard SaaS platforms, this design system encourages "off-axis" placement where content does not always start at column 1.

- **Whitespace:** Use `section-xp` (160px) or `section-lg` (128px) for vertical padding between major story blocks. This "wasteful" use of space is a signifier of luxury.
- **Breakpoints:**
  - **Desktop (1440px+):** 12 columns, 64px margins.
  - **Tablet (768px - 1024px):** 8 columns, 32px margins, reduced vertical spacing.
  - **Mobile (<768px):** 4 columns, 20px margins, stack all asymmetrical elements into a single vertical flow.
- **Alignment:** Captions and labels should often align with the inner edges of images rather than the global grid to create a "nested" architectural feel.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and subtle **Ambient Shadows** rather than traditional elevation tiers.

- **Surfaces:** Floating cards use a semi-transparent `glass-fill` background with a `backdrop-filter: blur(20px)`. 
- **Outlines:** Instead of heavy shadows, use 1px "Champagne Gold" borders at 20% opacity to define the edges of floating elements.
- **Shadows:** When used, shadows must be extremely soft and "long" (e.g., `0px 20px 50px rgba(0,0,0,0.03)`), suggesting a low-hanging sun and natural lighting.
- **Layers:** Use z-index layers to overlap text on images, creating a sense of physical stacking found in architectural blueprints and luxury magazines.

## Shapes
This design system uses a **Sharp (0px)** roundedness level. In luxury architecture, precision and straight lines denote structural integrity and modernism. 

All buttons, image containers, cards, and input fields must have perfectly square corners. The only exception is the "pill" style for small tags or specific interactive "magnetic" buttons to differentiate them from static structural elements.

## Components
- **Buttons:** Primary buttons are Sharp-edged, solid "Deep Emerald" with "Luxury White" text. Hover states trigger a subtle expansion of the "Champagne Gold" border. Magnetic interaction: buttons should slightly track the cursor position when within a 20px radius.
- **Input Fields:** Minimalist design with only a bottom border (1px). Focus state turns the border from "Soft Beige" to "Champagne Gold."
- **Cards:** Property cards should feature full-bleed imagery. Information overlays should appear as translucent glass panels that "slide" up on hover, revealing the property's financial metrics.
- **Navigation:** A persistent but ultra-thin top bar. Use a "hamburger" menu that opens a full-screen overlay with massive EB Garamond links to maintain the cinematic feel.
- **Chips/Labels:** Use the `label-caps` typography style. Backgrounds should be transparent with a 1px border.
- **Imagery:** All images must have a consistent "cinematic" grade—high contrast, warm highlights, and deep shadows. Black and white architectural photography is encouraged for secondary sections.