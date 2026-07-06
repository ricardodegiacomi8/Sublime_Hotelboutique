---
name: Gilded Sanctuary
colors:
  surface: '#fff9eb'
  surface-dim: '#e0daca'
  surface-bright: '#fff9eb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf3e3'
  surface-container: '#f4edde'
  surface-container-high: '#eee8d8'
  surface-container-highest: '#e8e2d2'
  on-surface: '#1e1c12'
  on-surface-variant: '#4c4734'
  inverse-surface: '#333026'
  inverse-on-surface: '#f7f0e0'
  outline: '#7d7762'
  outline-variant: '#cec6ae'
  surface-tint: '#6d5e00'
  primary: '#6d5e00'
  on-primary: '#ffffff'
  primary-container: '#c5aa10'
  on-primary-container: '#4a3f00'
  inverse-primary: '#e2c633'
  secondary: '#6a5e28'
  on-secondary: '#ffffff'
  secondary-container: '#f1e09c'
  on-secondary-container: '#6e622c'
  tertiary: '#4957ab'
  on-tertiary: '#ffffff'
  tertiary-container: '#97a5ff'
  on-tertiary-container: '#28378a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe253'
  primary-fixed-dim: '#e2c633'
  on-primary-fixed: '#211b00'
  on-primary-fixed-variant: '#534600'
  secondary-fixed: '#f4e29f'
  secondary-fixed-dim: '#d7c685'
  on-secondary-fixed: '#211b00'
  on-secondary-fixed-variant: '#514612'
  tertiary-fixed: '#dee0ff'
  tertiary-fixed-dim: '#bbc3ff'
  on-tertiary-fixed: '#000f5d'
  on-tertiary-fixed-variant: '#303f92'
  background: '#fff9eb'
  on-background: '#1e1c12'
  surface-variant: '#e8e2d2'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 40px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 120px
  section-gap-mobile: 64px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
---

## Brand & Style
The brand personality for the Sublime Hotel Boutique has evolved from raw earthiness toward "Golden Hour Luxury"—an intentional blend of sun-drenched warmth and editorial sophistication. It targets a discerning traveler seeking tranquility, opulence, and a connection to the radiant Mediterranean light.

The design style is **Minimalist-Tactile**. It rejects the coldness of traditional tech minimalism in favor of a "warm" aesthetic characterized by heavy whitespace, high-end editorial typography, and a color palette derived from sun-bleached architecture (stone, aged wood, and brass). The UI should feel like a physical space: airy, grounded, and exceptionally quiet.

**Emotional Response:** Serenity, warmth, exclusivity, and radiant comfort.

## Colors
The palette is inspired by the interplay of sunlight on architectural surfaces and the cooling shadows of dusk.

- **Primary (Gilded Gold):** Used for primary actions, subtle accents, and brand markers. It represents the warmth of the sun and high-end hardware.
- **Secondary (Olive):** A foundational grounding color. It provides a natural, earth-toned counterpoint to the golden primary.
- **Tertiary (Dusk Blue):** A soft, cool accent used sparingly for contrast, reminiscent of the sky at twilight.
- **Neutral (Warm Stone):** A range of stone-inspired grays used for background layering and subtle UI partitions.

Avoid using pure black (`#000000`) or pure white (`#FFFFFF`). All colors should maintain a subtle warm undertone to ensure the "Sublime Hotel" atmosphere remains consistent.

## Typography
This system employs a classic editorial pairing to create a sense of heritage and modernity.

- **Headlines:** Use **Libre Caslon Text**. This serif face conveys authority and timeless elegance. For display sizes, tighten the letter spacing slightly to create a more curated, high-fashion look.
- **Body & UI:** Use **DM Sans**. This geometric sans-serif remains legible at small sizes while its low-contrast strokes complement the serif headlines without competing for attention.

**Hierarchy Rules:**
- Use "Display" sizes for hero sections and dramatic introductions.
- Use "Label Small" in all-caps for overlines and category tags to emphasize the editorial grid.
- Ensure body text maintains a generous line height (1.6) to support the "breathable" layout philosophy.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy with a focus on asymmetrical balance and "white space as a luxury."

**Grid Model:**
- **Desktop:** 12-column grid with a 1280px max-width. Margins are generous (80px) to frame the content like a high-end magazine.
- **Tablet:** 8-column grid with 40px margins.
- **Mobile:** 4-column grid with 20px margins.

**Spacing Rhythm:**
We use a base-8 scale, but favor larger increments for section breaks (e.g., 120px) to ensure no part of the interface feels crowded. Elements should "float" within their containers. Large photographic imagery should often break the grid or span 100% of the width to contrast with the structured typography.

## Elevation & Depth
Depth is communicated through **Tonal Layering** rather than shadows. This maintains the flat, architectural feel of the brand.

- **Surfaces:** Use the warm stone and gold-tinted neutral palette to create tiers. A "Card" is not defined by a shadow, but by a subtle shift in background color (e.g., a subtle shift from the base background to a container-low surface).
- **Outlines:** Use very low-contrast, thin borders (0.5px or 1px) in the `olive` color at 15% opacity to define boundaries without adding visual noise.
- **Photography:** The primary source of "depth" comes from high-quality, high-contrast imagery of the hotel's textures (aged brass, linen, shadows on plaster).

## Shapes
The shape language is primarily **Soft** and architectural. 

Most elements use a 0.25rem (4px) radius to take the "edge" off while maintaining a precise, structured appearance. Buttons and input fields should feel like carved stone or precision hardware—solid and deliberate.

Avoid pill shapes or large circular radii, as they feel too "tech-oriented" and playful for a luxury boutique hotel. The only exception is for circular decorative elements or avatar frames.

## Components

**Buttons:**
- **Primary:** Gilded Gold background with Dark Stone text. Rectangular with a 4px radius. No shadows.
- **Secondary:** Ghost style. Olive border (1px) with Olive text.
- **Tertiary:** Underlined text using the Serif font for a sophisticated "Read More" feel.

**Input Fields:**
- Minimalist design. Only a bottom border (1px) in Olive, or a very light stone-filled box. Labels should use `label-sm` (all-caps) positioned above the field.

**Cards:**
- Used for room listings or amenities. No shadows. Use a subtle tonal background or a simple 1px border. The focus must be on the image and the typography.

**Chips/Tags:**
- Use for amenities (e.g., "SPA", "WIFI"). Small caps, generous letter spacing, with a light gold-tinted border.

**Navigation:**
- Transparent or Warm Stone background. The logo should be the focal point, centered or left-aligned, using the `Libre Caslon Text` brand mark. Links should have generous horizontal padding.