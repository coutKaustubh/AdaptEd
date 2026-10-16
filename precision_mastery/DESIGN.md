---
name: Precision Mastery
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
  on-surface-variant: '#464554'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777586'
  outline-variant: '#c7c4d7'
  surface-tint: '#5148d7'
  primary: '#2a14b4'
  on-primary: '#ffffff'
  primary-container: '#4338ca'
  on-primary-container: '#c1beff'
  inverse-primary: '#c3c0ff'
  secondary: '#4f5c8e'
  on-secondary: '#ffffff'
  secondary-container: '#b7c4fd'
  on-secondary-container: '#435081'
  tertiary: '#553300'
  on-tertiary: '#ffffff'
  tertiary-container: '#744800'
  on-tertiary-container: '#ffb759'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#100069'
  on-primary-fixed-variant: '#372abf'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b7c4fd'
  on-secondary-fixed: '#071747'
  on-secondary-fixed-variant: '#374475'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
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
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
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
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-formula:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xxs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system establishes an academically rigorous yet approachable digital environment for Class 9 Mathematics. The interface merges the structural discipline of developer productivity tools (Linear-style crispness and micro-borders) with the instructional clarity of premium digital workspaces and bite-sized pedagogical feedback loops.

### Brand Personality & Emotional Objectives
- **Intellectual Rigor without Intimidation**: Mathematics presented through structured, bite-sized units that instill confidence rather than cognitive paralysis.
- **Clarity & Spatial Efficiency**: Clean, intentional micro-alignments, tight density where useful, and ample breathing room around conceptual formulas.
- **Mastery-Focused**: Visual feedback highlights progressive mastery stages (Evidence & Confidence metrics: Limited, Moderate, Strong) rather than superficial gamification badges.

### Visual Style
- **Structured Precision**: A refined hybrid of modern minimalism and structural modularity.
- **Micro-Delimiters**: 1px subtle borders (`#E2E8F0`) with crisp geometry, minimizing reliance on heavy drop-shadows.
- **Information Architecture**: Inspired by clear typographic hierarchies and modular metadata tags that organize formulas, learning objectives, and dynamic assessment workflows.

## Colors

The system uses a focused, purposeful color strategy designed to direct focus toward mathematical content while conveying diagnostic states clearly.

### Functional Palette
- **Canvas / Surface Background**: `#F8FAFC` (ultra-clean off-white slate)
- **Container / Card Surface**: `#FFFFFF` (crisp white for distinct visual grouping)
- **Primary / Brand Anchor**: `#4338CA` (Deep Indigo — active nodes, primary CTA states, mastery paths)
- **Secondary / Depth**: `#172554` (Deep Navy — headers, high-emphasis structural modules)
- **Tertiary / Accent**: `#F59E0B` (Warm Amber Orange — active streaks, hints, focus highlights)
- **Neutral Primary (Text)**: `#0F172A` (Slate 900 — high-contrast reading)
- **Neutral Secondary (Muted)**: `#64748B` (Slate 500 — metadata, instructional labels, passive borders)
- **Subtle Micro-Borders**: `#E2E8F0` (Slate 200 — container definitions, dividers)

### Diagnostic Feedback & Mastery Signals
- **Success / Strong Evidence**: `#059669` (Emerald — correct answers, verified mastery)
- **Warning / Moderate Evidence**: `#D97706` (Amber — partial understanding, revision prompts)
- **Critical / Limited Evidence**: `#E11D48` (Rose — diagnostic gaps, prerequisite alerts)

### State Conventions
- Interactive hover surfaces shift using an alpha-tinted overlay: `rgba(67, 56, 202, 0.04)`.
- Active focus rings implement an outer glow: `0 0 0 2px #FFFFFF, 0 0 0 4px #4338CA`.
- Disabled surfaces utilize `#F1F5F9` with text at `#94A3B8`.

## Typography

The typographic system relies on **Inter** for clean readability and balanced proportions across dense problem sets, step-by-step proofs, and telemetry dashboards. **JetBrains Mono** is reserved strictly for formulas, mathematical variables, and coordinate pairs to prevent visual confusion between numeric values (such as `1`, `l`, `I`, and `0`, `O`).

### Typographic Rules
- **Mathematical Formulations**: Mathematical notation embedded within narrative sentences adopts tabular numeric styling (`tnum`) and dedicated vertical alignment to maintain uniform baseline flow.
- **Labels and Badges**: All metadata labels (mastery tiers, chapter tags, diagnostic indicators) render in uppercase or semi-bold sentence case with adjusted letter spacing (`0.02em` to `0.04em`) for legibility at small scales.
- **Reading Length**: Core educational explanations and problem statements are constrained to a maximum width of `68ch` to minimize eye fatigue during extended study sessions.

## Layout & Spacing

The layout is grounded in a consistent 4px/8px modular scale, built to support both split-screen problem environments and broad analytical dashboards.

### Responsive Grids & Canvas Architecture
- **Desktop (1280px and above)**: 12-column fluid grid, `1.5rem` gutters, constrained to a maximum layout container of `1440px`. Used for dual-pane problem workspaces (problem canvas on the left, step-by-step scratchpad/workspace on the right).
- **Tablet (768px – 1279px)**: 8-column layout with `1.25rem` gutters and `1.5rem` outer margins. Side panels collapse into progressive slide-overs or tabbed views.
- **Mobile (< 768px)**: 4-column layout with `1rem` gutters and `1rem` outer canvas padding. Interactive assessment cards stack vertically.

