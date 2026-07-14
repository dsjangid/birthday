---
name: Linen & Lace
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4f4444'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#807474'
  outline-variant: '#d2c3c3'
  surface-tint: '#6e595a'
  primary: '#6e595a'
  on-primary: '#ffffff'
  primary-container: '#ebcfcf'
  on-primary-container: '#6c5757'
  inverse-primary: '#dbc0c0'
  secondary: '#6b5a5e'
  on-secondary: '#ffffff'
  secondary-container: '#f1dade'
  on-secondary-container: '#6f5e62'
  tertiary: '#844f59'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffc7d0'
  on-tertiary-container: '#814d57'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f8dcdc'
  primary-fixed-dim: '#dbc0c0'
  on-primary-fixed: '#271818'
  on-primary-fixed-variant: '#554242'
  secondary-fixed: '#f4dde1'
  secondary-fixed-dim: '#d7c1c5'
  on-secondary-fixed: '#25181b'
  on-secondary-fixed-variant: '#524346'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#f8b5c0'
  on-tertiary-fixed: '#350e18'
  on-tertiary-fixed-variant: '#693842'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  display:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 34px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-personal:
    fontFamily: Caveat
    fontSize: 22px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 24px
  gutter: 16px
  section-gap: 64px
---

## Brand & Style

The design system is centered on a "digital heirloom" aesthetic, blending the curated nature of a premium scrapbook with the effortless utility of a modern social platform. It targets an audience that values sentimental preservation and quiet elegance. 

The style is a sophisticated hybrid of **Minimalism** and **Tactile/Skeuomorphism**. It prioritizes vast amounts of whitespace (breathing room) to let individual memories shine, while utilizing subtle physical metaphors—like the texture of heavyweight paper and the translucency of vellum—to evoke a sense of touch. The emotional goal is to make the user feel as if they are unwrapping a gift or turning the pages of a high-end linen-bound photo album.

## Colors

The palette is anchored in warmth and soft contrast. 
- **Base Surface:** Warm Ivory (#FAF8F5) serves as the "tabletop" on which all content sits. 
- **Content Surface:** Pure White (#FFFFFF) is reserved for cards and "paper" elements to distinguish them from the background.
- **Accents:** Dusty Pink and Blush Rose provide soft highlights for interactive states and decorative elements, while Rosewood is used sparingly for thin dividers and emphasis to maintain a grounded, premium feel.
- **Typography:** Soft Black (#3E3E3E) ensures high legibility while avoiding the harshness of pure black, maintaining the "ink on paper" quality.

## Typography

This design system utilizes a three-font hierarchy to balance elegance, clarity, and personality.
- **Serif (EB Garamond):** Used for titles and expressive headings. It should be set with generous leading to feel airy.
- **Sans (Inter):** Used for functional UI text and longer body passages. It provides a clean, modern counterpoint to the more decorative fonts.
- **Script (Caveat):** Used for "handwritten" notes, captions, and the signature bow motifs. It should always appear at a slightly larger optical size than the body text to ensure readability.

## Layout & Spacing

The layout follows a **Fluid Grid** with fixed maximum widths for desktop to preserve the "album" feel. 
- **Desktop:** 12-column grid, 24px gutters, max-width 1200px.
- **Mobile:** 4-column grid, 16px gutters, 20px side margins.

The spacing rhythm is intentionally loose. Use "Section Gaps" (64px+) between different thematic content blocks to prevent the UI from feeling cluttered. Content should "float" on the Ivory background with generous internal padding within cards (minimum 24px).

## Elevation & Depth

Depth is conveyed through **Ambient Shadows** and **Tonal Layering**. 
- **Level 1 (Base):** Warm Ivory background with a subtle, non-repeating paper grain texture overlay (2% opacity).
- **Level 2 (Cards):** White surfaces with very soft, diffused shadows (Blur: 20px, Y: 4, Opacity: 4%, Color: #3E3E3E). 
- **Level 3 (Interactive):** Elements like active buttons or hovered cards lift slightly (Blur: 30px, Y: 8, Opacity: 6%).
- **Washi Tape:** Semi-transparent overlays (80% opacity) used to "pin" images to the background, featuring slightly irregular edges to mimic hand-torn paper.

## Shapes

The shape language is soft and organic. All containers use a minimum of 8px (0.5rem) corner radius. 
- **Polaroids:** Images should be nested in White cards with a larger bottom margin to mimic the classic Polaroid format.
- **Buttons:** Fully pill-shaped (rounded-xl) to emphasize the soft, "precious" nature of the interface.
- **Iconography:** Use light-weight (2pt) stroke icons with rounded terminals.

## Components

### Buttons
Primary buttons are pill-shaped, filled with Dusty Pink (#EBCFCF), using Soft Black text. Secondary buttons use a Rosewood outline (1px) or a text-only style with the Caveat font for a personal touch.

### Cards & Polaroids
The primary content container is the "Memory Card." It is White, rounded, and features a soft shadow. For a "scrapbook" feel, occasionally tilt cards by 1-2 degrees. Images within cards should have a "Washi Tape" accent—a small, rectangular Blush Rose (#F3DCE0) overlay at the top or corner.

### Inputs
Text fields are minimalist: a single Rosewood line at the bottom rather than a full box, with placeholder text in Caveat to mimic a "fill-in-the-blank" journal entry.

### Signature Motif: The Bow
A delicate, hand-drawn bow line-art (using the Caveat style) should be used as a divider or a decorative flourish at the end of sections. It serves as a visual "seal" of quality and care.

### Chips & Tags
Small, pill-shaped tags in Blush Rose with `label-caps` typography, used for categorizing memories (e.g., "MOMENTS", "CAKE", "WISHES").