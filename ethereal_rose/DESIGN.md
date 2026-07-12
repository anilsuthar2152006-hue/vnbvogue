---
name: Ethereal Rose
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#564240'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#8a716f'
  outline-variant: '#ddc0bd'
  surface-tint: '#a23c36'
  primary: '#410002'
  on-primary: '#ffffff'
  primary-container: '#630d0d'
  on-primary-container: '#ec746a'
  inverse-primary: '#ffb4ac'
  secondary: '#7f5253'
  on-secondary: '#ffffff'
  secondary-container: '#fec3c3'
  on-secondary-container: '#7a4e4e'
  tertiary: '#1d1b18'
  on-tertiary: '#ffffff'
  tertiary-container: '#32302d'
  on-tertiary-container: '#9c9793'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ac'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#832521'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#f2b8b8'
  on-secondary-fixed: '#311113'
  on-secondary-fixed-variant: '#643b3c'
  tertiary-fixed: '#e7e1dd'
  tertiary-fixed-dim: '#cbc6c1'
  on-tertiary-fixed: '#1d1b19'
  on-tertiary-fixed-variant: '#494643'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter-mobile: 16px
  gutter-desktop: 32px
  margin-mobile: 20px
  margin-desktop: 80px
  max-width: 1280px
---

## Brand & Style
This design system embodies a "Modern Editorial Luxury" aesthetic. It is tailored for high-end beauty, wellness, and lifestyle products where the primary goal is to evoke feelings of serenity, indulgence, and timeless elegance. 

The visual style leverages a "Minimalist-Tactile" hybrid. It uses expansive whitespace and a refined color palette to create breathing room, while employing subtle tonal layering and serif-forward typography to provide a sense of physical, high-quality print media. The interface should feel intentional, quiet, and sophisticated, avoiding aggressive animations or loud UI patterns in favor of graceful transitions and a steady visual rhythm.

## Colors
The palette is rooted in organic, warm tones extracted from the reference imagery. 

- **Primary (Deep Burgundy):** Used for critical actions, key headings, and high-impact brand moments. It provides the necessary weight and authority to the design.
- **Secondary (Soft Rose):** Used for decorative elements, accents, and soft call-to-actions. It bridges the gap between the dark primary and the light background.
- **Background (Cream/Off-White):** The canvas of the design system. Avoid pure #FFFFFF; use the warm tertiary tone to maintain a soft, inviting feel.
- **Neutral:** A deep charcoal, rather than pure black, is used for body text to ensure legibility while maintaining the "soft-focus" sophistication of the overall brand.

## Typography
The typography strategy relies on a high-contrast pairing between a sophisticated Serif and a functional Geometric Sans.

- **Headlines:** Playfair Display is used for all headings. It brings a literary, editorial feel. Large displays should use a tighter letter-spacing for a "fashion-masthead" look.
- **Body & UI:** Manrope provides a clean, modern balance. Its generous x-height ensures readability even on textured backgrounds.
- **Labels:** Small labels and utility text use Manrope with increased letter-spacing and uppercase styling to create a clear hierarchy and a "premium label" aesthetic.

## Layout & Spacing
The design system utilizes a **Fixed Grid** model for desktop to maintain the editorial integrity of the layouts, transitioning to a fluid model for mobile.

- **Desktop (1440px+):** 12-column grid with 32px gutters and 80px side margins. Large amounts of vertical "breathing room" (section padding of 120px+) are encouraged to signify luxury.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px gutters and 20px margins.

Spacing follows an 8px base unit. Component-level spacing should be generous to avoid a cluttered, "utility-first" appearance.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Soft Ambient Shadows** rather than structural borders.

- **Surface Levels:** The base layer is the Cream (#F9F3EE). Raised elements (like cards) use pure White (#FFFFFF) to subtly lift off the page.
- **Shadows:** Use extremely diffused shadows with a slight warm tint (`rgba(99, 13, 13, 0.04)`). The blur radius should be high (20px+) with low offset to simulate natural, soft light.
- **Overlays:** Use a subtle backdrop blur (8px) on navigation bars or modals to maintain a sense of environmental continuity.

## Shapes
The shape language is "Soft-Modern." While we avoid aggressive "bubbly" curves, sharp 90-degree corners are too harsh for this brand. 

- **Primary Radius:** A 4px (0.25rem) radius is the standard for buttons and inputs, providing a hint of softness while maintaining a structural, professional look.
- **Large Radius:** Larger containers like cards or image frames may use 8px (0.5rem) to better frame photography.
- **Decorative:** Icons and brand marks may utilize circular containers to contrast against the rectangular grid.

## Components

- **Buttons:** Primary buttons are solid Burgundy (#630D0D) with white text. Secondary buttons use an "Outlined" style with a 1px border of the primary color. Buttons should have generous horizontal padding (32px+) to feel significant.
- **Input Fields:** Use a "minimalist underline" or a very subtle background tint (#F3ECE6) with no border. Focus states are indicated by a 1px Burgundy underline.
- **Cards:** Cards should be borderless, utilizing the tonal elevation (Pure White on Cream) and soft ambient shadows defined in Section 5.
- **Chips/Badges:** Use the Soft Rose (#D9A2A2) with the Primary Burgundy text for a low-contrast, harmonious look.
- **Navigation:** Top-level navigation is centered and uses the Label-MD typography style. Hover states involve a simple fade or a subtle 1px underline.
- **Imagery:** Photography is a core component. Images should have a consistent warm filter and should always be presented in either strict rectangular frames or elegant, oversized circular masks.