---
name: Kinetic Kinetic / Raw Blueprint
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
  on-surface-variant: '#434933'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#747a60'
  outline-variant: '#c3caac'
  surface-tint: '#4e6700'
  primary: '#4e6700'
  on-primary: '#ffffff'
  primary-container: '#c6ff00'
  on-primary-container: '#587300'
  inverse-primary: '#a6d700'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2e1'
  on-secondary-container: '#656464'
  tertiary: '#006970'
  on-tertiary: '#ffffff'
  tertiary-container: '#b0f8ff'
  on-tertiary-container: '#00767e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bef500'
  primary-fixed-dim: '#a6d700'
  on-primary-fixed: '#151f00'
  on-primary-fixed-variant: '#3a4d00'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#7df4ff'
  tertiary-fixed-dim: '#00dbe9'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  headline-xl:
    fontFamily: Syne
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 76px
    letterSpacing: -0.04em
  headline-xl-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Syne
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 52px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Syne
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Space Grotesk
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.08em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 9px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.12em
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 3rem
---

## Brand & Style

This design system establishes a high-voltage, avant-garde brutalist aesthetic engineered for progressive design studios, experimental creative technologists, and high-fashion editorial platforms. The brand attitude is uncompromising, razor-sharp, and architecturally deliberate. It rejects polished corporate minimalism in favor of visceral tension: colliding raw CAD wireframes, Bezier drafting crosshairs, and structural vector paths with monumental typography and radioactive chartreuse saturation.

The emotional impact is immediate sensory electricity paired with clinical precision. Layouts evoke the working canvas of a vector design tool or master blueprint, elevated to couture graphic art. The visual architecture relies on exposed grid skeletons, zero-radius mechanical contours, monospaced metadata stamps, and unapologetic black-on-acid contrasts.

## Colors

The palette operates on high-voltage dynamic range. Rather than standard muted surfaces, the primary background canvas is dominated by piercing electric lime (`#c6ff00` / `#d4ff00`), generating an unrelenting graphic punch. Razor-sharp contrast is anchored by jet obsidian (`#0a0a0a`), serving as the primary text, structural frame, and solid container background.

Crisp stark white (`#ffffff`) acts as a distinct graphic cutout layer—creating striking typographic badges, inverted status blocks, and intense focus points. Technical cyan (`#00f0ff`) provides pinpoint vector accents, handle-points, and precision coordinate indicators, referencing digital pen tool nodes and blueprint markers.

Tonal hierarchies are strictly functional:
- **Canvas Base:** High-saturation acid chartreuse `#c6ff00` or stark blackout `#0a0a0a`.
- **Text & Master Line Art:** Jet black `#0a0a0a` against lime fields; electric lime `#c6ff00` or stark white `#ffffff` against dark fields.
- **Wireframe Guides & Bounding Boxes:** 1px hairline strokes in `#0a0a0a` with 40% opacity or cyan `#00f0ff` highlights.

## Typography

The typographic hierarchy juxtaposes avant-garde sculptural geometry with computational precision:

- **Display & Headlines (Syne):** Extra-bold, wide, kinetic letterforms create unmissable architectural statements. Kerning is tight, and tracking is pulled inward to form interlocking typographic blocks. Headlines may combine filled typography with outline/wireframe stroke text.
- **Body & Secondary Copy (Space Grotesk):** Provides structural geometric clarity, maintaining modern tension without sacrificing sustained legibility across portfolio narratives and case study dossiers.
- **System Labels, Metatags & Drafting Coordinates (JetBrains Mono):** Monospaced, tracked-out uppercase notation acts as cad-like annotations (e.g., `// 2021-2024`, `[INDEX_001]`, `(C)SSORA`). Used for vertical running sidebar text, coordinate stamps, and interactive tags.

## Layout & Spacing

The layout model is governed by a visible, unyielding modular blueprint grid:

