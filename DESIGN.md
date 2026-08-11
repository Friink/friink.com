---
name: Kinetic Calm
colors:
  surface: '#f8faf9'
  surface-dim: '#d8dada'
  surface-bright: '#f8faf9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f3'
  surface-container: '#eceeed'
  surface-container-high: '#e6e9e8'
  surface-container-highest: '#e1e3e2'
  on-surface: '#191c1c'
  on-surface-variant: '#3f4945'
  inverse-surface: '#2e3131'
  inverse-on-surface: '#eff1f0'
  outline: '#6f7975'
  outline-variant: '#bec9c4'
  surface-tint: '#0c6b59'
  primary: '#004c3f'
  on-primary: '#ffffff'
  primary-container: '#33aa55'
  on-primary-container: '#ffffff'
  inverse-primary: '#8ee39c'
  secondary: '#4b635c'
  on-secondary: '#ffffff'
  secondary-container: '#cbe5dc'
  on-secondary-container: '#4f6860'
  tertiary: '#6d3022'
  on-tertiary: '#ffffff'
  tertiary-container: '#8a4737'
  on-tertiary-container: '#ffc4b6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b5f2bc'
  primary-fixed-dim: '#8ee39c'
  on-primary-fixed: '#002108'
  on-primary-fixed-variant: '#0f5b24'
  secondary-fixed: '#cee8df'
  secondary-fixed-dim: '#b2ccc3'
  on-secondary-fixed: '#071f1a'
  on-secondary-fixed-variant: '#344b45'
  tertiary-fixed: '#ffdad2'
  tertiary-fixed-dim: '#ffb4a3'
  on-tertiary-fixed: '#3a0a02'
  on-tertiary-fixed-variant: '#723426'
  background: '#f8faf9'
  on-background: '#191c1c'
  surface-variant: '#e1e3e2'
typography:
  display-lg:
    fontFamily: Manrope
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter-md: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
The design system embodies a "Kinetic Calm" aesthetic—a sophisticated blend of high-end Swiss minimalism and soft organic tech. It is designed for professional environments that require high focus but want to avoid the cold sterility of traditional enterprise software.

The style leverages **Minimalism** with a touch of **Glassmorphism** for depth. It prioritizes clarity, generous whitespace, and a rhythmic sense of motion. The emotional goal is to feel precise yet breathing, reliable yet visionary. It avoids aggressive "growth-hack" visuals in favor of editorial-grade compositions that respect the user's cognitive load.

## Colors
The palette is centered around the fresh green #33aa55, which provides an energetic but grounded anchor for the Friink brand.

The website maps this brand color to the `primary` theme token. Light and dark modes both retain #33aa55 for actions, paired with dark text for accessible contrast.

- **Primary:** Used for key actions and brand presence.
- **Containers:** Lower-intensity versions of the primary color used for grouping related content or subtle background highlights.
- **Neutral:** A slightly "cool-mint" grey scale ensures that the neutral surfaces feel integrated with the primary brand color rather than being stark black or white.
- **Accessibility:** All "On" color tokens are calculated to ensure a minimum 4.5:1 contrast ratio against their respective backgrounds to meet WCAG AA standards.

## Typography
The typographic system utilizes **Manrope** for structural elements to provide a modern, balanced, and refined feel. **Hanken Grotesk** is used for body and functional text to ensure maximum legibility with a clean, contemporary edge.

Headlines should use tighter letter spacing to maintain a "locked-in" editorial look. Body text uses a generous 1.6x line height to promote readability in data-dense environments.

## Layout & Spacing
The design system employs a **Fluid Grid** model based on an 8px base unit (with a 4px half-step for fine-tuning). 

- **Desktop:** 12-column grid, 24px gutters, 64px side margins.
- **Tablet:** 8-column grid, 16px gutters, 32px side margins.
- **Mobile:** 4-column grid, 16px gutters, 16px side margins.

Horizontal spacing between unrelated components should favor 32px or 48px to preserve the "Calm" aesthetic, preventing the UI from feeling cluttered.

## Elevation & Depth
Depth is created through **Tonal Layers** and **Ambient Shadows**. Surfaces do not "float" in a void; they sit on logical tiers:

1.  **Level 0 (Base):** The `neutral_color` background.
2.  **Level 1 (Surface):** White cards with a very soft, diffused shadow (12% opacity of the primary-neutral tint).
3.  **Level 2 (Overlay):** Used for modals or menus, adding a 12px backdrop blur (glassmorphism) to maintain context of the underlying layer.

Avoid heavy black shadows. Shadows should always be tinted with a hint of the `primary_color` to ensure they feel like they belong to the environment.

## Shapes
The shape language is "Rounded." This softens the precision of the typography and creates a more approachable, human feel.

- **Standard Buttons & Inputs:** 0.5rem (8px).
- **Cards & Containers:** 1rem (16px).
- **Feature Banners:** 1.5rem (24px).

Interactive states (like hover) should never change the border radius, only the elevation or background fill.

## Components
- **Buttons:** Primary buttons use `primary_color` with `on_primary` text. Use high-horizontal padding (24px) to give them a premium, confident footprint.
- **Chips:** Small, pill-shaped markers using `primary_container` for the background and `on_primary_container` for the text.
- **Input Fields:** Use the `outline` token for borders. On focus, the border shifts to `primary_color` with a 2px thickness and a subtle outer glow.
- **Lists:** Clean rows separated by 1px `outline` at 20% opacity. Icons within lists should use `secondary_color` to avoid competing with primary actions.
- **Cards:** Utilize the `surface` token. Ensure padding within cards is at least 24px to maintain the spacious aesthetic.
- **Navigation:** Top navigation should use a semi-transparent `surface` with a backdrop blur to provide a sense of place as the user scrolls.