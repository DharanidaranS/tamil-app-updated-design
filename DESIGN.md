---
name: Tamil Classicist Keyboard Engineering
colors:
  surface: '#141316'
  surface-dim: '#141316'
  surface-bright: '#3a383c'
  surface-container-lowest: '#0f0e11'
  surface-container-low: '#1c1b1e'
  surface-container: '#201f22'
  surface-container-high: '#2b292d'
  surface-container-highest: '#363437'
  on-surface: '#e6e1e5'
  on-surface-variant: '#d1c5b4'
  inverse-surface: '#e6e1e5'
  inverse-on-surface: '#313033'
  outline: '#9a8f80'
  outline-variant: '#4e4639'
  surface-tint: '#e8c176'
  primary: '#e8c176'
  on-primary: '#412d00'
  primary-container: '#c9a45c'
  on-primary-container: '#523a00'
  inverse-primary: '#775a19'
  secondary: '#ffb2be'
  on-secondary: '#660026'
  secondary-container: '#8f123c'
  on-secondary-container: '#ff9cae'
  tertiary: '#cac4ce'
  on-tertiary: '#322f37'
  tertiary-container: '#aca7b0'
  on-tertiary-container: '#3f3d44'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea4'
  primary-fixed-dim: '#e8c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4200'
  secondary-fixed: '#ffd9de'
  secondary-fixed-dim: '#ffb2be'
  on-secondary-fixed: '#3f0015'
  on-secondary-fixed-variant: '#8c0f3a'
  tertiary-fixed: '#e6e0ea'
  tertiary-fixed-dim: '#cac4ce'
  on-tertiary-fixed: '#1c1b21'
  on-tertiary-fixed-variant: '#48454d'
  background: '#141316'
  on-background: '#e6e1e5'
  surface-variant: '#363437'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Noto Serif
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
  headline-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Manrope
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Manrope
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Manrope
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
  code-keycap:
    fontFamily: Manrope
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 15px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system expresses the intellectual legacy of classic Tamil literary printing fused with the physical rigor of mechanical keyboard engineering. Created for high-density Windows desktop productivity and scholarly computing, the visual atmosphere is calm, reverent, and obsessively precise.

The emotional baseline is that of a quiet bibliophile’s sanctum: warm graphite obsidian, tactile keycaps with subtle chamfered steps, and glowing gold accents reminiscent of historic temple copperplate and gilt bindings. The interface rejects disposable software ephemera, presenting itself as an enduring instrument of precision input.

### Design Movements
- **Tactile / Skeuomorphic Precision**: Physical keycap architecture, micro-beveled boundaries, tactile state depression, and keyboard matrix spatial density.
- **Classic Editorial Typography**: High-contrast serif headlines rooted in traditional palm-leaf and lead-type printing heritage, supported by crisp humanist sans-serif metadata.
- **Deep Obsidian Minimal Tonalism**: A dark visual ecosystem built on deep basalt and graphite surfaces where luminescence serves strictly semantic and tactile purposes.

## Colors

The palette establishes an authoritative dark chamber, grounded in obsidian graphite and punctuated by antique gold and ceremonial maroon.

### Color Hierarchy & Roles
- **Primary (`#C9A45C` - Temple Gold)**: Reserved for primary intentional actions, active glyph indicators, milestone telemetry, and current cursor anchors.
- **Secondary (`#A22349` - Classical Tamil Maroon)**: Used strictly for semantic punctuation, live script composition triggers, and ligature inflection badges. Stays disciplined at under 10% total visual surface weight.
- **Tertiary (`#1F1D24` - Basalt Keycap)**: Forms the physical body of interactive keys, structured toolbars, and elevated modular panels.
- **Neutral (`#0E0D10` - Deep Graphite Obsidian)**: The master canvas baseline. It recedes into infinite darkness, allowing typographic glyphs and key cap edges to advance with crystalline legibility.

### Surface System
- **Surface-0 (Canvas)**: `#0E0D10`
- **Surface-1 (Chamber / Sidebar)**: `#141318`
- **Surface-2 (Keycap / Inset Containers)**: `#1F1D24`
- **Surface-3 (Raised Matrix & Flyouts)**: `#2A2731`
- **Border / Hairline**: `#3B3745` (Subtle boundary), `#C9A45C33` (Gold hairline accent)

## Typography

The typography pairs the literary weight of `Noto Serif` with the structural utility of `Manrope`.

### Script Discipline
- **Literary Headers & Glyph Showcases (`Noto Serif`)**: Evokes centuries of Tamil incised epigraphy and early hot-metal printing. Used for literary previews, document titles, layout inspection titles, and hero character displays.
- **Application Logic & Matrix HUD (`Manrope`)**: Provides ultra-clear legibility across complex multi-key mapping matrices, speed statistics, settings, and hardware state diagnostics.
- **Keycap Typography**: Primary Tamil characters use centered baseline positioning with high visual contrast. Secondary Latin mapping labels sit in the top-left corner rendered in `label-sm` with 60% opacity.

