---
name: Obsidian Mint Precision
colors:
  surface: '#111316'
  surface-dim: '#111316'
  surface-bright: '#37393d'
  surface-container-lowest: '#0c0e11'
  surface-container-low: '#1a1c1f'
  surface-container: '#1e2023'
  surface-container-high: '#282a2d'
  surface-container-highest: '#333538'
  on-surface: '#e2e2e6'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#e2e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#68dba9'
  on-secondary: '#003825'
  secondary-container: '#25a475'
  on-secondary-container: '#00311f'
  tertiary: '#ffb3af'
  on-tertiary: '#650911'
  tertiary-container: '#fc7c78'
  on-tertiary-container: '#711419'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#85f8c4'
  secondary-fixed-dim: '#68dba9'
  on-secondary-fixed: '#002114'
  on-secondary-fixed-variant: '#005137'
  tertiary-fixed: '#ffdad7'
  tertiary-fixed-dim: '#ffb3af'
  on-tertiary-fixed: '#410005'
  on-tertiary-fixed-variant: '#842225'
  background: '#111316'
  on-background: '#e2e2e6'
  surface-variant: '#333538'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
  label-kbd:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 12px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style

This design system establishes a high-efficiency, distraction-free environment tailored for utility and developer clipboard workflows. The aesthetic blends **Refined Technical Minimalism** with tactile dark-mode precision:

- **Personality:** Methodical, frictionless, unobtrusive, engineered. The interface stays quiet until activated, prioritizing data legibility and keyboard ergonomics.
- **Target Audience:** Engineers, technical writers, power users, and multi-device creators requiring instantaneous clip synchronization and code snippet fidelity.
- **Emotional Response:** Calm focus, rapid certainty, and effortless spatial control. The avoidance of pure void black (`#000000`) prevents eye strain during extended night sessions, while crisp mint accents provide instant visual validation.
- **Design Metaphor:** An illuminated dark slate workbench with micro-milled chassis borders, precision neon status diodes, and monospaced syntax clarity.

## Colors

The palette is engineered specifically for deep-focus dark environments, adhering rigorously to WCAG AA contrast ratios (minimum 4.5:1 for standard body copy, 3:1 for large display elements and structural controls).

### Tonal Foundation & Surfaces
- **Canvas / Root Background:** `#121417` (Deep graphite, warm charcoal base eliminating OLED harshness).
- **Surface Level 1 (Panels / Drawers):** `#181a1f` (Primary container for lists and workspace areas).
- **Surface Level 2 (Cards / Modals):** `#1e2228` (Interactive item blocks and clip cells).
- **Surface Level 3 (Hover / Inactive Focus):** `#262a32` (Elevated overlays and dropdown menus).

### Hairline Borders
- **Subtle Perimeter Border:** `#2d333b` (Subtle 1px structural separator across inactive states).
- **Interactive Structural Border:** `#38414d` (Hover outlines, active input frames, and divider emphasis).

### Accents & Indicators
- **Primary Mint:** `#10b981` (Action buttons, affirmative toggles, copy confirmation states, sync indicators).
- **Primary Mint Hover / Deep Accent:** `#059669` (Pressed actions and saturated state badges).
- **Mint Alpha Fill:** `rgba(16, 185, 129, 0.12)` (Selection pills, inline highlight tags, focused row fills).

### Typography Tones
- **Primary Text:** `#f1f5f9` (Crisp off-white; achieves > 13:1 contrast against `#121417`).
- **Muted Text / Metadata:** `#94a3b8` (Secondary slate; achieves 5.2:1 contrast against `#1e2228`).
- **Dimmed / Disabled Text:** `#64748b` (Shortcuts, disabled keys, non-essential syntax punctuation).

## Typography

The type system creates a functional dichotomy between administrative UI and raw clipboard content:
- **Primary Interface (`Inter`):** Applied across shell headers, navigation, tooltips, and standard utility copy. Optimized for high glanceability at small display sizes.
- **Payload & Code Surfaces (`JetBrains Mono`):** Applied to clip preview bodies, code blocks, raw hex values, sync payload stats, and keyboard shortcuts (`<kbd>`).
- **Rendering Rules:** Enable `font-feature-settings: "cv02", "cv03", "cv04", "cv11"` on Inter for unambiguous character rendering (such as disambiguating lowercase `l` and capital `I`). Code snippets maintain a rigid 1.4 tab sizing ratio.

## Layout & Spacing

This design system uses a strict **8pt reference grid with a 4pt micro-step** (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 12px, `space-lg` = 16px, `space-xl` = 24px) for data density.

