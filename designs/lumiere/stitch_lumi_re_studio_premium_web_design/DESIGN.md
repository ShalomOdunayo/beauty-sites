---
name: Lumière Studio
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d4'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ed'
  surface-container: '#f5ece7'
  surface-container-high: '#efe6e2'
  surface-container-highest: '#e9e1dc'
  on-surface: '#1e1b18'
  on-surface-variant: '#4e4639'
  inverse-surface: '#34302c'
  inverse-on-surface: '#f8efea'
  outline: '#7f7667'
  outline-variant: '#d1c5b4'
  surface-tint: '#775a19'
  primary: '#775a19'
  on-primary: '#ffffff'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#e9c176'
  secondary: '#5e5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdb'
  on-secondary-container: '#63635f'
  tertiary: '#6d5b4a'
  on-tertiary: '#ffffff'
  tertiary-container: '#b8a18d'
  on-tertiary-container: '#483829'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#e4e2dd'
  secondary-fixed-dim: '#c8c6c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#f7dec8'
  tertiary-fixed-dim: '#dac2ad'
  on-tertiary-fixed: '#26190c'
  on-tertiary-fixed-variant: '#544434'
  background: '#fff8f5'
  on-background: '#1e1b18'
  surface-variant: '#e9e1dc'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0.01em
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Montserrat
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
  container-max: 1280px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style
The brand personality is rooted in "Understated Opulence." It targets a discerning clientele seeking a sanctuary for wellness and aesthetic refinement. The emotional response should be one of immediate serenity, trust, and a sense of being cared for in a premium environment.

This design system employs a **Luxurious Minimalism** style. It rejects the clutter of traditional medical interfaces in favor of editorial-inspired layouts. Key characteristics include:
- **Generous Whitespace:** Prioritizing "breathing room" to convey exclusivity.
- **Soft Tactility:** Using subtle depth and organic shapes to feel approachable yet high-end.
- **Refined Contrast:** High-contrast serif typography paired with muted, tonal backgrounds to create a focal point on content and imagery.

## Colors
The palette is inspired by natural stone and warm skin tones, designed to feel "lit from within."

- **Primary (Gold):** Used sparingly for high-value actions, active states, and subtle accents. It should never feel "yellow," but rather a muted, metallic sand.
- **Secondary (Beige/Ivory):** These form the foundation of the UI. Use Ivory for the primary background and Beige for section containers to create soft, tonal shifts.
- **Tertiary (Taupe):** Used for borders, secondary text, and iconography to maintain warmth where charcoal would be too harsh.
- **Neutral (Charcoal):** Reserved for primary headings and body text to ensure maximum legibility against the light background.

## Typography
The typography system relies on the interplay between the authoritative, high-contrast **Playfair Display** and the clean, geometric **Montserrat**.

- **Headlines:** Use Playfair Display for all titles. Large display sizes should utilize a medium-to-semibold weight to emphasize the delicate serifs.
- **Body Text:** Montserrat is used for all long-form content to provide a modern, clinical contrast to the serif headings. Keep line heights generous (1.6) to enhance readability and the feeling of "airiness."
- **Labels:** Small labels, such as category tags or overlines, should use uppercase Montserrat with increased letter spacing to create a sophisticated, architectural feel.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain strict control over whitespace and content density, centered within the viewport.

- **Desktop:** A 12-column grid with wide 32px gutters. Large section margins (64px) ensure content never feels cramped.
- **Sectioning:** Use significant vertical padding (120px+) between major sections to emphasize the "one thought at a time" experience.
- **Mobile:** Transition to a 4-column grid with 20px margins. Headlines should scale down aggressively to maintain the editorial balance without causing excessive wrapping.

## Elevation & Depth
Depth is created through **Tonal Layering** and **Ambient Shadows** rather than harsh borders.

- **Surfaces:** Use subtle background color shifts (Ivory to Beige) to distinguish between the page and a container.
- **Shadows:** Shadows should be extremely diffused, using a low-opacity Taupe tint rather than pure black. The blur radius should be large (30px+) with an opacity around 4-6%, creating a "floating" effect for cards.
- **Glassmorphism:** Use selective backdrop blurs (20px) for navigation bars and modal overlays to maintain a sense of environmental continuity.

## Shapes
The shape language is organic and soft. While the base `roundedness` is set to level 2 (0.5rem), this design system frequently utilizes much larger radii for prominent components like service cards and image frames to evoke a sense of comfort and beauty. Use `rounded-xl` (1.5rem) as the standard for containers and cards.

## Components
- **Buttons:** Primary buttons use a Gold background with Charcoal text. They are pill-shaped with a slight 2px vertical offset shadow. Secondary buttons are "ghost" style with a 1px Taupe border and no background.
- **Service Cards:** Use a vertical orientation with large, high-quality imagery at the top. The image should have a soft 1.5rem corner radius. Below the image, use a centered Playfair Display title and a Montserrat price label.
- **Testimonial Blocks:** Centered layout. Large "quote" marks in 10% opacity Gold. Use Playfair Display for the quote text itself at a medium size (headline-md).
- **Input Fields:** Minimalist design featuring only a bottom border in Taupe (1px). Upon focus, the border transitions to Gold. Labels should be small, uppercase Montserrat positioned above the field.
- **Chips/Tags:** Used for treatment categories. Small, pill-shaped with a Beige background and Taupe text, providing a soft contrast against the Ivory page.