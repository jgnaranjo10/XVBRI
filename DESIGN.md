---
name: The Design System
colors:
  surface: '#fff9ef'
  surface-dim: '#e1d9c7'
  surface-bright: '#fff9ef'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf3e0'
  surface-container: '#f6edda'
  surface-container-high: '#f0e7d5'
  surface-container-highest: '#eae2cf'
  on-surface: '#1f1b10'
  on-surface-variant: '#4d4732'
  inverse-surface: '#343024'
  inverse-on-surface: '#f9f0dd'
  outline: '#7e775f'
  outline-variant: '#d0c6ab'
  surface-tint: '#705d00'
  primary: '#705d00'
  on-primary: '#ffffff'
  primary-container: '#ffd700'
  on-primary-container: '#705e00'
  inverse-primary: '#e9c400'
  secondary: '#006d36'
  on-secondary: '#ffffff'
  secondary-container: '#83fba5'
  on-secondary-container: '#00743a'
  tertiary: '#00696f'
  on-tertiary: '#ffffff'
  tertiary-container: '#00f1ff'
  on-tertiary-container: '#006a70'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe16d'
  primary-fixed-dim: '#e9c400'
  on-primary-fixed: '#221b00'
  on-primary-fixed-variant: '#544600'
  secondary-fixed: '#83fba5'
  secondary-fixed-dim: '#66dd8b'
  on-secondary-fixed: '#00210c'
  on-secondary-fixed-variant: '#005227'
  tertiary-fixed: '#79f5ff'
  tertiary-fixed-dim: '#00dbe8'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#fff9ef'
  on-background: '#1f1b10'
  surface-variant: '#eae2cf'
typography:
  display-lg:
    fontFamily: notoSerif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: notoSerif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-rt:
    fontFamily: notoSerif
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  callout-it:
    fontFamily: notoSerif
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.5'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 32px
  element-gap: 16px
  section-margin: 64px
---

## Brand & Style

This design system is built upon the concept of "Enchanted Modernism." It aims to evoke a sense of wonder, optimism, and high-end whimsy, catering to audiences who value storytelling and premium craftsmanship. The personality is radiant and welcoming, avoiding the darkness of traditional folklore in favor of a bright, midday-forest aesthetic.

The visual style is a hybrid of **Glassmorphism** and **Tactile** design. It utilizes translucent, airy surfaces that seem to float over rich, textured backgrounds. The interface should feel as though it is illuminated from within, using soft glows and subtle particle effects to suggest magic without compromising the clarity of a high-end digital experience.

## Colors

The palette is anchored by **Radiant Gold**, used primarily for interactive elements and key brand moments to signify value and magic. **Vibrant Emerald Green** serves as the secondary color, providing a natural, lush contrast that grounds the golden highlights.

The background uses a **Soft Luminous Cream** (#FDFCF0), mimicking high-quality parchment. This is complemented by "Glow" tokens—low-opacity radial gradients of white and soft gold—that sit behind primary containers to create the "fairy dust" effect. Text is kept in a deep, warm charcoal to ensure legibility while maintaining the organic feel of the system.

## Typography

Typography in this design system follows a dual-pathway approach. **Noto Serif** is the cornerstone of the system, used for all storytelling elements, headlines, and body copy to provide an elegant, literary feel. For highlights and "magical" emphasis, the system utilizes the italic variants of Noto Serif to mimic calligraphic flourishes.

To maintain modern usability, **Plus Jakarta Sans** is used for functional UI labels, buttons, and navigation items. Its soft, rounded terminals complement the joyful aesthetic of the system while ensuring high scannability in dense interfaces.

## Layout & Spacing

The layout philosophy is based on a **Fluid Grid** with exaggerated white space to emphasize the "airy" quality of the brand. Containers are never cramped; they breathe with generous internal padding. 

A 12-column grid is standard for desktop, but elements frequently break the grid with subtle offsets or "floating" positions to simulate magic. Spacing follows an 8px rhythmic scale, but vertical margins between sections are intentionally oversized (64px+) to prevent the interface from feeling cluttered or "heavy."

## Elevation & Depth

Depth is achieved through **Ambient Shadows** and **Tonal Layers** rather than harsh black shadows. Surfaces use a "Golden Glow" shadow—a multi-layered stack of soft, diffused shadows tinted with #FFD700 at 10-15% opacity.

Higher elevation levels incorporate backdrop blurs (20px+) to create a frosted glass effect over the parchment backgrounds. This ensures that floating elements like modals or tooltips feel light and ephemeral. Sparkle particles should be placed at the highest Z-index, occasionally overlapping container boundaries to break the box-model visual constraint.

## Shapes

The shape language is consistently **Rounded**, avoiding all sharp corners to maintain a friendly and safe atmosphere. Standard components use a 0.5rem radius, while large feature cards and "Hero" sections utilize 1.5rem (rounded-xl) to feel soft and inviting. 

Buttons and decorative chips may occasionally use pill-shapes to add a playful, modern energy to the classic typography. Geometric shapes are often softened further with organic "blob" silhouettes in the background to reinforce the fairy tale theme.

## Components

### Buttons
Primary buttons are solid Radiant Gold with a slight inner glow on the top edge. Hover states should trigger a "sparkle" animation or an increase in the outer golden shadow. Secondary buttons use a fine Emerald Green border with a transparent, glass-blurred center.

### Cards & Containers
Cards are styled as "Parchment Panes"—light cream backgrounds with a subtle 1px border in a darker gold. They feature high-diffusion shadows to appear as if they are floating 10-20px above the base layer.

### Inputs & Forms
Input fields use a soft, inset shadow to look like they are pressed into the parchment. The focus state replaces the inset shadow with a Vibrant Emerald Green glow.

### Interactive "Magic" Elements
*   **Fairy Dust:** Subtle, animated SVG particles that follow the cursor or cluster around active buttons.
*   **Progress Bars:** Styled as growing vines or a trail of golden light.
*   **Tooltips:** High-blur glassmorphic bubbles with Noto Serif Italic text.