### Breakpoints & Layout Model
- **Compact Viewport (< 640px):** Single-column stack. Sticky top global search, full-width clip cards, bottom action drawer. Margin: `1rem`, gutter: `0.75rem`.
- **Medium Viewport (641px - 1024px):** Dual-pane view. Left pane: navigation & tag filters (240px fixed). Right pane: fluid card grid / clipboard stream.
- **Expanded Desktop (> 1024px):** Three-column utility workbench. Left rail: system status & tags (220px). Central column: clip stream (420px max). Right column: inspector & raw clip editor (fluid fill, min 480px).
- **Component Padding Consistency:** List items and compact cards follow `space-sm` (vertical) and `space-md` (horizontal) density rules to maximize vertical scan length without feeling compressed.

## Elevation & Depth

Rather than relying on intense, muddy shadows, the design system employs **Tonal Layering with Milled Hairline Borders**:

1. **Layer 0 (Base Canvas):** `#121417`, unbordered.
2. **Layer 1 (Recessed Containers & Sidebars):** `#181a1f` with a 1px solid border in `#2d333b`.
3. **Layer 2 (Floating Cards & Item Blocks):** `#1e2228` with a 1px solid border in `#2d333b`. When hovered, the border subtly lifts to `#38414d` with a low-intensity ambient floor shadow: `0 4px 12px rgba(0, 0, 0, 0.35)`.
4. **Layer 3 (Modals, Overlays, Floating Menus):** `#262a32` with a 1px border in `#38414d` and a drop shadow of `0 12px 32px rgba(0, 0, 0, 0.55)`.
5. **Active Focus Ring:** A crisp 1px ring offset by 2px (`outline: 2px solid #10b981`, `outline-offset: 2px`) for keyboard focus traversal, guaranteeing absolute positional clarity.

## Shapes

The geometric silhouette across components is set to **Level 2 (Rounded)**:
- Standard buttons, input controls, chips, and clip item rows utilize an `8px` (`0.5rem`) corner radius.
- Larger application panels, inspector cards, and modal windows scale to `12px` (`0.75rem`) to maintain proportional contour curves.
- Keyboard badge pills (`<kbd>`) use a tighter `4px` (`0.25rem`) radius to match the precision of physical keycaps.
- Circular treatment (`rounded-full`) is strictly reserved for live sync status dots and user avatars.

## Components

### Buttons
- **Primary:** Background `#10b981`, text `#121417` (bold `Inter`), 0 borders. Hover transitions to `#059669`. Height: 36px (desktop), 40px (touch). Padding: 0 16px.
- **Secondary / Ghost:** Background `transparent`, text `#f1f5f9`, border 1px solid `#2d333b`. Hover: background `#1e2228`, border `#38414d`.
- **Icon / Micro Actions:** 28x28px, background `transparent`, text `#94a3b8`. Hover: background `#262a32`, text `#f1f5f9`.

### Clip Cards & List Items
- **Card Container:** Background `#1e2228`, border 1px solid `#2d333b`, radius 8px, padding 12px.
- **Active / Selected State:** Border 1px solid `#10b981`, background `rgba(16, 185, 129, 0.05)`.
- **Content Hierarchy:** Type badge (Text/Code/Link/Image) in `label-code-sm` at the top right; body snippet rendered in `label-code` for code or `body-md` for text; bottom metadata shows sync timestamp and device origin in `body-sm` (`#94a3b8`).

### Input Fields & Search Bars
- **Frame:** Background `#181a1f`, border 1px solid `#2d333b`, radius 8px, padding 8px 12px. Text `#f1f5f9`, placeholder `#64748b`.
- **Focus:** Border color `#10b981`, inner glow `0 0 0 1px #10b981`.
- **Trailing Shortcuts:** Includes `<kbd>` markers styled with `#262a32` background and `#94a3b8` text.

### Chips & Filters
- **Default:** Background `#181a1f`, border 1px solid `#2d333b`, text `#94a3b8`, radius 6px, padding 4px 8px.
- **Selected:** Background `rgba(16, 185, 129, 0.15)`, border 1px solid `#10b981`, text `#10b981`.

### Checkboxes & Toggle Switches
- **Checkbox:** 16x16px square, radius 4px, border 1px solid `#38414d`, background `#181a1f`. Checked state fills `#10b981` with a dark `#121417` checkmark icon.
- **Toggle Switch:** 36x20px capsule track in `#262a32`. Active track turns `#10b981`. Thumb is a 16px circle (`#f1f5f9`) transitioning with a 150ms ease curve.

### App-Specific: Sync Status Indicator & Shortcut Badges
- **Sync Indicator:** 8px circle. Green pulse (`#10b981`) for synced, amber (`#f59e0b`) for active transfer, slate (`#64748b`) for offline.
- **Shortcut Key (`<kbd>`):** Background `#181a1f`, border 1px solid `#2d333b`, border-bottom 2px solid `#38414d`, radius 4px, text `#94a3b8`, font `JetBrains Mono` 10px.