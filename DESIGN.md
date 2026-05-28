---
name: Atelier de Casa
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#747878'
  outline-variant: '#c4c7c8'
  surface-tint: '#5d5f5f'
  primary: '#5d5f5f'
  on-primary: '#ffffff'
  primary-container: '#fafafa'
  on-primary-container: '#717373'
  inverse-primary: '#c6c6c7'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#8a5100'
  on-tertiary: '#ffffff'
  tertiary-container: '#fff9f7'
  on-tertiary-container: '#a76300'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2e2e2'
  primary-fixed-dim: '#c6c6c7'
  on-primary-fixed: '#1a1c1c'
  on-primary-fixed-variant: '#454747'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#ffb86f'
  on-tertiary-fixed: '#2c1600'
  on-tertiary-fixed-variant: '#693c00'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e3e2e2'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  button:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 24px
  section-gap: 160px
---

## Brand & Style

The design system is engineered for a luxury interior design studio catering to high-net-worth clientele. The brand personality is architectural, curated, and silent—allowing the photography of physical spaces to provide the primary visual narrative. 

The aesthetic is **Refined Minimalism**. It leverages heavy whitespace to create an "airy" feel, reminiscent of a high-end art gallery or a boutique architectural monograph. The emotional response is one of tranquility, precision, and exclusivity. By stripping away unnecessary UI ornamentation, the design system focuses on composition, rhythm, and the tactile quality of the digital interface.

## Colors

The palette is anchored by a high-key off-white (#FAFAFA), which serves as the primary canvas to prevent the "clinical" feel of pure hex white while maintaining maximum luminosity. 

- **Primary Canvas:** #FAFAFA. Used for page backgrounds and large structural containers.
- **Deep Contrast:** #262626 (Warm Charcoal). Used for primary typography, iconography, and high-depth UI elements to ensure legibility and a grounded, architectural feel.
- **Strategic Accent:** #FF9900 (Deep Orange-Gold). Reserved exclusively for interactive highlights, primary calls to action, and subtle brand signals. It must be used sparingly to maintain the minimalist integrity.
- **Subtle Neutral:** #737373. Employed for secondary metadata, borders, and placeholders to maintain a low-contrast hierarchy where necessary.

## Typography

This design system utilizes **Plus Jakarta Sans** across all levels to maintain a contemporary, geometric consistency. 

Typography is used as a structural element. **Display** and **Headline** levels use tight letter-spacing and bold weights to create impact against the vast whitespace. **Body** copy is set with generous line-heights (1.8x - 2.0x for long-form) to ensure a comfortable, premium reading experience. **Labels** are often set in uppercase with increased tracking to evoke the feel of architectural blueprints and luxury branding.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to ensure precise control over photographic compositions, transitioning to a fluid model for mobile devices. 

- **Grid:** A 12-column grid with wide 32px gutters to provide maximum breathing room between elements.
- **Sectioning:** Vertical spacing is aggressive. Use the `section-gap` (160px) to separate distinct content blocks, forcing the user to focus on one idea at a time.
- **Responsive behavior:** On mobile, margins reduce significantly, but vertical gaps remain generous to maintain the "airy" brand character. All imagery should maintain aspect ratios to prevent distortion of interior design details.

## Elevation & Depth

To maintain the minimalist aesthetic, this design system avoids traditional heavy shadows. Instead, it utilizes **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Strategy:** Use subtle shifts in background color (e.g., from #FAFAFA to a slightly cooler white or very light gray) to define hierarchy.
- **Outlines:** Use 1px solid borders in a very faint charcoal (#E5E5E5) for cards and input fields.
- **Floating Elements:** For the sticky navbar or floating action buttons, use an extremely diffused ambient shadow: `0 20px 40px rgba(0,0,0,0.04)`. The shadow should feel like a soft glow rather than a physical projection.
- **Interaction:** Depth is achieved through scale transforms (e.g., a 1.02x scale on card hover) rather than increasing shadow density.

## Shapes

The shape language is **Soft (0.25rem)**. 

Luxury interior design often balances hard architectural lines with soft organic furniture. This design system reflects that by using tight, disciplined corner radii. While primary buttons and cards use the soft radius, large-scale hero imagery should remain sharp (0px) to mimic the edges of a framed photograph or a window pane.

## Components

- **Sticky Navbar:** A high-blur glassmorphic background (`backdrop-filter: blur(20px)`) with a 1px bottom border in #E5E5E5. The logo is centered for desktop, with navigation links using the `label-caps` style.
- **Buttons:** Primary buttons are solid #262626 with #FAFAFA text. The "Deep Orange-Gold" is used exclusively for the most critical CTA (e.g., "Book Consultation"). Secondary buttons are outlined with 1px charcoal.
- **Modern Package Grids:** Use an asymmetrical grid layout. Feature packages in cards with large, high-resolution background images, with price and title overlays using high-contrast white typography.
- **Input Fields:** Minimalist under-line style or very thin 1px full-border. Focus states transition the border color to #FF9900.
- **Hero Sections:** High-impact, full-bleed imagery. Headlines should be placed with intentional asymmetry, often overlapping the image slightly to create a sense of depth and modern editorial flair.
- **Lists:** Clean, strictly aligned lists with 2px orange-gold bullet indicators or custom architectural icons.