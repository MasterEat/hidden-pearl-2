---
name: Hidden Pearl Boutique
colors:
  surface: '#f7f9ff'
  surface-dim: '#d8dadf'
  surface-bright: '#f7f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f9'
  surface-container: '#eceef3'
  surface-container-high: '#e6e8ee'
  surface-container-highest: '#e0e2e8'
  on-surface: '#181c20'
  on-surface-variant: '#3c4949'
  inverse-surface: '#2d3135'
  inverse-on-surface: '#eef1f6'
  outline: '#6c7a79'
  outline-variant: '#bbc9c8'
  surface-tint: '#006a69'
  primary: '#006a69'
  on-primary: '#ffffff'
  primary-container: '#43d9d7'
  on-primary-container: '#005b5a'
  inverse-primary: '#45dbd9'
  secondary: '#555f6f'
  on-secondary: '#ffffff'
  secondary-container: '#d6e0f3'
  on-secondary-container: '#596373'
  tertiary: '#5d5f5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#c5c5c1'
  on-tertiary-container: '#50524e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#69f7f5'
  primary-fixed-dim: '#45dbd9'
  on-primary-fixed: '#00201f'
  on-primary-fixed-variant: '#00504f'
  secondary-fixed: '#d9e3f6'
  secondary-fixed-dim: '#bdc7d9'
  on-secondary-fixed: '#121c2a'
  on-secondary-fixed-variant: '#3d4756'
  tertiary-fixed: '#e3e3de'
  tertiary-fixed-dim: '#c6c7c2'
  on-tertiary-fixed: '#1a1c19'
  on-tertiary-fixed-variant: '#454744'
  background: '#f7f9ff'
  on-background: '#181c20'
  surface-variant: '#e0e2e8'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is anchored in the concept of "Urban Sanctuary." It targets discerning travelers seeking an authentic, high-end residential experience in an urban setting. The aesthetic draws heavily from **Minimalism** and **Modern Editorial** design, prioritizing quiet luxury over loud ornamentation. 

The emotional response should be one of immediate decompression—shifting from the chaotic energy of travel to the calm, curated atmosphere of a boutique apartment. The visual language utilizes expansive white space, precise grid alignments, and a rhythmic balance between fine-lined typography and high-resolution architectural photography. The interface acts as a sophisticated frame for the property's physical beauty, ensuring the digital experience is as seamless and premium as the stay itself.

## Colors

The palette is a sophisticated mix of warm neutrals and a singular, vibrant Mediterranean accent.

- **Primary Accent (#43D9D7):** A luminous turquoise used sparingly for interactive elements, status indicators, and subtle brand flourishes. It represents the "pearl" within the urban greyscale.
- **Neutrals & Surfaces:** 
    - **Pearl White (#FCFCFA):** The primary background color to ensure a soft, non-clinical feel.
    - **Soft Greige (#E5E5E0):** Used for subtle section dividers and secondary backgrounds.
    - **Deep Charcoal (#1F2937):** Used for primary text and high-contrast UI elements to ensure groundedness and readability.
- **Usage Note:** Backgrounds should remain predominantly light. Avoid using the primary turquoise for large surfaces; it is strictly a functional accent to maintain a premium, understated atmosphere.

## Typography

This design system uses a high-contrast typographic pairing to evoke a "boutique journal" feel. 

- **Headlines:** Playfair Display provides an authoritative, elegant, and literary tone. Serif headings should use "Optical Sizing" where available to maintain hair-line elegance at large sizes. 
- **Body & Interface:** Inter is used for its exceptional legibility and neutral character, ensuring that functional information doesn't compete with the editorial headlines.
- **Bilingual Support:** Both fonts have extensive support for Greek and Latin glyphs. Ensure that line-heights are generous (1.6x for body) to accommodate the slightly taller nature of Greek characters and maintain a "breathing" layout.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on desktop to maintain the integrity of editorial compositions. 

- **Grid:** A 12-column grid is used for desktop. 
- **Rhythm:** Generous vertical "white space" (section gaps of 120px) is essential to convey a sense of luxury and calm.
- **Full-Width Bleeds:** While text content stays within the 1280px container, hero imagery and specific editorial panels should "bleed" to the edges of the viewport to create an immersive, architectural feel.
- **Mobile Reflow:** On mobile devices, the 12-column grid collapses to a single column with 20px side margins. High-impact imagery should maintain a 4:5 or 1:1 aspect ratio to dominate the viewport.

## Elevation & Depth

This design system avoids heavy drop shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

- **Depth:** Physicality is suggested through subtle color shifts rather than shadows. For example, a "Card" or "Surface" is defined by a change from White to Soft Greige (#F5F5F0).
- **Overlays:** When elements overlap (e.g., text over photography), use a very soft, high-blur scrim or a solid white background with 95% opacity. 
- **Lines:** Use 1px solid lines in Muted Grey (#E5E5E0) for structural separation (fact strips, footers, and navigations). This reinforces the "architectural drawing" aesthetic.

## Shapes

The shape language is strictly **Sharp (0px)**. 

Rectilinear forms reflect the clean lines of modern architecture and the structure of a printed magazine. This applies to buttons, image containers, input fields, and cards. By removing all border-radius, the UI feels more disciplined, premium, and sophisticated. The only exception is for circular icons or specific "Pearl" brand elements which may use a 100% radius (pill/circle).

## Components

- **Sticky Header:** A minimal bar using a Pearl White background. The logo sits left, while the language switcher (GR/EN) uses `label-caps` typography with a simple 1px vertical divider.
- **Buttons:**
    - *Primary:* Solid Deep Charcoal background with White text. Hover state shifts to Primary Turquoise.
    - *Ghost:* 1px Deep Charcoal border, no background.
- **Property Fact Strips:** A horizontal row of data (e.g., "4 Guests", "2 Bedrooms") separated by 1px vertical lines. Use ultra-thin (1pt) line icons in Charcoal.
- **Editorial Content Blocks:** Alternating layouts (Image Left / Text Right and vice versa). Text containers should have significant padding to ensure they never feel crowded against the imagery.
- **Amenities Grid:** A 3 or 4 column grid using simple line icons. Labels use `body-md` weight.
- **FAQ Accordions:** Completely flat design. Questions use `headline-sm`. The expand/collapse icon is a simple '+' or '-' sign in Turquoise. No borders between items; use a simple 1px horizontal rule.
- **Input Fields:** Bottom-border only (1px Charcoal). Labels float above in `label-caps`. This mimics high-end stationery.