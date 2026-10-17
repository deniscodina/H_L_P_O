---
name: Technical Empanada Spec
colors:
  surface: '#f4fafe'
  surface-dim: '#d5dbdf'
  surface-bright: '#f4fafe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4f8'
  surface-container: '#e9eff3'
  surface-container-high: '#e3e9ed'
  surface-container-highest: '#dde3e7'
  on-surface: '#161c1f'
  on-surface-variant: '#55433c'
  inverse-surface: '#2b3134'
  inverse-on-surface: '#ecf2f6'
  outline: '#88736b'
  outline-variant: '#dbc1b8'
  surface-tint: '#964824'
  primary: '#3d1100'
  on-primary: '#ffffff'
  primary-container: '#602000'
  on-primary-container: '#e3855c'
  inverse-primary: '#ffb597'
  secondary: '#216390'
  on-secondary: '#ffffff'
  secondary-container: '#92ccff'
  on-secondary-container: '#0a5783'
  tertiary: '#301b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#4d2e00'
  on-tertiary-container: '#db8c00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcd'
  primary-fixed-dim: '#ffb597'
  on-primary-fixed: '#360f00'
  on-primary-fixed-variant: '#78310f'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#92ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#ffddb7'
  tertiary-fixed-dim: '#ffb95e'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f4fafe'
  on-background: '#161c1f'
  surface-variant: '#dde3e7'
  crust-dark: '#602000'
  crust-baked: '#85340D'
  blueprint-cyan: '#73ADDE'
  blueprint-grid: '#B8DCF5'
  crust-gold: '#FFA400'
  crust-light: '#FFE469'
  crust-amber: '#DF8C00'
  surface-canvas: '#F0F6FA'
  surface-card: '#FFFFFF'
typography:
  display-hero:
    fontFamily: Climate Crisis
    fontSize: 44px
    fontWeight: '900'
    lineHeight: 48px
  display-hero-mobile:
    fontFamily: Climate Crisis
    fontSize: 30px
    fontWeight: '900'
    lineHeight: 34px
  counter-giant:
    fontFamily: Climate Crisis
    fontSize: 72px
    fontWeight: '900'
    lineHeight: 72px
  counter-giant-mobile:
    fontFamily: Climate Crisis
    fontSize: 56px
    fontWeight: '900'
    lineHeight: 56px
  headline-sm:
    fontFamily: Space Mono
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 22px
    letterSpacing: 0.04em
  body-md:
    fontFamily: Space Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-sm:
    fontFamily: Space Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 15px
  label-code:
    fontFamily: Space Mono
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.08em
  label-badge:
    fontFamily: Space Mono
    fontSize: 9px
    fontWeight: '700'
    lineHeight: 10px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.25rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

The design system embodies a tongue-in-cheek fusion between rigorous architectural schematic drafting and warm Argentine culinary culture. It frames an organic, comforting subject—the empanada—within an analytical engineering blueprint. The target audience seeks levity, tactile delight, and an engaging single-screen counting experience.

The aesthetic fuses **Brutalism** and **Tactile Blueprinting**:
- **Technical Precision**: Cyan drafting axes, measurement ticks, crop marks, and monospaced technical readouts establish structural rigor.
- **Culinary Warmth**: Rich, baked crust browns and golden yolk tones interrupt the cold engineering canvas, giving tactile presence to buttons and illustration layers.
- **Expressive Tension**: Bloated, high-impact headline typography collides with monospaced data markers, reinforcing the satirical premise of calculating physical stomach capacity through structural drafting standards.

## Colors

The palette establishes an intentional thermal contrast between the cold engineering environment and the hot, oven-baked subject matter:

- **Primary (`#602000`, `#85340D`)**: Warm crust tones serve as line art, primary structural strokes, focus outlines, and primary action triggers.
- **Secondary (`#73ADDE`, `#B8DCF5`)**: Blueprint cyans govern engineering registration marks, technical callouts, measurement ticks, and the coordinate grid.
- **Tertiary (`#FFA400`, `#FFE469`, `#DF8C00`)**: Golden crust highlights indicate status progression, capacity filling, active states, and savory accents.
- **Neutral (`#F0F6FA`, `#FFFFFF`)**: Pure blueprint ground and clinical white module decks. 

Apply `#B8DCF5` at low opacity (12–18%) for the background millimeter grid pattern. Reserve `#602000` for physical stroke lines to ensure high-contrast legibility over `#F0F6FA`.

## Typography

The type system juxtaposes dramatic mass against technical precision:

- **Display & Counter (`Climate Crisis`)**: Used exclusively for top-level brand impact ("HAY LUGAR PARA OTRA?") and the primary numerical count. It reflects dough expansion and visceral fullness. Always render in all-caps.
- **Technical & Body (`Space Mono`)**: Used for system telemetry, status reads, capacity gauges, and operational commands. All labels, coordinates, and indicators must be uppercase with expanded letter-spacing to emulate technical drafting annotations and architectural title blocks.

