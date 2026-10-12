---
name: Quiet Real-Time Utility
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#3d4a42'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6d7a72'
  outline-variant: '#bccac0'
  surface-tint: '#006c4a'
  primary: '#006948'
  on-primary: '#ffffff'
  primary-container: '#00855d'
  on-primary-container: '#f5fff7'
  inverse-primary: '#68dba9'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#00685f'
  on-tertiary: '#ffffff'
  tertiary-container: '#008378'
  on-tertiary-container: '#f4fffc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#85f8c4'
  primary-fixed-dim: '#68dba9'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#005137'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#89f5e7'
  tertiary-fixed-dim: '#6bd8cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#005049'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  code-editor:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  code-meta:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
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

The design system embodies calm utility, immediacy, and friction-free focus. Tailored for engineers, writers, and knowledge workers who treat copy-paste as a primary cognitive workflow, the interface recedes entirely into the background so user data commands total focus. 

The aesthetic marries clinical minimalism with soft physical precision. It uses crisp whitespace, deliberate structural alignment, and whisper-quiet micro-interactions rather than loud decorative flourishes. Real-time synchronicity is communicated through subtle status micro-animations and an emerald-mint signal rather than flashy indicators. The tone is quiet, ultra-responsive, and relentlessly dependable.

## Colors

The palette is anchored by a pure paper white canvas (`#FFFFFF`) framed by zinc/slate neutrals, paired with a functional mint emerald accent (`#059669`) that conveys live connection and validated states.

- **Canvas & Surface Base:** Pure White (`#FFFFFF`) for active edit planes; Neutral Surface Subdued (`#F8FAFC`) for secondary sidebars and structural framing; Neutral Surface Muted (`#F1F5F9`) for inactive pills and hover highlights.
- **Hairline Outlines:** Strict hairline borders (`#E2E8F0` / `#CBD5E1`) partition panes cleanly without relying on visual weight or heavy shadows.
- **Text & Foreground:** Deep Slate (`#0F172A`) for primary readability; Neutral Slate (`#64748B`) for metadata, shortcuts, and character counts; Subtle Slate (`#94A3B8`) for placeholders and passive status text.
- **Functional Sync Accent:** Fresh Mint Emerald (`#059669`) provides high-contrast, WCAG AA-compliant real-time feedback (active socket pulses, successful sync rings, copy feedback). Deep Teal (`#0D9488`) acts as an interactive state tint.

## Typography

The typographic hierarchy utilizes a dual-engine structure:
1. **Interface Engine (`Inter`):** Handles UI chrome, global navigational bars, control menus, metadata labels, and modal dialogues. It is tuned for dense readability and neutral voice.
2. **Buffer Engine (`JetBrains Mono`):** Dedicated to raw clipboard entries, snippet previews, keyboard shortcut markers, and sync timestamps. Its strict fixed metrics ensure zero horizontal jump during live remote edits and clean tabular rendering of code snippets, URLs, or structured data.

Large display typography is kept restrained; scale steps remain tight to preserve maximum vertical space for user content.

## Layout & Spacing

The layout is built upon an adaptive utility grid with a strict 4px/8px baseline rhythm:
- **Canvas Boundaries:** Mobile views use a full-bleed layout with `1rem` outer safe margins. Desktop viewports switch to a fixed-sidebar (`280px` or `320px`), full-height central editor canvas, and an optional collapsible auxiliary panel.
- **Responsive Handling:** 
  - **Mobile (< 768px):** Single-column stacked state. History items appear in a bottom sheet or a top drawer toggled via the header. Active clip editor occupies 100% viewport height minus top action bar.
  - **Tablet (768px - 1024px):** Split-view with a condensed 240px snippet list and a responsive editor canvas.
  - **Desktop (> 1024px):** Fixed-width left utility navigation, central responsive clipboard editor, and a contextual right rail for item telemetry (QR code, device sync count, expiration controls).
