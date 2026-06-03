---
name: PASHAN
colors:
  surface: '#fff8f5'
  surface-dim: '#f5d3c0'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff1ea'
  surface-container: '#ffeadf'
  surface-container-high: '#ffe3d3'
  surface-container-highest: '#fedcc8'
  on-surface: '#29170c'
  on-surface-variant: '#534439'
  inverse-surface: '#402c1f'
  inverse-on-surface: '#ffede4'
  outline: '#857467'
  outline-variant: '#d8c3b4'
  surface-tint: '#8c4f11'
  primary: '#894d0e'
  on-primary: '#ffffff'
  primary-container: '#a76526'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb77c'
  secondary: '#2a6958'
  on-secondary: '#ffffff'
  secondary-container: '#b0f0da'
  on-secondary-container: '#316f5e'
  tertiary: '#765700'
  on-tertiary: '#ffffff'
  tertiary-container: '#946f05'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc2'
  primary-fixed-dim: '#ffb77c'
  on-primary-fixed: '#2e1500'
  on-primary-fixed-variant: '#6d3900'
  secondary-fixed: '#b0f0da'
  secondary-fixed-dim: '#95d3be'
  on-secondary-fixed: '#002018'
  on-secondary-fixed-variant: '#0a5041'
  tertiary-fixed: '#ffdf9f'
  tertiary-fixed-dim: '#eec058'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5b4300'
  background: '#fff8f5'
  on-background: '#29170c'
  surface-variant: '#fedcc8'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: 0.04em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: 0.04em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: 0.04em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.3'
    letterSpacing: 0.02em
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.18em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system for this brand is rooted in the concept of *Sthapatya*—the ancient Indian science of architecture and proportion. It targets a discerning audience seeking authentic, sacred artifacts and gemstones. The visual language balances the weight of ancient stone with the ethereal quality of devotion.

The design style is **Modern Minimalist with Vedic influences**. It avoids excessive ornamentation in favor of precise "Flat" geometry, using high-quality typography and a sophisticated color palette to convey premium value. The emotional response should be one of deep trust, serenity, and timelessness. 

Key visual principles:
- **Sacred Geometry:** Alignment follows a strict grid, echoing temple floor plans.
- **Materiality:** Colors evoke earth (Pashan), water (Ganga), and metal (Copper).
- **Modernity:** Clean lines and subtle 0.5px borders ensure the brand feels contemporary and accessible, not dated.

## Colors
The palette is derived from the natural elements of Indian sacred sites.
- **The Earthly Foundation:** `Brown (Darkest)` is used for high-impact areas like the navigation bar and hero backgrounds to establish a sense of gravity.
- **The Divine Spark:** `Copper` serves as the primary action color, symbolizing the metallic elements used in ritualistic vessels.
- **The Living Water:** `Teal (Ganga Jal)` acts as a secondary accent for labels and eyebrows, providing a cooling contrast to the warm earth tones.
- **The Sanctuary:** `Cream` provides a breathable, paper-like background that allows product photography (the "Sacred Stones") to remain the focal point.

## Typography
The typographic hierarchy creates a dialogue between the editorial elegance of `Playfair Display` and the functional clarity of `Inter`. 

- **Headlines:** Must use the specified 0.04em letter-spacing to enhance the "luxury editorial" feel. They should be treated as architectural elements.
- **Body Text:** Rendered in `Muted Brown` to reduce visual vibration on the Cream background, ensuring a comfortable reading experience for long-form product storytelling.
- **Labels:** Small, uppercase, and widely tracked (0.18em). These are used for categories, eyebrows above headlines, and technical metadata.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to maintain the "contained" feel of a curated gallery, while transitioning to a fluid stacked system for mobile.

- **Desktop:** A 12-column grid with generous 64px side margins. 
- **Mobile:** A 4-column grid with 20px margins.
- **Rhythm:** An 8px base unit governs all spacing. Vertical rhythm is expansive, using large gaps (80px–120px) between sections to signify premium airiness.
- **Sticky Navbar:** The top navigation is fixed, using a `Darkest Brown` fill with `Copper` or `Cream` icons to maintain a permanent anchor of brand identity during the scroll.

## Elevation & Depth
In alignment with the "Sacred Stone" theme, the UI is predominantly flat and grounded. Depth is achieved through color blocking rather than shadows.

- **Flat Solid Fills:** Elements sit flush against the background. 
- **0.5px Borders:** Used to define boundaries for inputs and cards without adding bulk. Use `Copper` for active states and a subtle `Brown 2` for inactive states.
- **Subtle Hover:** Only product cards utilize a soft, high-diffusion shadow on hover to signify interactability. All other elements use color shifts (e.g., Copper to Light Copper).
- **Canvas Layer:** A background animation layer handles "Gem & Particle" effects, providing a 60fps sense of "life" behind the static, stone-like UI.

## Shapes
Shapes are disciplined and minimalist.
- **Base Corner Radius:** 4px for most UI components (buttons, input fields).
- **Large Components:** Product images and cards may use up to 8px for a slightly softer, more approachable feel.
- **Strictness:** Do not use fully rounded pill shapes. The geometry should remain "hewn," reflecting the namesake stone.

## Components
- **Buttons:** Solid `Copper` fill with `Cream` text for primary actions. 0.5px `Copper` border with no fill for secondary. No gradients. Hover state uses `Light Copper`.
- **Input Fields:** 0.5px `Brown 2` border on `Cream 2` background. Focused state shifts border to `Teal`. Labels always use the `label-caps` style above the field.
- **Product Cards:** `Cream 2` background with a 0.5px border. Images should have a slight "stone-gray" desaturation until hovered.
- **Chips/Labels:** Small `Teal 2` text with a 0.5px `Teal 2` border. No fill.
- **Ratings:** Stars are rendered in `Gold`, using a sharp, geometric vector style.
- **Lists:** Bullet points are replaced with small `Copper` squares (2px) to maintain the geometric architectural theme.