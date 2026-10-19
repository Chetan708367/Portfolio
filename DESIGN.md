---
name: Obsidian Engineering
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#9699ff'
  on-tertiary-container: '#1d17b2'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 16px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
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
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses the craft, precision, and architectural discipline of a senior frontend engineer. Built around a refined dark tech aesthetic, it fuses deep slate-obsidian tones with restrained, electric neon pulses (emerald, cyan, and indigo/violet). 

The emotional signature is high-focus, technically sophisticated, and meticulously polished. Rather than aggressive cyber-brutalism, this system balances developer-centric utility with executive-tier aesthetic refinement:
- **Atmosphere:** Deep space, clean room laboratory, IDE-inspired clarity.
- **Visual Identity:** 1px precision hairline borders, micro-glows on interaction, subtle backdrop-filter translucency, and monospaced data accents.
- **Tone:** Confident, deliberate, functional, and modern.

## Colors

The palette leverages an obsidian base with calculated energetic accents, tuned strictly for high contrast readability and ergonomic low-light viewing:

- **Canvas & Base Neutrals:**
  - `canvas-base`: `#0B0F17` (Deepest void obsidian background)
  - `surface-primary`: `#111827` (Card and panel backgrounds)
  - `surface-elevated`: `#1F2937` (Floating overlays, sheets, code blocks)
  - `border-hairline`: `rgba(255, 255, 255, 0.08)` or `#1F2937` (Subtle frame delineation)
  - `border-focused`: `#374151` (Active or highlighted component strokes)

- **Accents & Roles:**
  - **Primary (`#10B981` Emerald):** Represents active build states, production readiness, terminal prompts, and affirmative CTAs.
  - **Secondary (`#06B6D4` Cyan):** Designates architecture nodes, API links, client-side metadata, and reactive highlights.
  - **Tertiary (`#6366F1` Violet / Indigo):** Designates deep logic, backend integration, experimental features, and decorative ambient radial gradients.

- **Typography & Content:**
  - `text-primary`: `#F9FAFB` (Highest contrast heading and body text)
  - `text-secondary`: `#9CA3AF` (Secondary narratives, timestamps, captions)
  - `text-muted`: `#6B7280` (Code comments, inactive icons, subtle indicators)

## Typography

Typography establishes an intentional contrast between the polished editorial sans-serifs and precise monospaced technical indicators:

- **Headlines (Plus Jakarta Sans):** Crafted with tight tracking and confident geometric weights to anchor section transitions and case study titles.
- **Body & Longform (Inter):** Highly legible, neutral, and structurally transparent, ensuring case study deep-dives remain easy to digest on mobile viewports.
- **Monospace Accents (JetBrains Mono):** Deployed for metrics, tags, timestamps, code snippets, micro-labels, and terminal outputs. All monospaced tags use uppercase transformations or lowercase variable naming formats (`v2.4.0`, `git:main`).

## Layout & Spacing

This mobile-first layout operates on a 4-column fluid mobile grid scaling to an 8-column layout for tablets.

- **Vertical Cadence:** Strict 4px/8px modular base rhythm.
- **Section Margins:** Handheld devices use a disciplined `1rem` outer horizontal gutter to maximize screen real estate, expanding to `1.5rem` on larger mobile and foldable displays.
- **Compact Density:** Structural spacing balances airiness with informational density. Project cards and stack chips are clustered using tight micro-spacers (`space-xs` and `space-sm`) to reflect software UI paradigms rather than loose marketing sites.

## Elevation & Depth

Depth is established through translucent dark layers and subtle surface-edge reflections instead of heavy drop shadows:

- **Layer 0 (Canvas):** Pure `#0B0F17`.
- **Layer 1 (Cards & Modules):** `#111827` at `85%` opacity with a `12px` backdrop blur and a crisp `1px` perimeter border colored `rgba(255, 255, 255, 0.08)`.
- **Layer 2 (Modals, Drawers, Flyouts):** `#1F2937` at `95%` opacity with a `24px` backdrop blur and border colored `#374151`.
- **Ambient Accent Glows:** Active elements cast an ethereal ambient radial glow:
  - Cyan nodes: `0 0 24px -4px rgba(6, 182, 212, 0.2)`
  - Emerald status pins: `0 0 12px 1px rgba(16, 185, 129, 0.35)`
  - Neon violet interactive cards: `0 8px 32px -8px rgba(99, 102, 241, 0.15)`

## Shapes

The interface embraces a modern, controlled roundedness level:

- **Containers & Project Cards:** Default to `0.5rem` (`8px`) or `rounded-lg` (`1rem` / `16px`) for larger panels, providing a sleek architectural frame that avoids toy-like softness.
- **Pills & Tech Stack Badges:** Full-radius pill shapes for micro-indicators, contrasting against the squared structural cards.
- **Interactive Buttons:** `rounded-lg` (`16px`) for touch ergonomics that comfortably nest along thumb zones.

## Components

### Buttons
- **Primary:** Surface filled with `linear-gradient(135deg, #10B981, #06B6D4)`, typography in `#0B0F17` (bold `Plus Jakarta Sans`), height `44px` minimum for mobile touch targets.
- **Secondary (Ghost Outline):** `1px` border in `#374151`, background `rgba(17, 24, 39, 0.6)` with backdrop blur, hover/active stroke transition to `#06B6D4`.
- **Icon / Terminal Quick-Action:** Square `40x40px`, background `#111827`, border `1px solid rgba(255,255,255,0.08)`, active state illuminates with an accent micro-glow.

### Tech Stack Chips & Badges
- **Display:** Height `24px`, horizontal padding `8px`, typography `label-caps` (`JetBrains Mono`).
- **Surface:** `rgba(255, 255, 255, 0.03)` with a `1px` border in `rgba(255, 255, 255, 0.07)`.
- **Variants:** Subtle colored dot indicators (2px diameter) prefixing the text (`#10B981` for active stack, `#06B6D4` for tooling, `#6366F1` for libraries).

### Project & Case Study Cards
- **Construction:** Outer container uses `1px` hairline stroke (`#1F2937`) against `#111827` base.
- **Header:** Features live project status tag (`[PROD]`, `[ARCHIVE]`, `[WIP]`) in monospaced caps alongside repository stats.
- **Feedback:** Tap triggers an instantaneous micro-scale (`0.985`) and an ambient highlight along the top border using a subtle linear gradient border mask.

### Code Snippets & Architecture Previews
- **Surface:** High-contrast `#070A0F` inset container with a subtle horizontal scroll indicator.
- **Header Bar:** Mac/terminal-inspired 3-dot window controls scaled to `8px` with monospaced file path indicator (e.g., `src/hooks/useVirtualizer.ts`).

### Form Inputs & Terminal Inputs
- **Base:** Dark obsidian background (`#0B0F17`), inner border `#1F2937`, text in `#F9FAFB`.
- **Focus:** `1px` crisp border in `#06B6D4` accompanied by a localized cyan shadow glow (`0 0 0 2px rgba(6, 182, 212, 0.15)`).
- **Prompt:** Prepended with green terminal prompt indicator (`❯_`).