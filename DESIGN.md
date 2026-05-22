---
name: DS Integrales Design System
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#56423c'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#89726b'
  outline-variant: '#dcc1b8'
  surface-tint: '#9d4320'
  primary: '#9a401e'
  on-primary: '#ffffff'
  primary-container: '#b95833'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb59b'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#00666d'
  on-tertiary: '#ffffff'
  tertiary-container: '#008189'
  on-tertiary-container: '#f5feff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcf'
  primary-fixed-dim: '#ffb59b'
  on-primary-fixed: '#380d00'
  on-primary-fixed-variant: '#7e2c0a'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#8ff2fb'
  tertiary-fixed-dim: '#72d6de'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Geist
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
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
  section-padding-desktop: 80px
  section-padding-mobile: 48px
  gutter: 24px
  container-max-width: 1280px
---

## Brand & Style
The design system is anchored in the concepts of **Architectural Precision** and **Craftsman Warmth**. It is designed for a target audience that values professional reliability, high-end finishing, and transparency in home renovation. 

The aesthetic is **Modern Corporate** with a focus on tactile luxury. It avoids the coldness of typical construction brands by utilizing high-quality whitespace and a sophisticated, warm-toned palette. The visual language conveys that every project is handled with both technical expertise and an eye for interior design.

## Colors
This design system uses a palette that balances the earthiness of terracotta with the premium feel of gold. 

- **Primary (Terracotta #C05D38):** Used for primary calls to action, active states, and highlighting key services. It evokes brick, clay, and the physical act of building.
- **Secondary (Gold #D4AF37):** Used sparingly for accent elements, badges, and prestige markers to emphasize quality and high-end results.
- **Neutrals:** A deep charcoal (#1A1A1A) is used for typography to maintain high contrast without the harshness of pure black. Backgrounds should utilize a slightly off-white (#FAFAFA) to reduce eye strain and feel more "lived-in" and warm.

## Typography
We utilize **Geist** for its technical precision and modern, monolinear construction. It reflects the blueprint-like accuracy required in renovation while remaining highly legible and elegant.

Headlines should use tighter letter spacing and medium-to-semibold weights to feel grounded. Body text preserves generous line heights to ensure readability during long descriptions of services or processes. Labels are uppercase with increased tracking to create a clear hierarchy for metadata and technical specs.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain a premium, editorial feel, transitioning to a fluid model on mobile.

- **Grid:** 12-column grid for desktop with 24px gutters.
- **Margins:** Large outer margins (at least 64px on desktop) to allow the content to breathe.
- **Rhythm:** Spacing follows an 8px baseline. Use 80px or 120px for vertical section separation to emphasize the "clean and professional" brand personality.
- **Reflow:** On mobile, margins reduce to 20px, and multi-column service cards stack vertically to prioritize clarity of information.

## Elevation & Depth
The design system utilizes **Ambient Shadows** and **Tonal Layers** to create a sense of organized depth.

- **Surfaces:** Use subtle gray backgrounds (#F2F2F2) for container sections to separate them from the main page background.
- **Shadows:** Shadows are highly diffused and soft (Blur: 20px-40px) with low opacity (5-8%). They should have a tiny hint of the primary terracotta color in the shadow's hex code to maintain warmth.
- **Interactions:** Upon hover, cards should slightly lift (increase shadow spread) to provide tactile feedback, mimicking the physical nature of construction materials.

## Shapes
The shape language is defined by **Subtle Softness**. 

Standard elements like buttons and input fields use an 8px radius (`rounded`). Larger components like service cards or hero images utilize a 16px radius (`rounded-lg`) to feel modern and welcoming. This balance prevents the UI from looking too "sharp" or aggressive, aligning with the "trustworthy" brand personality.

## Components

### Navigation Bar
The navigation bar is sticky with a white background and a very subtle bottom border (1px #EEE). It uses `label-md` for links. The CTA "Get a Quote" uses the Primary Terracotta color to stand out.

### Service Cards
Cards use a white surface with a `rounded-lg` corner. They feature high-quality imagery at the top followed by a `headline-sm` title. Use a subtle hover lift effect to encourage engagement.

### Step-by-Step Process Indicators
A vertical or horizontal line (Secondary Gold) connecting numbered circles. Each step uses `headline-sm` for the title and `body-md` for the description. This visualizes the renovation journey clearly.

### Testimonial Cards
Testimonials are styled with a `body-lg` italicized quote. A small 48px circular avatar of the client is placed next to their name in `label-md` bold.

### Contact Form
Inputs use a 1px border (#DDD) that transitions to the Primary Terracotta on focus. Labels are always visible above the input field to ensure accessibility. Buttons are full-width on mobile with `rounded` corners and bold `label-md` text.