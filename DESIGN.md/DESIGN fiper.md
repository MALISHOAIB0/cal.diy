---
name: Kinetic Precision
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e8bcb6'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#ae8882'
  outline-variant: '#5e3f3b'
  surface-tint: '#ffb4a9'
  primary: '#ffb4a9'
  on-primary: '#690002'
  primary-container: '#ff5545'
  on-primary-container: '#5c0002'
  inverse-primary: '#c00009'
  secondary: '#ffb4a8'
  on-secondary: '#690100'
  secondary-container: '#a50301'
  on-secondary-container: '#ffaea1'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#909191'
  on-tertiary-container: '#282a2a'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4a9'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930005'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#ffb4a8'
  on-secondary-fixed: '#410000'
  on-secondary-fixed-variant: '#930100'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  danger-red: '#A30100'
  pure-white: '#FFFFFF'
  deep-black: '#0A0A0A'
  vibrant-red: '#F42821'
typography:
  headline-xl:
    fontFamily: Barlow Condensed
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Barlow Condensed
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Barlow Condensed
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Barlow Condensed
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Barlow
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Barlow
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Barlow
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Barlow Condensed
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Barlow Condensed
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Barlow Condensed
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  xxl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system is built for a brand that is high-energy, authoritative, and technically precise. It targets a professional audience that values efficiency, speed, and reliability. The visual language evokes a sense of "active intelligence"—a platform that is always moving, processing, and delivering results.

The chosen style is **High-Contrast Modern**. It leverages a deep, near-black foundation punctuated by aggressive, high-saturation reds. This aesthetic draws inspiration from industrial performance interfaces and high-end automotive telemetry, utilizing heavy-weight typography and razor-sharp structural alignment to communicate strength and technical expertise.

## Colors

The palette is anchored in a **dark-mode-first** philosophy. The primary color is a high-vibrancy red (`#F42821`), used strategically for calls to action and critical status indicators. A deeper, more traditional crimson (`#A30100`) acts as a secondary accent to provide depth and represent "danger" or "stop" states.

The background ecosystem utilizes `#0A0A0A` for primary surfaces, creating a "true-black" feel that allows the red accents to pop with maximum luminance. Text is primarily rendered in `#FFFFFF`, ensuring AAA accessibility contrast ratios. 

Avoid using middle-gray tones; instead, use low-opacity white overlays (2%, 4%, 8%) on the black background to create surface tiers.

## Typography

This design system utilizes a dual-font approach within the same family to maintain cohesion while creating high hierarchy. 

**Barlow Condensed** is reserved for headlines, labels, and UI navigation. Its narrow profile allows for impactful, high-density messaging and gives the UI a technical, data-heavy feel. It should be used in uppercase for small labels to maximize legibility at small scales.

**Barlow (Standard)** is used for all body copy and long-form text. It provides a more relaxed horizontal rhythm that aids in reading comprehension over dark backgrounds. 

For mobile, `headline-xl` should scale down to 32px, and `headline-lg` should scale to 24px.

## Layout & Spacing

The layout follows a **rigorous 12-column fluid grid** for desktop and a **4-column grid** for mobile. The system uses a 4px base unit to ensure all elements align to a technical "pixel grid."

Spacing is aggressive and structured. Layouts should favor large margins (`xxl`) between major sections to prevent the dark interface from feeling cramped. Content within cards and containers should utilize a standard `md` (16px) or `lg` (24px) padding to maintain a breathable but compact information density.

Gaps between grid items (gutters) are fixed at 24px to ensure distinct separation of data modules.

## Elevation & Depth

In this dark-mode environment, depth is achieved through **Tonal Layering** and **Subtle Outlines** rather than heavy shadows.

- **Level 0 (Background):** Pure black (`#0A0A0A`).
- **Level 1 (Cards/Containers):** A surface color created by a 4% white overlay on pure black.
- **Level 2 (Modals/Popovers):** An 8% white overlay with a very subtle, high-diffusion shadow (Color: `#000000`, Opacity: 40%, Blur: 20px).

To define edges in the dark space, every container uses a **Low-Contrast Outline**. These are 1px borders with 10% white opacity. For active or high-priority items, the border can transition to the primary red (`#F42821`) at 40% opacity.

## Shapes

The design system employs **Soft** geometry (`0.25rem` or 4px) for most UI components. This choice strikes a balance between the "clinical" feel of sharp corners and the "consumer" feel of high-radius buttons.

- **Small Components (Buttons, Inputs, Chips):** 4px corner radius.
- **Medium Components (Cards, Modals):** 8px corner radius (`rounded-lg`).
- **Containers:** Large layout containers should maintain a 4px radius to stay consistent with the technical grid.

Avoid circles unless for avatars or specific status pips; the system should feel architectural and block-based.

## Components

### Buttons
- **Primary:** Background `#F42821`, Text `#FFFFFF`, 4px radius. Bold, uppercase `label-md` typography.
- **Secondary:** Background transparent, 1px Border `#FFFFFF` (20% opacity), Text `#FFFFFF`.
- **Ghost:** No background or border, Text `#F42821`. Use for low-emphasis actions.

### Input Fields
- **Default State:** Background `#0A0A0A`, 1px border white (10%), placeholder text white (40%).
- **Focus State:** 1px border `#F42821`, background moves to 4% white overlay.
- **Label:** Use `label-sm` positioned above the input field.

### Cards
- Cards utilize a 4% white overlay surface. They should have a 1px border (white at 5% opacity) to provide a "cut-out" effect against the black background.

### Chips/Tags
- Small, compact containers with 4px radius. Use `#A30100` background for status-related tags and 10% white background for category-related tags.

### Lists
- Dividers between list items should be 1px tall, using white at 5% opacity. High-density data should use `body-sm` typography with `label-sm` headers.