- **Grid Skeletons:** A rigid 12-column responsive grid on desktop and 4-column on mobile. Visible hairlines (`1px solid #0a0a0a` or low-opacity chartreuse) explicitly segment columns, margins, and content panels.
- **Asymmetric Tension & Vertical Rails:** Dedicated vertical index rails (36px to 64px wide) anchor screen edges for vertically rotated metadata labels (`writing-mode: vertical-rl`), indexing years, sections, and category tags.
- **Crosshairs and Anchor Points:** Grid intersections, card corners, and hero modules display technical bounding-box markers (tiny 4px crosshairs `+` or anchor point squares `■`) reinforcing the drafting software viewport aesthetic.
- **Responsive Adaptation:**
  - **Desktop (1024px+):** Deep margin gutters, multi-column editorial spreads, overlapping vector paths, and persistent sidebar metadata rails.
  - **Tablet (768px - 1023px):** 8-column layout; technical coordinates remain visible, vertical text rotates to horizontal sub-headers where width is restricted.
  - **Mobile (< 768px):** Single-column stacked blocks encased in strict hairline-bordered cells, preserving the tactile framing and stark contrast.

## Elevation & Depth

This design system deliberately eschews realistic skeuomorphic shadows, soft blur drop shadows, and pillowy elevations. Depth is purely planar, graphic, and mechanical:

- **Zero-Diffusion Hard Shadows:** When depth is required, elements utilize pure hard-edge offset shadows (`4px 4px 0px #0a0a0a` or `6px 6px 0px #000000`). No blur radius is ever applied.
- **Flat Orthographic Layering:** Depth is conveyed through structural z-indexing: crisp stark white blocks floating over electric lime fields, bounded by hairline ink-traps.
- **Exposed Drafting Overlays:** SVG vector paths, Bezier handles, circular arc guides, and control-point callouts layer beneath or slice through foreground headline typography, simulating an active artwork-under-construction state.

## Shapes

The shape system is strictly architectural and brutalist:

- **Zero-Radius Primitives:** All standard interface containers, buttons, cards, and modal sheets have a `0px` border radius (`roundedness: 0`). Edges are razor-sharp.
- **Vector Knots & Nodes:** Decorative badge tags or technical points feature sharp 4px or 6px square node handles along border midpoints and corners, emulating anchor points in vector drafting applications.
- **High-Contrast Geometric Cutouts:** Inverted solid rectangular chips and high-contrast color blocks construct layout shapes with relentless angularity.

## Components

### Buttons
- **Primary Action:** Solid black (`#0a0a0a`) background with electric lime (`#c6ff00`) bold monospaced typography, uppercase, `0px` radius, 1px solid `#0a0a0a` border. On hover, background inverts to `#c6ff00` with `#0a0a0a` text and a hard `4px 4px 0px #0a0a0a` offset shadow.
- **Ghost / Drafting Button:** Transparent background, `1px solid #0a0a0a` hairline frame, square anchor dots pinned to all four corners. On hover, fills solid white `#ffffff`.

### Chips & Metadata Badges
- **Stark Cutout Chip:** Solid stark white (`#ffffff`) background, high-contrast cyan (`#00f0ff`) or jet black (`#0a0a0a`) monospaced typography, bracketed notation (`[01 / BRAND]`). Zero roundedness.
- **Status Indicator:** Solid lime dot or vector crosshair pinned to the left edge of an uppercase caption string.

### Lists & Modular Tables
- **Drafting Rows:** Separated by hairline `1px solid #0a0a0a` rules. Each row acts as an interactive cell: index number in `JetBrains Mono` on the left, oversized project title in `Syne` in the center, and technical timestamp on the far right.
- **Hover State:** Row background rapidly swaps to high-voltage chartreuse or stark white with inverse text color.

### Cards & Viewport Modules
- **Project Matrix Card:** Razor-sharp rectangular container wrapped in `1px solid #0a0a0a`. Corners feature corner-tick crosshairs. Image assets inside maintain sharp 0px clipping with high-contrast threshold/duotone hover filters.
- **Information Bounding Box:** Inset technical metrics displayed inside secondary border lines with coordinate notation (e.g., `X: 420 Y: 1080`).

### Checkboxes & Radio Controls
- **Brutalist Checkbox:** Square `16px x 16px` zero-radius frame with a 2px black border. Checked state displays a solid black fill or high-visibility electric lime interior block.
- **Brutalist Radio:** Diamond or square toggles rather than circles, reinforcing the unyielding geometric CAD lexicon.

### Input Fields
- **Wireframe Input:** Transparent background sitting atop an electric lime or obsidian plane, demarcated solely by a crisp bottom hairline or full `1px solid #0a0a0a` border. Monospaced placeholder text in 50% opacity, transitioning to high-contrast full-weight typing with an active cyan focus border.