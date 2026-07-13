---
name: Editorial Engineering
colors:
  surface: '#fff8f6'
  surface-dim: '#dfd9d7'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f9f2f0'
  surface-container: '#f3eceb'
  surface-container-high: '#ede7e5'
  surface-container-highest: '#e8e1df'
  on-surface: '#1d1b1a'
  on-surface-variant: '#4f4541'
  inverse-surface: '#33302f'
  inverse-on-surface: '#f6efed'
  outline: '#817470'
  outline-variant: '#d2c3be'
  surface-tint: '#6f5a52'
  primary: '#261811'
  on-primary: '#ffffff'
  primary-container: '#3d2c25'
  on-primary-container: '#ab9289'
  inverse-primary: '#dcc1b7'
  secondary: '#894f38'
  on-secondary: '#ffffff'
  secondary-container: '#feb295'
  on-secondary-container: '#79422c'
  tertiary: '#341002'
  on-tertiary: '#ffffff'
  tertiary-container: '#4e2413'
  on-tertiary-container: '#c78971'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f9ddd2'
  primary-fixed-dim: '#dcc1b7'
  on-primary-fixed: '#271812'
  on-primary-fixed-variant: '#56433b'
  secondary-fixed: '#ffdbce'
  secondary-fixed-dim: '#ffb599'
  on-secondary-fixed: '#360f01'
  on-secondary-fixed-variant: '#6d3823'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#fbb79d'
  on-tertiary-fixed: '#341003'
  on-tertiary-fixed-variant: '#693a27'
  background: '#fff8f6'
  on-background: '#1d1b1a'
  surface-variant: '#e8e1df'
typography:
  display-xl:
    fontFamily: Sora
    fontSize: 120px
    fontWeight: '800'
    lineHeight: 110px
    letterSpacing: -0.04em
  display-lg:
    fontFamily: Sora
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 84px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  technical-label:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  mono-code:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  section-gap: 160px
  container-padding: 64px
  gutter: 32px
  margin-mobile: 24px
---

## Brand & Style

This design system merges the precision of cloud architecture with the high-end aesthetic of independent editorial print. The brand personality is authoritative yet tactile, positioning technical mastery as an art form rather than a utility. 

The design style is a sophisticated hybrid of **Swiss Typography** and **Minimalist Editorial**. It utilizes high-impact, oversized type pairings and a broken grid layout to create a rhythmic, non-linear reading experience. The emotional response is one of "curated complexity"—where technical depth is presented with the spaciousness and elegance of a luxury magazine. 

Key visual identifiers include overlapping elements, paper-cut transition effects, and a warm, organic color palette that humanizes the sterile world of networking and cloud infrastructure.

## Colors

The palette moves away from traditional "tech-blue" in favor of a warm, grounded earth-tone spectrum.

- **Primary (#3D2C25):** A deep, rich brown used for maximum typographic contrast and grounding.
- **Secondary (#9B5E46):** An earthy clay used for primary actions, links, and highlighted technical nodes.
- **Tertiary (#C98B73):** A softer terracotta used for secondary accents, hover states, and decorative graphic elements.
- **Background (#F7F3EE):** A warm beige that serves as the "paper" canvas, reducing eye strain and providing a premium feel.
- **Surface (#FFF9F5):** An off-white reserved for floating cards and container elements to create subtle, organic depth.

## Typography

The typographic system is the core of the identity, using a "Swiss-Industrial" hierarchy.

- **Display & Headlines:** Sora is used in heavy weights and massive scales. Overlap these elements with images or following sections to create "broken" depth.
- **Body Text:** Plus Jakarta Sans provides a clean, modern contrast to the geometric display type, ensuring long-form technical explanations remain highly legible.
- **Technical Accents:** JetBrains Mono is used for labels, metadata, and code snippets. It should always be set in uppercase for labels to emphasize the "engineered" nature of the content.
- **Styling Note:** Use "hanging punctuation" and tight tracking on large display type to mimic high-end editorial layouts.

## Layout & Spacing

The system employs a **Broken 12-Column Grid** that encourages asymmetrical compositions.

- **The Macro-Grid:** Large sections are separated by expansive whitespace (160px+) to allow the "editorial" breathability typical of high-end magazines.
- **Horizontal Flow:** Project showcases utilize a horizontal-scroll mechanism that breaks the vertical scrolling pattern, mimicking the turning of a page.
- **Asymmetry:** Content should rarely be perfectly centered. Offset text blocks against oversized typography to create a sense of movement.
- **Mobile Adaptivity:** On mobile, the 12-column grid collapses to 4 columns. Oversized typography should scale aggressively (using `headline-lg-mobile`) and overlaps should be simplified to maintain touch-target integrity.

## Elevation & Depth

This design system avoids traditional shadows in favor of **Tonal Layering** and **Physical Metaphors**.

- **Paper-Cut Transitions:** Use hard-edged, clipped paths for section transitions to simulate stacked sheets of high-quality paper.
- **Layered Depth:** Use the `surface_hex` (#FFF9F5) to create "raised" areas against the `background_hex` (#F7F3EE). Instead of shadows, use subtle 1px borders in a slightly darker tint of the background color to define edges.
- **Glassmorphism (Subtle):** Apply a light backdrop blur (8px) with 40% opacity on navigation bars to maintain the "premium tech" feel without losing the organic warmth.

## Shapes

The shape language is organic and approachable. 

- **Containers:** All cards and primary containers use a 1rem (16px) radius to soften the rigidity of the grid.
- **Interactive Nodes:** Skill nodes in the interactive network map use perfect circles to represent atomic units of data.
- **Images:** Photography should feature slightly rounded corners (8px) or be masked in "organic" blob shapes to contrast with the sharp, geometric typography.

## Components

- **Magazine-Style Sections:** Use a "Master/Detail" layout where a massive Sora headline occupies 60% of the viewport width, with body text tucked into a narrow column on the opposite side.
- **Horizontal Project Cards:** Large-format cards with fixed aspect ratios (16:9). Upon hover, the earthy secondary color should "bleed" into the background of the card.
- **Network-Map Skill Nodes:** Interactive SVG nodes connected by thin, 1px lines. Use JetBrains Mono for the labels. Nodes should pulse with the `secondary_color` when active.
- **Buttons:** Large, pill-shaped buttons with `primary_color` backgrounds and `background_hex` text. Use a subtle "squish" animation on click.
- **Technical Lists:** Use JetBrains Mono for numbering (e.g., 01, 02, 03) and separate list items with thin, low-contrast horizontal rules.
- **Input Fields:** Minimalist under-line inputs (rather than boxed) to maintain the "drafting paper" aesthetic.