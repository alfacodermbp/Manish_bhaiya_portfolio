---
name: Manish Kumar Singh
colors:
  surface: '#131318'
  surface-dim: '#131318'
  surface-bright: '#39383f'
  surface-container-lowest: '#0e0e13'
  surface-container-low: '#1b1b21'
  surface-container: '#1f1f25'
  surface-container-high: '#2a292f'
  surface-container-highest: '#35343a'
  on-surface: '#e4e1e9'
  on-surface-variant: '#ccc3d8'
  inverse-surface: '#e4e1e9'
  inverse-on-surface: '#303036'
  outline: '#958da1'
  outline-variant: '#4a4455'
  surface-tint: '#d2bbff'
  primary: '#d2bbff'
  on-primary: '#3f008e'
  primary-container: '#7c3aed'
  on-primary-container: '#ede0ff'
  inverse-primary: '#732ee4'
  secondary: '#adc6ff'
  on-secondary: '#002e6a'
  secondary-container: '#0566d9'
  on-secondary-container: '#e6ecff'
  tertiary: '#ddb7ff'
  on-tertiary: '#490080'
  tertiary-container: '#8d36db'
  on-tertiary-container: '#f2dfff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eaddff'
  primary-fixed-dim: '#d2bbff'
  on-primary-fixed: '#25005a'
  on-primary-fixed-variant: '#5a00c6'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb7ff'
  on-tertiary-fixed: '#2c0051'
  on-tertiary-fixed-variant: '#6900b3'
  background: '#131318'
  on-background: '#e4e1e9'
  surface-variant: '#35343a'
typography:
  display-xl:
    fontFamily: Syne
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 76px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 54px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 4rem
---

## Brand & Style

This design system is crafted for an editorial graphic design portfolio, targeting creative directors, design-forward brands, and high-growth technology companies. It evokes a mood of quiet authority, nocturnal precision, and artistic confidence—balancing raw creative expression with disciplined structural clarity.

The aesthetic merges **High-Contrast Editorial Minimalism** with **Subtle Glassmorphism**:
- **Editorial Minimalism:** Generous negative space, oversized display typography, and strict typographic hierarchy let visual work and case studies breathe without distraction.
- **Nocturnal Atmosphere:** Deep obsidian and midnight navy surfaces ground the interface, allowing electric purple and cool blue accents to act as deliberate focal points rather than decorative noise.
- **Subtle Glassmorphism & Hairline Structure:** Translucent, frosted-glass overlays and crisp 1px hairline borders define spatial boundaries cleanly without heavy drop shadows.

## Colors

The palette is built for a **dark-mode** default, anchored by deep obsidian (`#07070C`) and midnight navy (`#0D0E1A`) surfaces that mirror the atmospheric depth of the portrait lighting.

- **Primary (`#7C3AED`):** Electric violet used for primary calls to action, active navigation indicators, and key interactive highlights.
- **Secondary (`#3B82F6`):** Cool electric blue paired with the primary violet in subtle radial gradients, rim-light accents, and secondary interactive states.
- **Tertiary (`#A855F7`):** Luminous orchid-purple reserved for hover states, focus rings, and delicate glow accents.
- **Neutral (`#07070C`):** Deep obsidian canvas background, stepped up to midnight navy (`#0D0E1A`) for elevated cards and containers.
- **Typography & Borders:** Primary text uses crisp off-white (`#F8FAFC`) for maximum legibility, while metadata, captions, and secondary copy use muted slate (`#94A3B8`). Hairline borders use `rgba(248, 250, 252, 0.08)` to maintain subtle structural separation.

## Typography

The typographic pairing contrasts **Syne**—an expressive, wide-stance display face—with **DM Sans**, a clean geometric sans-serif engineered for effortless reading on dark surfaces.

- **Display & Headlines (`Syne`):** Used for hero statements, section titles, and case study headers. Tight negative letter-spacing (`-0.015em` to `-0.03em`) gives oversized headlines a cohesive, editorial block presence.
- **Body & Labels (`DM Sans`):** Used for project descriptions, navigation, and metadata. Uppercase `label-sm` with wide tracking (`0.08em`) is reserved for category tags, year stamps, and index numbers.
- **Responsive Scaling:** Display sizes above `32px` step down to dedicated mobile tokens (`display-xl-mobile`, `headline-lg-mobile`) below `768px` to preserve editorial impact without horizontal overflow.

