---
name: Emerald & Gold Quinceañera
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#414944'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#717973'
  outline-variant: '#c0c9c2'
  surface-tint: '#396752'
  primary: '#002215'
  on-primary: '#ffffff'
  primary-container: '#043927'
  on-primary-container: '#73a48c'
  inverse-primary: '#a0d1b8'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#1b1d1d'
  on-tertiary: '#ffffff'
  tertiary-container: '#303232'
  on-tertiary-container: '#999a9a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bbeed3'
  primary-fixed-dim: '#a0d1b8'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#204f3c'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
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
  container-max: 1200px
  gutter: 24px
  section-padding: 80px
  element-gap: 16px
---

## Brand & Style

The design system is engineered to evoke the prestige of a high-end gala, specifically tailored for a milestone Quinceañera celebration. It targets an audience that values tradition, luxury, and meticulous detail. The emotional response is one of exclusivity, warmth, and "once-in-a-lifetime" importance.

The visual style is **Modern Minimalist with Tactile Accents**. It leans heavily into whitespace and sophisticated typography but incorporates physical metaphors like gold foil stamping and soft, multi-layered shadows to simulate the feel of premium stationery. Every interaction should feel intentional and graceful, utilizing smooth fade-in transitions to mirror the unfolding of a physical invitation.

## Colors

This design system utilizes a palette rooted in deep jewel tones and metallic highlights.

- **Primary (Deep Emerald):** Used for primary backgrounds, hero sections, and high-impact UI elements to establish a sense of depth and royalty.
- **Secondary (Shimmering Gold):** Reserved for accents, interactive states, borders, and decorative "foil" elements. It provides a luminous contrast against the emerald.
- **Tertiary (Soft White):** The primary canvas color. It is warmer than pure white to prevent a clinical feel, ensuring the design feels like expensive vellum or paper.
- **Neutral (Charcoal):** Used exclusively for body text and subtle borders to maintain high readability while appearing softer and more premium than pure black.

## Typography

The typographic hierarchy in this design system creates a dialogue between classic elegance and modern clarity. 

**Noto Serif** is the voice of the event, used for names, titles, and significant callouts. It should be typeset with generous leading to feel airy. **Manrope** provides a functional, refined contrast for logistical details (dates, RSVP instructions, and location). For labels and small metadata, use Manrope with increased letter spacing and uppercase styling to mimic the look of engraved descriptors on an invitation.

## Layout & Spacing

This design system employs a **Fixed Grid** model to maintain the proportions of a physical card. On desktop, content is centered within a generous container. On mobile, margins are increased to 24px to ensure the design feels framed rather than crowded.

The spacing rhythm is based on an 8px scale, but emphasizes "luxury through distance"—using larger-than-standard vertical gaps (Section Padding) to separate different phases of the invitation (e.g., The Invite, The Gallery, The Map).

## Elevation & Depth

Visual hierarchy is achieved through **Ambient Shadows** and **Tonal Layers**. 

Surfaces should feel like they are floating slightly above the background. Use extremely diffused shadows with a subtle Emerald tint (`rgba(4, 57, 39, 0.08)`) rather than gray. Gold foil elements should have a slight inner-bevel or a linear gradient (45 degrees) to simulate the way light hits a metallic surface. When a user interacts with a card, use a subtle "lift" effect—increasing the shadow blur while scaling the element by 1-2%.

## Shapes

The shape language of the design system is defined by **Large Radius Geometry**. Hard edges are avoided to maintain a soft, welcoming aesthetic. 

Primary containers and cards use `rounded-xl` (1.5rem) to evoke the feel of die-cut cardstock. Buttons and input fields use `rounded-lg` (1rem). Small decorative elements, like chips or photo frames, may use full pill-shaping to contrast against the more structural card layouts.

## Components

- **Primary Buttons:** Solid Emerald backgrounds with Gold text or Gold borders. On hover, a subtle gold outer-glow (foil effect) should appear.
- **RSVP Input Fields:** Soft White background with a 1px Charcoal border that transitions to Gold on focus. Use Manrope for input text.
- **Cards:** White surfaces with a delicate 1px Gold border. They should use the signature "floating" ambient shadow.
- **Chips/Badges:** Small, Emerald-tinted backgrounds with Gold Noto Serif text, used for tags like "Family Only" or "Black Tie."
- **Gold Foil Accents:** Horizontal rules (HRs) should be styled as 2px gold gradients that fade out at the edges.
- **Countdown Timer:** Large Noto Serif numbers in Gold, centered within an Emerald circular frame.
- **Photo Gallery:** Images should utilize the `rounded-xl` corners and a smooth fade-in-up animation upon scrolling into view.