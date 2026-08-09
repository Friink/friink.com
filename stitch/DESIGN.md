---
name: Kinetic Calm
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#3c4a46'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#6b7a76'
  outline-variant: '#bacac5'
  surface-tint: '#006b5f'
  primary: '#006b5f'
  on-primary: '#ffffff'
  primary-container: '#2dd4bf'
  on-primary-container: '#00574d'
  inverse-primary: '#3cddc7'
  secondary: '#4648d4'
  on-secondary: '#ffffff'
  secondary-container: '#6063ee'
  on-secondary-container: '#fffbff'
  tertiary: '#55615f'
  on-tertiary: '#ffffff'
  tertiary-container: '#b4c1be'
  on-tertiary-container: '#434f4d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#62fae3'
  primary-fixed-dim: '#3cddc7'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005047'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#d8e5e2'
  tertiary-fixed-dim: '#bcc9c6'
  on-tertiary-fixed: '#121e1c'
  on-tertiary-fixed-variant: '#3d4947'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Nunito Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Nunito Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Nunito Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Nunito Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-padding-mobile: 20px
  container-padding-desktop: 40px
  gutter: 24px
  section-gap: 80px
---

## Brand & Style

This design system evolves the brand into a "Kinetic Calm" aesthetic—a blend of restorative wellness and active hydration. The target audience is the modern, health-conscious individual who views wellness as an active pursuit rather than a sedentary one. 

The design style is **Modern-Organic**, mixing the cleanliness of Corporate Modernism with the vibrant energy of a high-saturation palette. It uses soft, fluid surfaces and subtle glassmorphism to maintain a sense of lightness and breathability. The emotional response is one of "energized focus"—a UI that feels as refreshing as a cold drink on a clear day. We lean into high-quality whitespace to ensure that the more vibrant color accents feel intentional and supportive rather than chaotic.

## Colors

The palette shifts from muted earth tones to a vibrant, multi-color "Oasis" scheme. 

- **Primary (Electric Mint):** A highly saturated green-teal that serves as the core energetic driver for actions and highlights.
- **Secondary (Hydra Blue):** A soft but confident periwinkle blue used to provide depth and contrast against the primary green.
- **Tertiary (Frost):** A very light, cool-tinted surface color used for background containers to keep the UI feeling airy.
- **Neutral (Deep Slate):** Used for typography and structural grounding to ensure high readability.

Color should be applied kinetically: use gradients transitioning from Primary to Secondary for high-impact areas like hero buttons or progress indicators. Surfaces should remain largely neutral or Frost-tinted to allow these "kinetic" pops of color to shine.

## Typography

The design system utilizes **Nunito Sans** exclusively to maintain a friendly, approachable, and rounded character. 

To achieve the "Kinetic" feel, we employ tight letter-spacing and heavy weights (ExtraBold/Black) for display headings. Body text remains at a standard weight for maximum legibility. When using headings over colorful backgrounds, ensure the weight is sufficient to maintain contrast. Use "Label-sm" in all-caps for category headers or overline text to add a sense of professional structure to the playful font choice.

## Layout & Spacing

The layout follows a **Fluid Grid** model with generous internal padding to emphasize the "calm" aspect of the brand. 

- **Mobile:** 4-column grid with 20px margins.
- **Tablet:** 8-column grid with 32px margins.
- **Desktop:** 12-column grid with a max-width of 1280px and 40px margins.

Spacing follows an 8px rhythmic scale. Components should utilize "breathable" internal padding (minimum 16px) to avoid visual clutter. Section gaps are intentionally large to create a rhythmic "pulse" as the user scrolls, preventing the vibrant colors from feeling overwhelming by separating them with significant white space.

## Elevation & Depth

Depth is communicated through **Tonal Layers** and **Soft Ambient Shadows**. 

1.  **Base Layer:** The pure white or Frost background.
2.  **Surface Layer:** Cards and containers use a white fill with a very soft, diffused shadow (10% opacity of Hydra Blue) to make them appear as if they are floating on a thin layer of water.
3.  **Glass Layer:** For navigation bars or modal overlays, use a backdrop blur (12px) with a 60% translucent white fill. This maintains the "Kinetic" feel by allowing the vibrant background colors to peek through as the user moves through the app.
4.  **Interactive Layer:** Buttons and active states use a slight vertical offset shadow when hovered to mimic physical "pressability."

## Shapes

The shape language is consistently **Rounded**. 

The base radius of 0.5rem (8px) is applied to all standard inputs and small cards. Larger containers and sections use `rounded-xl` (1.5rem) to soften the overall interface. Interaction elements like buttons and chips should lean toward the `rounded-lg` or even full pill-shape where appropriate to reinforce the friendly, organic nature of the "Kinetic Calm" brand. Avoid sharp corners entirely to maintain the restorative emotional response.

## Components

- **Buttons:** Primary buttons use a linear gradient from Electric Mint to Hydra Blue. Text is white or Deep Slate depending on contrast accessibility. Ghost buttons use a 2px stroke of the Primary color.
- **Chips:** Used for hydration tags or mood settings. These should be pill-shaped with a light tint of the Primary color (10% opacity) and Deep Slate text.
- **Cards:** White backgrounds with `rounded-xl` corners and soft Hydra Blue shadows. Use color-coded top borders (2px) to categorize content.
- **Input Fields:** Soft grey backgrounds with a bottom-only 2px border that turns Electric Mint when focused.
- **Progress Indicators:** Fluid, wave-like animations for hydration tracking. Use the Electric Mint color with a subtle "shimmer" effect to imply movement and life.
- **Navigation:** Bottom navigation (mobile) uses high-blur glassmorphism with Electric Mint icons for active states.