## Layout & Spacing

The design system uses a **12-column fluid grid** with a maximum container width of `1440px`, allowing editorial compositions to breathe while maintaining alignment across viewports.

- **Desktop (`>= 1024px`):** 12 columns with `24px` (`1.5rem`) gutters and `64px` (`4rem`) outer margins. Major portfolio sections are separated by `space-xl` (`4rem`) or multiples thereof to establish a calm, gallery-like rhythm.
- **Tablet (`768px – 1023px`):** 8 columns with `20px` gutters and `32px` (`2rem`) outer margins. Multi-column case study grids reflow from 3-up to 2-up.
- **Mobile (`< 768px`):** 4 columns with `16px` gutters and `20px` outer margins. Split hero layouts stack vertically, placing visual focal points above introductory copy.

## Elevation & Depth

In a dark-mode editorial interface, depth is communicated through **tonal layering**, **subtle glassmorphism**, and **low-contrast hairline outlines** rather than heavy drop shadows.

- **Tonal Layers:** The base canvas sits at `#07070C`. Elevated surfaces—such as project cards, modal drawers, and navigation bars—step up to midnight navy (`#0D0E1A`) or translucent `rgba(13, 14, 26, 0.72)`.
- **Glassmorphism:** Floating navigation headers and interactive overlays apply `backdrop-filter: blur(16px)` over semi-transparent midnight surfaces, allowing ambient purple-blue gradients to softly diffuse behind content.
- **Hairline Borders:** Structural separation relies on `1px solid rgba(248, 250, 252, 0.08)` borders. On hover or active focus, borders transition to a subtle `#7C3AED` or `#A855F7` tint to signal interactivity.

## Shapes

The design system adopts a **Rounded (`2`)** shape language (`0.5rem` base radius, `1rem` for `rounded-lg`, and `1.5rem` for `rounded-xl`), balancing geometric precision with modern softness.

- **Cards & Media Frames:** Project thumbnails and case study containers use `rounded-lg` (`1rem`) to frame artwork cleanly without competing with the photography or graphic work inside.
- **Buttons & Chips:** Interactive pills, filter tags, and primary action buttons use full pill radii (`9999px`) or `0.5rem` (`rounded`) for a tactile, contemporary feel.
- **Portrait & Halo Accents:** Circular framing (`50%`) is reserved for author portraits and ambient radial glow elements.

## Components

- **Buttons:** Primary buttons feature a solid `#7C3AED` fill with `#F8FAFC` text, `label-lg` typography, and a subtle `#A855F7` outer glow on hover. Secondary buttons use a transparent background, `1px` hairline border (`rgba(248, 250, 252, 0.16)`), and `#F8FAFC` text, shifting to a frosted glass fill on hover.
- **Chips:** Category and skill tags use `label-sm` uppercase text, `rgba(248, 250, 252, 0.04)` background, and `1px` hairline borders. Active filter chips adopt a `#7C3AED` tint at 20% opacity with `#A855F7` border and text.
- **Cards:** Portfolio project cards sit on `#0D0E1A` with `rounded-lg` (`1rem`) corners and `1px` hairline borders. Hovering triggers a smooth scale-up of the inner media (`1.03x`) and a subtle border shift toward `#3B82F6` or `#7C3AED`.
- **Lists:** Editorial index lists (e.g., awards, client rosters, or archive rows) use generous vertical padding (`space-md`), `1px` bottom hairline dividers, and right-aligned metadata in `#94A3B8`.
- **Input Fields:** Contact form inputs use `#0D0E1A` backgrounds, `0.5rem` corner radius, and `1px` hairline borders. Focus states illuminate the border with `#7C3AED` and a soft `0 0 0 3px rgba(124, 58, 237, 0.2)` ring.
- **Checkboxes & Radio Buttons:** Minimalist `1px` bordered controls with `#0D0E1A` fill; checked states fill with `#7C3AED` and crisp `#F8FAFC` indicators.
- **Floating Navigation Bar:** A sticky, glassmorphic top bar (`backdrop-filter: blur(16px)`) with `1px` bottom hairline border, housing the monogram/wordmark on the left and concise `label-lg` links on the right.