### Rhythmic Density
- **Micro-spacing (`space-xxs` to `space-sm`)**: Used for tight groupings inside data chips, progress bar tracks, and badge internals.
- **Macro-spacing (`space-lg` to `space-2xl`)**: Dedicated exclusively to separating thematic math domains (e.g., Algebra vs. Coordinate Geometry) and parent module boundaries.

## Elevation & Depth

Visual hierarchy relies on crisp surface separation and subtle micro-borders rather than heavy blur shadows, maintaining a focused workspace suitable for prolonged study.

### Elevation Strategy
- **Layer 0 (Canvas Base)**: `#F8FAFC`. The foundational backdrop for all views.
- **Layer 1 (Card / Module Surface)**: Pure `#FFFFFF`, delineated by a continuous 1px micro-border (`#E2E8F0`). Flat elevation with a feather-light boundary shadow: `0 1px 2px 0 rgba(15, 23, 42, 0.04)`.
- **Layer 2 (Interactive Floating / Hover Cards)**: `#FFFFFF`, border shifts to `#CBD5E1`. Shadow: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`. Used when a student hovers over an interactive question card or diagnostic graph node.
- **Layer 3 (Overlays, Modals, & Hints)**: `#FFFFFF`, border `#CBD5E1`. Shadow: `0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`.
- **Tonal Inset Surfaces**: Diagnostic breakdown bars and scratchpad input areas use an inset background of `#F1F5F9` with an inner hairline border (`#E2E8F0`).

## Shapes

The design uses a restrained `Soft (1)` corner geometry (`0.25rem` base, up to `0.75rem` for major containers) to preserve the sharp, structured aesthetic of modern technical tools, with fully rounded pill radii reserved specifically for status badges.

### Corner Radii Hierarchy
- **Micro Radii (`0.25rem` / 4px)**: Checkboxes, formula blocks, tooltips, and table cell highlights.
- **Component Radii (`0.375rem` - `0.5rem` / 6px - 8px)**: Buttons, text input boxes, dropdown selectors, and question choice options.
- **Structural Radii (`0.75rem` / 12px)**: Question summary cards, diagnostic panels, and persistent navigation sidebars.
- **Pill Geometry (`9999px`)**: Evidence confidence badges, progress track endpoints, and topic navigation chips.

## Components

### Buttons
- **Primary**: Background `#4338CA`, foreground `#FFFFFF`, border: none. Height: 40px (desktop), 44px (mobile touch targets). Padding: `0 1rem`. Radius: `0.375rem`. Hover: `#3730A3`. Active: `#312E81`.
- **Secondary / Outline**: Background `#FFFFFF`, foreground `#0F172A`, 1px border `#E2E8F0`. Hover: background `#F8FAFC`, border `#CBD5E1`.
- **Ghost**: Background transparent, foreground `#4338CA`. Hover: background `rgba(67, 56, 202, 0.06)`.
- **Mastery Action (Next Question / Verify)**: Background `#172554`, foreground `#FFFFFF`, weight 600.

### Cards & Problem Containers
- Flat `#FFFFFF` background with a 1px uniform outline of `#E2E8F0`. Padding: `1.5rem` (`space-lg`).
- Interactive Question State (Selection): Selected state replaces border with a 2px stroke of `#4338CA` and a subtle wash background of `rgba(67, 56, 202, 0.02)`.

### Confidence & Evidence Badges (Pills)
- Rendered with `border-radius: 9999px`, height 24px, padding: `0 0.625rem`, typography: `label-sm`.
- **Strong Evidence**: Background `rgba(5, 150, 105, 0.10)`, text `#065F46`, border 1px solid `rgba(5, 150, 105, 0.25)`.
- **Moderate Evidence**: Background `rgba(217, 119, 6, 0.10)`, text `#92400E`, border 1px solid `rgba(217, 119, 6, 0.25)`.
- **Limited Evidence**: Background `rgba(225, 29, 72, 0.08)`, text `#9F1239`, border 1px solid `rgba(225, 29, 72, 0.25)`.

### Adaptive Progress Bars
- Container track: 6px height (or 8px for hero tracks), background `#E2E8F0`, rounded `9999px`.
- Fill track: `#4338CA` for curriculum completion; shifts to `#059669` when mastery benchmark (>85%) is achieved.
- Segmented Adaptive Track: Discontinuous 4px bars separated by 2px gaps, illustrating discrete learning objective milestones.

### Input Fields & Scratchpad Elements
- Border 1px `#CBD5E1`, background `#FFFFFF`, text `#0F172A`, padding: `0.5rem 0.75rem`.
- Focus ring: `0 0 0 1px #4338CA, 0 0 0 4px rgba(67, 56, 202, 0.12)`.
- Formula / Symbolic Math Inputs: Embedded with a monospaced font family, light slate background `#F8FAFC`, and inline validation cues.

### Checkboxes & Multiple Choice Radio Buttons
- Radios and Checkboxes share a consistent 18px footprint with a 1.5px border `#CBD5E1`.
- Checked state: `#4338CA` fill with crisp white internal icon/dot. Focus indicator conforms to component standards.

### Topic Navigation Chips
- Height 32px, padding `0 0.875rem`, border 1px `#E2E8F0`, background `#FFFFFF`, text `#64748B`.
- Active/Selected chip: Background `#172554`, text `#FFFFFF`, border-color `#172554`.