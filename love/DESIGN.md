---
name: Velvet & Verse
colors:
  surface: '#fff8f7'
  surface-dim: '#f0d3d3'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0f0'
  surface-container: '#ffe9e8'
  surface-container-high: '#ffe1e1'
  surface-container-highest: '#f9dcdb'
  on-surface: '#271718'
  on-surface-variant: '#584141'
  inverse-surface: '#3e2c2c'
  inverse-on-surface: '#ffedec'
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
  background: '#fff8f7'
  on-background: '#271718'
  surface-variant: '#f9dcdb'
typography:
  headline-display:
    fontFamily: beVietnamPro
    fontSize: 64px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: beVietnamPro
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1.2'
  headline-md:
    fontFamily: beVietnamPro
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: notoSerif
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: notoSerif
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1100px
  gutter: 24px
  margin-edge: 40px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

This design system is built to facilitate a deeply personal digital tribute, prioritizing emotional resonance over utility. The brand personality is intimate, nostalgic, and sophisticated—evoking the feeling of a hand-written letter tucked inside a bouquet of roses. 

The aesthetic leans into a **refined Glassmorphism** blended with **Minimalism**. It uses soft, translucent layers to create a sense of depth and preciousness, while maintaining significant whitespace to let photographs and stories breathe. The visual language is intentionally "quiet," allowing the user’s personal memories to take center stage. Every interaction should feel like a gentle gesture, avoiding harsh transitions in favor of soft fades and meaningful reveals.

## Colors

The palette is rooted in the romance of a classic floral arrangement. 

- **Primary (Deep Burgundy):** Used for key headlines and meaningful calls to action. It represents depth of feeling and sophistication.
- **Secondary (Soft Rose Pink):** Used for decorative elements, subtle backgrounds, and accents. It provides warmth and a gentle, approachable energy.
- **Tertiary (Creamy White):** The primary canvas color. It is softer than pure white, providing a "paper-like" warmth that reduces eye strain and feels more heirloom than digital.
- **Neutral (Warm Charcoal):** Used for body text to ensure high readability while maintaining the warm temperature of the overall design.

Backgrounds should frequently utilize subtle gradients moving from Creamy White to a very faint Rose Pink to simulate natural lighting.

## Typography

The typography strategy relies on the tension between a contemporary, flowing script-like feel and a timeless literary serif.

- **Headings:** While the system uses *beVietnamPro* for technical implementation, it should be styled with thin weights and italicized properties where possible to mimic the fluid motion of a script. Headlines should be treated as art pieces—large, airy, and evocative.
- **Body:** *notoSerif* provides a classic, authoritative, yet warm reading experience. It is used for the storytelling elements, letters, and descriptions. Increased line height (1.6 - 1.7) is essential to evoke the feeling of a printed book.
- **Labels:** *plusJakartaSans* is used sparingly for functional UI elements (dates, metadata, buttons) to provide a clean, modern counterpoint to the more decorative fonts.

## Layout & Spacing

The layout follows a **Fixed Grid** model for editorial content to maintain a high-end magazine feel. Centralized columns are preferred for storytelling to keep the eye focused and the experience feeling "contained" and safe.

The spacing rhythm is generous. Avoid crowding elements; the design system relies on "breathable" margins to convey luxury and calm. Large vertical gaps (stack-lg) should be used between different chapters of the birthday tribute to signify a passage of time or a change in narrative tone.

## Elevation & Depth

Hierarchy is established through **Backdrop Blurs** and **Ambient Shadows**. 

Instead of traditional elevation, use "Tonal Envelopes." A card should feel like an vellum overlay—semi-transparent with a high-density background blur (20px - 30px) that allows the colors behind it to bleed through softly. 

Shadows must be extremely subtle, using the Deep Burgundy color at 5-8% opacity rather than black. This creates a "glow" effect rather than a heavy drop shadow. Borders should be minimal, appearing as 1px lines in a slightly darker shade of Rose Pink or as "ghost" borders that only appear on hover.

## Shapes

The shape language is organic and soft. Rigid corners are avoided to maintain the emotional warmth of the design.

Standard UI elements like cards and image containers use a 1rem (rounded-lg) radius. For buttons and interactive decorative elements, use the Pill-shaped (rounded-xl) style to mimic the softness of flower petals. Photographs, in particular, should occasionally use asymmetrical rounding or soft masks to break the digital "boxiness" of standard web layouts.

## Components

- **The Tribute Card:** The central component. It features a large background blur, a soft Rose Pink border, and uses a mix of the display font for the title and the serif for a preview of the story.
- **Action Buttons:** These are pill-shaped, using a Deep Burgundy fill with Creamy White text. On hover, the button should slightly expand (scale 1.02) with a soft glow effect.
- **Story Timeline:** A vertical 1px Burgundy line with Rose Pink circular nodes. Each node, when hovered, expands into a small thumbnail of a memory.
- **Image Frames:** Photographs should have a generous internal padding (12px-16px) of Creamy White, acting like a physical mat board in a picture frame.
- **Text Inputs:** Floating labels using *plusJakartaSans* with a simple 1px bottom-border that changes from Rose Pink to Deep Burgundy when focused.
- **Subtle Animations:** All components should enter the viewport with a "soft rise" (moveY: 20px to 0px) and a slow opacity fade-in (duration: 800ms) to simulate the turning of a page.