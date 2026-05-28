---
name: Equestrian Celebration
colors:
  surface: '#fff8f0'
  surface-dim: '#ffd655'
  surface-bright: '#fff8f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff2d8'
  surface-container: '#ffecbf'
  surface-container-high: '#ffe6a4'
  surface-container-highest: '#ffe087'
  on-surface: '#241a00'
  on-surface-variant: '#564149'
  inverse-surface: '#3c2f00'
  inverse-on-surface: '#ffefcc'
  outline: '#8a7079'
  outline-variant: '#ddbfc9'
  surface-tint: '#b01c72'
  primary: '#b01c72'
  on-primary: '#ffffff'
  primary-container: '#ff61b2'
  on-primary-container: '#680041'
  inverse-primary: '#ffafd0'
  secondary: '#7531d3'
  on-secondary: '#ffffff'
  secondary-container: '#8f4fed'
  on-secondary-container: '#fffbff'
  tertiary: '#00668a'
  on-tertiary: '#ffffff'
  tertiary-container: '#00a7e0'
  on-tertiary-container: '#00384d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd8e6'
  primary-fixed-dim: '#ffafd0'
  on-primary-fixed: '#3d0024'
  on-primary-fixed-variant: '#8c0058'
  secondary-fixed: '#ecdcff'
  secondary-fixed-dim: '#d6baff'
  on-secondary-fixed: '#280057'
  on-secondary-fixed-variant: '#5f07bc'
  tertiary-fixed: '#c3e8ff'
  tertiary-fixed-dim: '#7ad0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#fff8f0'
  on-background: '#241a00'
  surface-variant: '#ffe087'
typography:
  display-lg:
    fontFamily: Comfortaa
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Comfortaa
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.1'
  headline-lg:
    fontFamily: Comfortaa
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Comfortaa
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Quicksand
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1.6'
  label-md:
    fontFamily: Quicksand
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is a high-energy, immersive tribute to the spirit of friendship and magic. It captures the vibrant, whimsical essence of BronyCon 2026 by blending a **Tactile / Bubbly** aesthetic with modern **Glassmorphism**. The interface should feel alive, echoing the saturated palettes and soft, bouncy physics of contemporary animation.

The target audience ranges from long-time fans to new attendees, requiring an emotional response that is inclusive, optimistic, and celebratory. The style utilizes "squishy" UI metaphors, deep rounded corners, and a multi-layered depth system that suggests a world of magic just behind the glass. Sparkle accents and subtle gradient glows should be used as functional highlights to guide the user's attention.

## Colors

The palette is anchored by "Friendship Pink" and "Magic Purple," serving as the primary drivers of action and hierarchy. 

- **Primary (Pink):** Used for main CTAs, progress indicators, and celebratory highlights.
- **Secondary (Purple):** Used for navigation elements, secondary buttons, and depth-defining borders.
- **Tertiary (Sky Blue):** Utilized for information badges, links, and success states.
- **Neutral (Sunny Yellow):** Reserved for warnings, star ratings, and playful background accents.

Backgrounds should remain a very soft, warm off-white (`#FFF9FF`) to ensure the vibrant colors pop without causing visual fatigue.

## Typography

Typography focuses on approachable geometry. **Comfortaa** is used for all headlines to provide a distinctive, rounded "bubbly" feel that aligns with the brand's friendliness. **Quicksand** handles all functional body copy, maintaining the rounded aesthetic while offering superior legibility for schedules and descriptions.

For large display text, use tight tracking and slightly overlapping letterforms where possible to increase the "toy-box" feel. Use the Tertiary blue for inline links and the Primary pink for emphatic bolding within paragraphs.

## Layout & Spacing

The system follows a **Fluid Grid** model with high-volume internal padding. Layouts should never feel cramped; they should feel expansive and "airy."

- **Desktop:** 12-column grid with a max-width of 1440px. Use large 48px gutters to separate content blocks.
- **Mobile:** Single column with 16px side margins.
- **Spacing Rhythm:** All spacing should be multiples of 8px. Use `lg` (48px) spacing between major sections to allow the rounded container shapes to be clearly defined.
- **Z-Axis Spacing:** Use "floating" layouts where cards appear to drift over a dynamic, sparkling background rather than being locked into rigid vertical stacks.

## Elevation & Depth

This design system rejects flat design in favor of **Tonal Layers** and **Soft Ambient Shadows**. 

1.  **Surfaces:** Cards use a white background with a subtle 1px border colored in a 10% opacity version of the Primary pink.
2.  **Shadows:** Shadows are never black. Use high-blur, low-opacity shadows tinted with Magic Purple (`rgba(160, 97, 255, 0.15)`).
3.  **Glassmorphism:** Navigation bars and overlays should use a background blur (20px) with a semi-transparent white tint, giving the impression of frosted magic crystals.
4.  **Inner Glows:** Interactive elements like buttons should have a very soft white inner glow on the top edge to simulate a 3D "bubbly" volume.

## Shapes

The shape language is dominated by extreme roundedness. The default radius is **Pill-shaped**, creating a friendly, safe, and toy-like atmosphere. 

- **Containers:** All cards and sections should use at least a `rounded-2xl` (1.5rem) or `rounded-3xl` (2rem) radius.
- **Decorative Elements:** Use perfect circles for "sparkle" motifs and floating bubbles in the background. 
- **Active States:** When an element is pressed, it should visually "shrink" slightly (scale 0.98), reinforcing the tactile, squishy feel of the UI.

## Components

### Buttons & Chips
Buttons are "Bubbly." They feature a heavy bottom shadow (2px offset) that disappears on hover/click to simulate being pressed into a soft surface. Primary buttons use a gradient from Primary Pink to a slightly warmer magenta. Chips are always pill-shaped and use high-contrast text against a 10% opacity background of their respective category color.

### Input Fields
Inputs are rounded and use a thicker 2px border. On focus, the border transitions to Primary Pink and the field gains a soft outer glow. Use Quicksand for placeholder text to keep it friendly.

### Cards
Cards are the primary content container. They should feature a `2rem` corner radius and a soft, tinted purple shadow. For "Special Guest" or "Featured" cards, add a subtle animated "shimmer" effect or a gradient border.

### Checkboxes & Radios
These should be oversized and distinctly circular (even for checkboxes) to maintain the bubbly aesthetic. Use the Sky Blue tertiary color for the "checked" state.

### Sparkle Elements
A unique component for this system: "Sparkles." These are small, multi-pointed star vectors that can be placed at the corners of cards or near headings to signify importance or "magical" status.