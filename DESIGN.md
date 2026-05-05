---
name: Timeless Grace
colors:
  surface: '#fff8f7'
  surface-dim: '#e2d8d7'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf1f1'
  surface-container: '#f6ebeb'
  surface-container-high: '#f0e6e5'
  surface-container-highest: '#eae0e0'
  on-surface: '#1f1a1b'
  on-surface-variant: '#4f4444'
  inverse-surface: '#342f2f'
  inverse-on-surface: '#f9eeee'
  outline: '#817474'
  outline-variant: '#d3c3c3'
  surface-tint: '#715859'
  primary: '#715859'
  on-primary: '#ffffff'
  primary-container: '#ebcbcb'
  on-primary-container: '#6c5455'
  inverse-primary: '#debfbf'
  secondary: '#615e57'
  on-secondary: '#ffffff'
  secondary-container: '#e7e2d8'
  on-secondary-container: '#67645c'
  tertiary: '#775a19'
  on-tertiary: '#ffffff'
  tertiary-container: '#f6cd81'
  on-tertiary-container: '#735615'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fcdbdb'
  primary-fixed-dim: '#debfbf'
  on-primary-fixed: '#281717'
  on-primary-fixed-variant: '#574142'
  secondary-fixed: '#e7e2d8'
  secondary-fixed-dim: '#cac6bd'
  on-secondary-fixed: '#1d1c16'
  on-secondary-fixed-variant: '#494740'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#e9c176'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4201'
  background: '#fff8f7'
  on-background: '#1f1a1b'
  surface-variant: '#eae0e0'
typography:
  display:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  section-padding: 80px
  element-gap: 16px
---

## Brand & Style

This design system is built upon the pillars of trust, femininity, and specialized care, reflecting a legacy of 25 years in high-end beauty. The aesthetic direction is **Warm Minimalism**—a style that prioritizes intentional whitespace and clarity while avoiding the coldness often associated with modernism. 

The visual language is designed to evoke a sense of sanctuary. It speaks to a discerning clientele who values experience and quiet luxury. By balancing structured layouts with soft, organic transitions and high-quality editorial imagery, the design system creates an atmosphere of professional intimacy and effortless elegance.

## Colors

The color palette is rooted in a sophisticated, tonal range that mimics natural skin tones and precious metals.

- **Primary (Soft Pink):** Used for key brand moments and subtle highlights. It represents femininity and the gentleness of care.
- **Secondary (Warm Beige):** The primary surface color for sections, providing a soft alternative to pure white to enhance the feeling of warmth.
- **Tertiary (Refined Gold):** Reserved for accents, interactive states, and luxury signifiers. It should be used sparingly to maintain its premium impact.
- **Neutral (Deep Taupe):** Used for typography and iconography to ensure high readability without the harshness of pure black.
- **White:** Used as the base "breathable" space to maintain the minimalist aesthetic.

## Typography

This design system utilizes a high-contrast typographic pairing to balance tradition with modern accessibility.

- **Headlines:** **Noto Serif** is chosen for its timeless, literary qualities. It conveys the authority and expertise of a 25-year legacy. Large display settings should use tighter letter-spacing for an editorial feel.
- **Body & UI:** **Plus Jakarta Sans** provides a clean, contemporary counterpoint. Its soft, slightly rounded terminals echo the feminine nature of the brand while ensuring exceptional legibility across digital interfaces.
- **Hierarchy:** Use the serif face for storytelling and section titles; use the sans-serif for functional information, navigation, and service descriptions.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop to maintain a boutique, curated feel, transitioning to a fluid model for mobile devices. 

A 12-column grid is used with generous gutters (24px) to allow content to breathe. Horizontal spacing between sections is intentionally large (80px+) to slow down the user's scroll and encourage a "spa-like" browsing pace. Content should be centered or asymmetrically balanced to mimic high-end fashion magazine layouts.

## Elevation & Depth

Hierarchy in this design system is achieved through **Ambient Shadows** and tonal layering rather than heavy borders or deep offsets.

- **Shadows:** Use very soft, highly diffused shadows with a low opacity (4-8%) and a slight tint of the Primary color (Pink) or Neutral (Taupe). This prevents shadows from looking "dirty" on warm backgrounds.
- **Layering:** Depth is created by placing white cards or elements over Warm Beige surfaces. 
- **Transitions:** Use soft blurs and subtle fades to enhance the feeling of specialized care and gentleness.

## Shapes

The shape language is defined by **Rounded (0.5rem)** corners. This radius is applied to buttons, input fields, and cards to soften the interface and make it feel more welcoming. 

Large-scale imagery and container wrappers may use even softer radii (1rem to 1.5rem) to reinforce the organic, human-centric nature of the brand. Sharp 90-degree angles should be avoided in all UI components to maintain the feminine aesthetic.

## Components

- **Buttons:** Primary buttons use a solid Warm Beige or Soft Pink fill with Taupe text. For the "Luxury" feel, use a ghost button style with a Refined Gold border for secondary actions.
- **Input Fields:** Minimalist design with a bottom-only border or a very light background fill. Focus states should transition the border color to Refined Gold.
- **Cards:** Used for service menus or staff profiles. Cards should have no visible border, utilizing the "Rounded" shape and a subtle ambient shadow to lift from the background.
- **Chips/Badges:** Used for service categories (e.g., "Facials," "Massage"). These should be pill-shaped with a low-opacity Primary color fill.
- **Image Containers:** Since imagery is a focus, images should feature a subtle inner "glow" or soft rounded corners to integrate seamlessly with the typography.
- **Service Lists:** Use elegant Serif headers for service names with the Sans-serif body for descriptions, separated by generous vertical padding and a very faint horizontal divider.