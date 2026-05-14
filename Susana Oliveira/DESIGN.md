---
name: Serenity & Care
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#48454e'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#79757e'
  outline-variant: '#cac4ce'
  surface-tint: '#625981'
  primary: '#625981'
  on-primary: '#ffffff'
  primary-container: '#dcd0ff'
  on-primary-container: '#60577f'
  inverse-primary: '#ccc0ee'
  secondary: '#605d65'
  on-secondary: '#ffffff'
  secondary-container: '#e5e1ea'
  on-secondary-container: '#66636b'
  tertiary: '#695f2a'
  on-tertiary: '#ffffff'
  tertiary-container: '#e5d796'
  on-tertiary-container: '#675d28'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7deff'
  primary-fixed-dim: '#ccc0ee'
  on-primary-fixed: '#1e1539'
  on-primary-fixed-variant: '#4a4168'
  secondary-fixed: '#e5e1ea'
  secondary-fixed-dim: '#c9c5cd'
  on-secondary-fixed: '#1c1b21'
  on-secondary-fixed-variant: '#48464d'
  tertiary-fixed: '#f1e3a1'
  tertiary-fixed-dim: '#d5c787'
  on-tertiary-fixed: '#211b00'
  on-tertiary-fixed-variant: '#504714'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Nunito Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Nunito Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Nunito Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Nunito Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1120px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style

The brand personality of the design system is rooted in empathy, professional excellence, and psychological safety. Designed for a clinical psychology practice, it prioritizes a serene and breathable interface that reduces cognitive load and evokes a sense of immediate relief.

The design style is a blend of **Minimalism** and **Soft Organicism**. It utilizes generous white space (respiro) to signify clarity of mind, while incorporating subtle organic curves to avoid a cold, institutional feel. The emotional response is one of trust, stability, and quiet confidence, ensuring patients feel held in a safe, professional space from the first interaction.

## Colors

The palette is monochromatic and high-key, designed to minimize visual noise. 

- **Primary (#DCD0FF):** A soft accent lilac used for primary actions, subtle highlights, and active states. It represents the "therapeutic bridge"—a calm but clear point of focus.
- **Secondary (#F5F0F9):** A very light lilac used for section backgrounds and surface layering to distinguish content without the harshness of high-contrast borders.
- **Neutral (#FFFFFF):** Pure white is the foundation of the system, used to provide maximum "air" and a sense of clinical cleanliness.
- **Text:** Darker slate tones are used for legibility, avoiding pure black to maintain the soft atmosphere.

## Typography

This design system uses a sophisticated typographic pairing to balance clinical authority with personal approachability.

- **Headlines (EB Garamond):** Used for all major headings and titles. This classic serif typeface conveys wisdom, history, and a scholarly foundation in psychology.
- **Body & UI (Nunito Sans):** Its rounded terminals and open apertures make it highly legible and friendly. It is used for all functional text, patient records, and informational content to ensure the experience feels modern and accessible.

In Portuguese (Portugal), ensure correct usage of typography for emphasis, preferring italics for subtle nuance rather than aggressive bolding.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop and a **Fluid Grid** on mobile, with an emphasis on "Macro-Spacing."

- **The 8px Rhythm:** All padding, margins, and component heights must be multiples of 8px.
- **Generous Margins:** Desktop layouts should maintain a 64px side margin to create a "sanctuary" effect, pushing content to the center of the visual field.
- **Section Gaps:** Use large vertical spacing (120px+) between major content blocks to prevent the user from feeling overwhelmed by information.
- **Alignment:** Content should be primarily left-aligned for readability, with centered "moments of reflection" for quotes or therapeutic testimonials.

## Elevation & Depth

To maintain the serene aesthetic, depth is communicated through **Ambient Shadows** and **Tonal Layers** rather than heavy borders.

- **Tiers of Surface:** The base is pure white. Secondary information sits on `#F5F0F9` containers with no shadows. 
- **The "Floating" Effect:** Interactive cards or modals use a very soft, diffused shadow: `0 12px 32px rgba(220, 208, 255, 0.15)`. The shadow is slightly tinted with the accent lilac to feel integrated rather than grey and dirty.
- **Backdrop Blurs:** For overlays or navigation headers, use a subtle background blur (8px) with 90% opacity white to maintain context of the background while focusing the user.

## Shapes

The shape language is **Soft and Organic**. 

- **Primary Radius:** A default of `0.5rem` (8px) is applied to all standard components.
- **Large Surfaces:** Cards and containers use `1.5rem` (24px) to create a "cradling" effect.
- **Organic Accents:** For decorative elements or image masks, use asymmetrical "blob" shapes with varying radii to mimic natural forms, reinforcing the human and non-mechanical nature of the practice.

## Components

### Buttons
Primary buttons use the accent lilac (`#DCD0FF`) with dark slate text. The shape should be slightly more rounded than standard (pill-shaped or `1.5rem`). No heavy borders; use a soft hover state that deepens the color slightly.

### Cards
Cards are primarily white on a light lilac background or light lilac on a white background. Use the "Floating" shadow effect sparingly. Content should have at least `32px` of internal padding to maintain the "airy" feel.

### Input Fields
Inputs use a simple bottom border or a very light lilac fill. Focus states should transition the background to white and add a subtle primary lilac glow. Avoid harsh black outlines.

### Chips & Tags
Used for therapy specialties or session types. These should be subtly filled with the secondary lilac, using the `label-md` typography for a professional, organized appearance.

### Lists
Lists should have increased vertical line heights. Use a custom soft-circle bullet point in the primary accent lilac instead of standard black dots.

### Feedback & Notifications
Success or informational messages should use a muted sage green or the existing lilac—avoiding aggressive reds or oranges to prevent triggering anxiety in the user.