- **Breathing Space:** Spacing inside work planes relies on generous inner paddings (`space-lg` to `space-xl`) to establish an uncluttered, zen-like typing and viewing environment.

## Elevation & Depth

Visual hierarchy is maintained without heavy directional drop shadows or intense surface bevels. Depth is articulated via a three-tier plane model:

1. **Substrate (Flat Hairlines):** Canvas surfaces and cards sit on `#FFFFFF` and are bounded by precise 1px borders in `#E2E8F0`. Spatial separation between editor zones is strictly structural.
2. **Interactive Lift (Whisper Shadows):** Temporary overlays, floating toolbars, and search palettes utilize an ambient, ultra-diffused shadow tinted with slate: `0 4px 20px -2px rgba(15, 23, 42, 0.04), 0 2px 6px -1px rgba(15, 23, 42, 0.02)`.
3. **Active Focus & Modals:** Dropdowns and quick-command modals float with a crisp hairline border and soft ambient halo (`0 12px 32px -4px rgba(15, 23, 42, 0.06)`), backdropped by an ultra-subtle translucent wash (`rgba(255, 255, 255, 0.8)` with an 8px blur).

## Shapes

The design system adopts a balanced, refined curvature:
- **Core Elements (Inputs, Buttons, Cards):** Standardized at `8px` (`roundedness: 2` scale) to deliver a modern, approachable feel while maintaining structural sharpness.
- **Nested Groups (Clipboard Panels, Code Blocks):** Outer containers employ `12px` to cleanly frame inner elements using the `8px` radius without corner-tangency conflicts.
- **Pills & Badges:** Monospace status chips, shortcut tags, and sync indicators retain full circular caps (`9999px`) to visually differentiate metadata from actionable rectangular controls.

## Components

### Buttons
- **Primary Action (e.g., "Copy", "New Clip"):** Background `#059669`, text `#FFFFFF`, radius 8px, hover `#047857`. Zero border. Micro-scale press feedback (`transform: scale(0.98)`).
- **Secondary / Ghost:** Transparent background with 1px border `#E2E8F0`, text `#0F172A`, hover background `#F8FAFC` and border `#CBD5E1`.
- **Icon / Utility Actions:** Ghost style, 32x32px square bounding box, radius 6px, slate icon `#64748B`, transition to text `#0F172A` on hover.

### Chips & Badges
- **Sync Status Dot:** 6px circular dot (animated pulse when synchronizing, solid `#059669` when connected, `#94A3B8` when offline) paired with a `code-meta` text label inside an 8px vertical-padded pill.
- **Format Chips (Plain, Markdown, Code, JSON):** Height 22px, background `#F1F5F9`, text `#475569`, borderless, font `JetBrains Mono` 11px.

### Clipboard History List
- **List Item:** Padded cell (`space-md`), separated by 1px `#F1F5F9` divider. Active item highlighted with `#F8FAFC` background and a 2px left border accent in `#059669`.
- **Preview:** Single-line clamped preview rendered in monospaced body, with a contextual timestamp (`2m ago`, `Just now`) floating right in `#94A3B8`.

### Input & Text Editor Area
- **Primary Content Buffer:** Borderless, clean canvas with `padding: space-xl`. No resize handle on auto-growing desktop canvas. Caret colored in `#059669`.
- **Search & Quick Jump Field:** 36px height, rounded 8px, border 1px `#E2E8F0`, subtle background `#F8FAFC`. Focus transitions border to `#059669` with an emerald focus-ring glow of 2px (`rgba(5, 150, 105, 0.15)`).

### Toggle Controls & Switches
- **Real-time Sync Switch:** 36x20px capsule track. Unchecked state `#CBD5E1`, checked state `#059669`. Thumb is 16px pure white circle with 1px shadow.

### Toast / Ephemeral Feedback
- **Feedback Banner ("Copied to clipboard"):** Floating bottom-center capsule, dark slate base (`#0F172A`), white text, accompanied by a mint checkmark icon. Appears for 1.8 seconds with a subtle vertical translate slide.