## Layout & Spacing

The architecture operates strictly as a **Single-Screen Viewport** (designed around a 390px × 844px mobile viewport) with zero multi-page navigation or tab bars. When viewed on larger displays, the interface locks into a centered, frame-constrained vertical technical sheet.

- **Vertical Cadence**: The canvas is organized top-to-bottom across four defined operational zones:
  1. *Header Deck*: Title and technical blueprint section tags (`SEC: 01 // CAPACITY_MONITOR`).
  2. *Hero Stage*: An interactive schematic coordinate target hosting the scale-reactive vector asset.
  3. *Telemetry Bar*: Stomach saturation gauge (`0% → 100%`) with micro measurement indices.
  4. *Command Deck*: Primary action triggers, reset controls ("Piatto Vuoto"), and operational badges.
- **Rhythm**: Layout rules align strictly to a 4px sub-grid anchored over a repeating millimeter blueprint matrix. Component gaps remain tight (`space-sm` to `space-md`) to mirror high-density instrumentation panels.

## Elevation & Depth

Visual hierarchy does not use artificial skeuomorphic lighting or blurry drop shadows; depth is conveyed through layered physical drafting surfaces and architectural drafting borders:

- **Surface Tiers**:
  - *Layer 0 (Canvas)*: `#F0F6FA` with an overlaid 10px / 20px cyan millimeter grid.
  - *Layer 1 (Modular Decks)*: `#FFFFFF` panels featuring crisp `1.5px` borders in `#602000` or `#73ADDE`.
  - *Layer 2 (Floating Action Docks)*: Raised panels utilizing high-offset hard shadows: `0px 4px 0px #602000` (tactile architectural draft shadow).
  - *Layer 3 (Overlays & Alert Banners)*: Full-bleed popout technical sheets framed with double `#602000` hairline rules.
- **Active State Elevation**: Pressed controls translate `2px` downward along the Y-axis while reducing their hard shadow offset by `2px`, creating a tangible mechanical switch response.

## Shapes

The interface maintains a structural, semi-machined corner aesthetic:

- **Base Radius (`roundedness: 1`)**: Standard elements (telemetry boxes, secondary buttons, badge tags) use `0.25rem` (4px) corner rounding to soften raw industrial hard edges without losing structural crispness.
- **Deck Sheets (`rounded-lg`)**: Primary interactive sheet modules employ `0.5rem` (8px).
- **Registration Ticks & Blueprint Marks**: Precision reticles, measurement pips, and stomach gauge segments maintain strictly square corners (`0px`).
- **Interactive Hero**: The central vector illustration breaks from the rigid geometric framing with its hand-pleated scalloped border (*repulgue*), providing an organic focal anchor.

## Components

### Buttons
- **Primary Counter Trigger ("OTRA MAS")**:
  - Surface: `#FFA400` with baked golden gradient transition into `#DF8C00`.
  - Border: `2px solid #602000`. Shadow: `0px 4px 0px #602000`.
  - Typography: `headline-sm`, uppercase, font family `Space Mono`.
  - Active State: `transform: translateY(2px)`, shadow reduces to `0px 2px 0px #602000`.
- **Secondary / Danger Action ("PIATTO VUOTO" / Reset)**:
  - Surface: Transparent or `#FFFFFF` with blueprint border `1.5px solid #73ADDE`.
  - Text Color: `#602000`.
  - Hover / Focus: Background tint `#F0F6FA`, border `#602000`.

### Capacity Gauge (Stomach Saturation)
- Track: `#FFFFFF` container with `1.5px solid #602000`, subdivided by internal hairline tick marks every 10% unit.
- Fill: `#FFA400` shifting dynamically into `#85340D` as capacity exceeds 80%.
- Capacity Labels: `label-code` metadata mounted directly above the bar displaying dynamic readouts (e.g., `CAPACITY: 7/10 [70%]`).

### Chips & Technical Badges
- Surface: `#FFFFFF` or `#F0F6FA`.
- Border: `1px solid #73ADDE`.
- Padding: `0.125rem 0.375rem`.
- Typography: `label-badge` in `#73ADDE` or `#602000`, prefixed with drafting syntax (e.g., `SPEC // ASADOR EXPERTO`).

### Inspection Cards / Decks
- Container: Flat `#FFFFFF` sheet with a single `1.5px solid #602000` boundary.
- Architectural Annotations: Exterior corner tick lines (`+` crosshairs) placed at top-left and bottom-right corners using `#73ADDE`.
- Interior Padding: `space-md` to `space-lg`.

### Hero Stage Canvas
- Central circular blueprint target with dashed radial reference rings in `#B8DCF5`.
- Floating dimension callouts projecting from the empanada asset via `#73ADDE` leader lines displaying mock scale indicators (e.g., `Ø 135MM`).