## Layout & Spacing

The layout operates on a desktop-first, high-density modular engine calibrated for screen real estate efficiency and mechanical balance.

### Grid & Density
- **Matrix Viewports**: A compact 12-column layout designed to dock keyboard maps, composition preview buffers, and phonetic conversion tables side by side.
- **Rhythm**: Built on a strict 4px sub-grid with base unit steps (`4px`, `8px`, `12px`, `20px`, `32px`). Keyboard unit keys strictly follow a standard 1U modular base with `space-xs` (4px) physical inter-key separation.
- **Adapting Breakpoints**:
  - **Desktop (>= 1200px)**: Persistent split view showing dual-pane configuration: interactive keybed dock at base, fluid document canvas at center, and glyph inspector pinned right.
  - **Compact / Tablet (< 1200px)**: Floating keybed HUD with collateral panels collapsed into sliding trays.
  - **Mobile (< 768px)**: Edge-to-edge keyboard layer with full-width composition drawer and horizontal scroll glyph ribbons.

## Elevation & Depth

Depth is modeled directly on hardware industrial design, prioritizing mechanical bevels, inner shadow extrusions, and tactile edge highlights over ambient drop shadows.

### Elevation Hierarchy
- **Level 0 (Base Bed)**: `#0E0D10` flush surface with a 1px inner hairline boundary of `rgba(255, 255, 255, 0.04)`.
- **Level 1 (Sub-Panels & Inset Trays)**: Recessed `#141318` with subtle inset shadow: `inset 0 1px 3px rgba(0, 0, 0, 0.6)`.
- **Level 2 (Resting Keycap)**: `#1F1D24` with top border highlight `inset 0 1px 0 rgba(255, 255, 255, 0.08)`, underside drop shadow `0 2px 0 #070709`, and outer hairline `rgba(255, 255, 255, 0.06)`.
- **Level 3 (Pressed Keycap)**: `#18171C` flush translated by `1.5px` downward, removing underside shadow and accentuating `inset 0 2px 4px rgba(0, 0, 0, 0.7)`.
- **Level 4 (Floating Inspections / Tooltips)**: `#2A2731` floating overlay with a crisp gold-tinted hairline border `1px solid rgba(201, 164, 92, 0.25)` and directional cast shadow `0 8px 24px rgba(0, 0, 0, 0.55)`.

## Shapes

The design system enforces architectural firmness with a roundedness factor of `1` (`0.25rem` / `4px` base radius).

### Shape Tokens
- **Standard Corners (`0.25rem`)**: Applied to mechanical keycaps, input text fields, action buttons, segmented controls, and glyph selector chips.
- **Container Corners (`rounded-lg` / `0.5rem`)**: Applied to structural floating windows, preference modals, keyboard tray borders, and literary text frames.
- **Overlay Corners (`rounded-xl` / `0.75rem`)**: Reserved for system-level flyouts and detached HUD diagnostic overlays.
- **Sharp Details (`0px`)**: Divider hairlines, table headers, and matrix layout borders maintain surgical square geometries.

## Components

### Keycaps & Interactive Keys
- **Resting**: `#1F1D24` fill, centered Tamil character in `#EAE8E4` (`body-md`), secondary script in `#8A8793` (`label-sm`). Double-chamfered border highlight.
- **Active / Depressed**: Surface drops to `#17161A`, text shifts to `#C9A45C`, underside mechanical elevation drops to zero.
- **Modifier Keys (Shift, AltGr, Grantha Toggle)**: `#19181E` muted surface with `#A22349` status dot indicator when locked.

### Buttons
- **Primary**: Solid Gold fill `#C9A45C` with deep graphite typography `#0E0D10` (`label-lg`), crisp 4px radius, and tactile 1px border `rgba(255, 255, 255, 0.2)`.
- **Secondary**: `#1F1D24` background with hairline border `#3B3745` and gold text hover state.
- **Accent (Tamil Mode Shift)**: Deep Maroon fill `#A22349` with white typography `#FFFFFF` for layout switches and conversion operations.

### Input Fields & Search Bars
- Inset dark trough `#141318` with `1px` stroke `#3B3745`. Focus transitions stroke immediately to `#C9A45C` without blurred outer halos, honoring engineering clarity. Placeholder text sits in `#686473`.

### Chips & Ligature Badges
- Compact 20px height tokens with 4px corner radii. Inactive chips use `#1F1D24` with `#9A97A5` typography. Active combination chips display `#A223491F` background, maroon outline, and `#EAE8E4` text.

### Cards & Configuration Blocks
- Surface `#141318`, separated by 1px `#3B3745` borders. Headers utilize `Noto Serif` (`headline-sm`) accompanied by warm gold section markers and mono-spaced speed/keystroke metadata.