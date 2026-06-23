---
name: Clinical Precision
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#424750'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#727781'
  outline-variant: '#c2c6d1'
  surface-tint: '#27609d'
  primary: '#003461'
  on-primary: '#ffffff'
  primary-container: '#004b87'
  on-primary-container: '#8abcff'
  inverse-primary: '#a3c9ff'
  secondary: '#00658d'
  on-secondary: '#ffffff'
  secondary-container: '#41befd'
  on-secondary-container: '#004b69'
  tertiary: '#29353a'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f4c51'
  on-tertiary-container: '#aebcc2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d3e4ff'
  primary-fixed-dim: '#a3c9ff'
  on-primary-fixed: '#001c38'
  on-primary-fixed-variant: '#004882'
  secondary-fixed: '#c6e7ff'
  secondary-fixed-dim: '#81cfff'
  on-secondary-fixed: '#001e2d'
  on-secondary-fixed-variant: '#004c6b'
  tertiary-fixed: '#d7e5eb'
  tertiary-fixed-dim: '#bbc9cf'
  on-tertiary-fixed: '#111d22'
  on-tertiary-fixed-variant: '#3c494e'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
  bone-white: '#F8FAFC'
  clinical-gray: '#E2E8F0'
  success-green: '#10B981'
  deep-navy: '#002D52'
typography:
  display-lg:
    fontFamily: manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: manrope
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is engineered for an Orthopedic Surgeon, prioritizing a "Medical-Grade" aesthetic that balances surgical precision with patient-centric warmth. The brand personality is authoritative, sterile (in a clinical, clean sense), and reassuring. 

The chosen style is **Corporate / Modern** with a focus on high-legibility and structured reliability. It avoids the warm, earthy tones of the reference site in favor of a palette that emphasizes hygiene and technological advancement in orthopedic care. The visual language uses generous whitespace to reduce cognitive load for patients who may be in pain or seeking urgent information, evoking a sense of calm and professional expertise.

## Colors

The palette shifts from the reference's browns to a "Trustworthy Medical" spectrum. 

- **Primary Blue (#004B87):** A deep, institutional blue that conveys authority and stability. Used for primary actions and headers.
- **Secondary Blue (#00A3E0):** A brighter, more energetic blue used for accents and interactive elements to guide the eye.
- **Tertiary Blue (#E6F4FA):** A soft wash for backgrounds and surface differentiation, keeping the UI airy.
- **Bone White (#F8FAFC):** The primary background color, providing a cleaner, more sterile look than pure white.
- **Clinical Gray (#E2E8F0):** Used for borders and dividers to maintain structural integrity without creating visual noise.

## Typography

Legibility is the highest priority. **Manrope** is used for headlines to provide a modern, refined, and balanced appearance that feels contemporary but professional. **Inter** is used for body text and labels for its systematic, utilitarian nature, ensuring that patient instructions and service details are accessible even to those with visual impairments.

Text hierarchy is strictly maintained to allow for quick scanning of medical services and contact information. All labels utilize slightly increased letter spacing for maximum clarity.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop, centered within a 1200px container to ensure readability and focus. On mobile, it transitions to a fluid single-column layout.

Spacing is based on an 8px base unit. 
- **Desktop:** 12-column grid with 24px gutters.
- **Tablet:** 8-column grid with 24px gutters and 32px side margins.
- **Mobile:** 4-column grid with 16px gutters and 20px side margins.

Content "stacking" (vertical spacing between elements) is generous to maintain a sense of order and cleanliness. Elements should be grouped logically using `stack-md` for related items and `stack-lg` for distinct sections.

## Elevation & Depth

To maintain a "Clinical" feel, the system uses **Tonal Layers** and **Low-contrast outlines** rather than aggressive shadows. 

- **Level 0 (Surface):** Used for the main background (Bone White).
- **Level 1 (Container):** White surfaces with a subtle 1px border (#E2E8F0). Used for service cards and testimonials.
- **Level 2 (Interactive):** Elements like buttons or active cards utilize a very soft, diffused ambient shadow (Color: Primary Blue, Opacity: 8%, Blur: 12px) to suggest interactivity without breaking the flat, professional aesthetic.

Separation of sections is primarily achieved through subtle shifts in background color (Bone White to Tertiary Blue) rather than heavy drop shadows.

## Shapes

The shape language is **Soft**. A 4px (0.25rem) base radius is applied to most components. This creates a professional, disciplined look while subtly softening the "edge" of medical information to make it more approachable.

- **Standard Elements:** 4px radius (Input fields, Chips, Small buttons).
- **Cards/Modals:** 8px radius (Service cards, Appointment booking panels).
- **Full-round:** Only used for specialized "status" indicators or circular profile images for testimonials.

## Components

### Buttons
- **Primary:** Solid Primary Blue background, white text. Rectangular with soft corners.
- **Secondary:** Outlined in Secondary Blue with Secondary Blue text.
- **Action CTA:** Slightly larger padding for "Book Appointment" buttons to ensure high visibility.

### Service Cards
Designed to display orthopedic procedures (e.g., Joint Replacement, Sports Medicine). 
- **Style:** Level 1 elevation (white background, thin gray border). 
- **Layout:** Icon (Secondary Blue) at top-left, followed by Headline-md, then Body-sm. 

### Patient Testimonials
- **Style:** Tertiary Blue background. 
- **Structure:** Quote in Body-lg (italicized), followed by a small avatar and patient name in Label-lg.

### Appointment Booking
- **Input Fields:** 1px border (#E2E8F0) that turns Primary Blue on focus. 
- **Labels:** Always persistent (not floating) in Label-md above the field for medical accessibility standards.

### Chips
Used for filtering specialties or tagging doctor availability.
- **Style:** Tertiary Blue background with Primary Blue text, 4px radius.