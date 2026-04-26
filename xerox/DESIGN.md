---
name: Romantic Tribute System
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#584141'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#8c7071'
  outline-variant: '#e0bfbf'
  surface-tint: '#af2b3e'
  primary: '#570013'
  on-primary: '#ffffff'
  primary-container: '#800020'
  on-primary-container: '#ff828a'
  inverse-primary: '#ffb3b5'
  secondary: '#7b5455'
  on-secondary: '#ffffff'
  secondary-container: '#fecbcb'
  on-secondary-container: '#7a5354'
  tertiary: '#60603e'
  on-tertiary: '#ffffff'
  tertiary-container: '#aead85'
  on-tertiary-container: '#414121'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b5'
  on-primary-fixed: '#40000b'
  on-primary-fixed-variant: '#8e0f28'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#ecbaba'
  on-secondary-fixed: '#2f1314'
  on-secondary-fixed-variant: '#613d3e'
  tertiary-fixed: '#e6e5b9'
  tertiary-fixed-dim: '#cac99f'
  on-tertiary-fixed: '#1d1d03'
  on-tertiary-fixed-variant: '#484828'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: notoSerif
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  h1:
    fontFamily: notoSerif
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  h2:
    fontFamily: notoSerif
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-personal:
    fontFamily: newsreader
    fontSize: 22px
    fontWeight: '400'
    lineHeight: '1.6'
  body-standard:
    fontFamily: newsreader
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  label-caps:
    fontFamily: notoSerif
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.15em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 4rem
  element-gap: 2rem
  section-margin: 8rem
  gutter: 24px
---

## Brand & Style

The core philosophy of this design system is "Digital Heirlooms." It is designed to evoke the tactile sensation of high-end stationery, velvet-lined jewelry boxes, and the soft glow of a candlelit room. The target audience is discerning individuals celebrating a significant milestone, requiring a UI that feels less like software and more like a curated experience.

The style is a sophisticated blend of **Minimalism** and **Glassmorphism**. We utilize expansive white space (in creamy tones) to let emotional content breathe, while employing frosted glass layers to create a sense of depth and mystery. Every interaction should feel intentional, quiet, and profoundly premium.

## Colors

The palette is anchored by a **Deep Ruby Red**, used sparingly for emphasis and "heart" elements. This is balanced by **Soft Rose Pink** used for subtle highlights and secondary surfaces. The foundation of the UI is **Creamy White** (Cream and Off-White), avoiding the clinical feel of pure hex white. 

Gradients are essential to this design system. Rather than flat fills, we use radial and linear washes to mimic the way light hits physical materials. The ruby gradient should be used for primary calls to action, while the rose wash provides a soft background texture for cards and containers.

## Typography

This design system utilizes **Noto Serif** for its structural elements and headlines, providing a timeless, authoritative foundation. For personal narratives, letters, and quotes, **Newsreader** is utilized—specifically in its italic variant—to serve as a high-end, literary substitute for script fonts.

To maintain the premium feel:
- **Headlines** should use tighter tracking and be set in the Ruby Red.
- **Personal Touches** (quotes/notes) should always be rendered in Newsreader Italic with generous line-height to mimic a handwritten letter.
- **Labels** should be set in small-caps with wide tracking to emulate luxury brand tagging.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy with oversized margins to create an "editorial" feel. Content should never feel cramped; we prioritize breathing room over information density.

A 12-column grid is used for the desktop experience, but key content—such as the birthday tribute letter—should be centered and restricted to the middle 6 or 8 columns to ensure readability and focus. Spacing follows an 8px rhythm, but we lean heavily into larger increments (32px, 48px, 64px) to emphasize the luxuriousness of the space.

## Elevation & Depth

Depth is achieved through **Glassmorphism** rather than traditional elevation scales. 

- **Layers:** Use backdrop filters (blur: 12px to 20px) on surfaces that sit above the background Rose Wash.
- **Shadows:** Instead of black shadows, use "Ambient Rose Shadows"—low opacity (#800020 at 5-10%) with a very large blur radius (40px+) and a slight vertical offset. This creates a soft, glowing lift.
- **Borders:** Every card and modal should feature a 1px "Silk Border"—a semi-transparent gradient that is slightly lighter than the surface it sits on, creating a shimmering, delicate edge.

## Shapes

In alignment with the "no harsh lines" directive, this design system uses **Roundedness Level 2**. 

Standard containers utilize a 0.5rem (8px) radius, while larger hero cards and "Letter" components should utilize `rounded-xl` (1.5rem/24px) to soften the presence of the content. Interactive elements like buttons should never have sharp corners; they are either moderately rounded or fully pill-shaped to maintain an inviting, organic aesthetic.

## Components

### Buttons
Primary buttons use the `ruby-glow` gradient with white Noto Serif text. Secondary buttons are "Ghost" style with a delicate Silk Border and Ruby text. All hover states should include a soft increase in the ambient shadow glow rather than a color change.

### Cards & Containers
The "Tribute Card" is the hero component. It features a Creamy White background at 85% opacity, a 20px backdrop blur, and a delicate Silk Border. Inside, content is centered with generous internal padding (min 40px).

### The "Letter" Component
A specialized component for long-form tributes. It uses a soft Rose Wash background, no borders, and utilizes the `body-personal` typography. It should feel like a physical sheet of high-quality vellum.

### Interactive Elements
- **Input Fields:** Minimalist lines with a soft rose bottom-border that glows ruby when focused.
- **Chips:** Soft rose backgrounds with ruby text, used for "Tags of Affection" or "Memory Categories."
- **Navigation:** Subtle, center-aligned text links with a slow-fade underline animation on hover.

### Media Treatment
All photos should have a slight 1px inner border and a very soft corner radius. Consider a subtle "sepia-rose" overlay on images to ensure they harmonize with the color palette.