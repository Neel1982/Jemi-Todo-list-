---
name: Serene Focus
colors:
  surface: '#fcf8ff'
  surface-dim: '#dad8ef'
  surface-bright: '#fcf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f2ff'
  surface-container: '#efecff'
  surface-container-high: '#e8e6fd'
  surface-container-highest: '#e3e0f7'
  on-surface: '#1a1a2a'
  on-surface-variant: '#474553'
  inverse-surface: '#2f2f40'
  inverse-on-surface: '#f2efff'
  outline: '#787584'
  outline-variant: '#c9c4d5'
  surface-tint: '#5d4cbf'
  primary: '#5c4bbe'
  on-primary: '#ffffff'
  primary-container: '#7565d9'
  on-primary-container: '#ffffff'
  inverse-primary: '#c8bfff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#825400'
  on-tertiary: '#ffffff'
  tertiary-container: '#a36a00'
  on-tertiary-container: '#ffffff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5deff'
  primary-fixed-dim: '#c8bfff'
  on-primary-fixed: '#190064'
  on-primary-fixed-variant: '#4531a6'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb5'
  tertiary-fixed-dim: '#ffb956'
  on-tertiary-fixed: '#2a1800'
  on-tertiary-fixed-variant: '#633f00'
  background: '#fcf8ff'
  on-background: '#1a1a2a'
  surface-variant: '#e3e0f7'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.03em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.0625rem
    fontWeight: '400'
    lineHeight: 1.625rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies mindful productivity, order, and cognitive ease. Tailored for students, researchers, and busy knowledge workers navigating daily overwhelm, the visual language intentionally reduces visual stimulation to cultivate a tranquil mental space.

The aesthetic fuses warm, Scandinavian-inspired modern minimalism with functional clarity:
- **Calm & Unhurried:** Eliminates competitive visual noise, high-saturation accents, and abrupt transitions. Interfaces feel grounded, spacious, and deliberate.
- **Pure Tangibility:** Zero frosted glass, zero iridescent gradients, and zero decorative visual clutter. Surfaces rely on tactile, paper-like clean white planes suspended gently over warm off-white canvas tones.
- **Quiet Guidance:** Micro-interactions and accents serve strictly to inform and guide, employing muted lavender tones and gentle emerald completions rather than loud demanding alerts.

## Colors

The palette is tuned specifically for sustained daylight focus and evening study sessions without retinal fatigue.

### Color Tokens & Assignments
- **Canvas / Page Background:** `#F7F7FB` — A balanced, warm-neutral off-white that softens interface contrast compared to harsh pure white.
- **Surface (Cards & Modals):** `#FFFFFF` — Crisp, pure white planes that float with clear boundary definition over the canvas.
- **Primary Accent:** `#7565D9` (Soft Lavender-Purple) — Anchor for primary actions, active filters, and focused states.
  - Primary Hover: `#6353C7`
  - Primary Subtle Surface / Badges: `#F1EFFF`
  - Primary Subtle Text: `#5B4BB8`
- **Secondary / Success:** `#10B981` (Soft Sage Emerald) — Task completion states, streak milestones, and positive feedback indicators.
  - Success Soft Background: `#ECFDF5`
  - Success Muted Border: `#A7F3D0`
- **Neutrals & Text Hierarchy:**
  - Text Primary: `#252536` — Deep slate-charcoal; delivers high legibility without the starkness of pure black `#000000`.
  - Text Secondary / Muted: `#717182` — Calm, balanced slate for meta-information, secondary timestamps, and placeholder states.
  - Border Subtle: `#ECECF2` — Baseline structural perimeter line for cards and container boundaries.
  - Border Interactive: `#E2E2EA` — Visible boundary for idle text inputs, toggle outlines, and dividers.

## Typography

The design system utilizes **Plus Jakarta Sans** throughout all display, body, and label roles. Its geometric foundation combined with subtly softened terminals offers a welcoming, human feel while maintaining strict structural clarity for dense task schedules and lists.

### Implementation Guidelines
- **Comfortable Reading Rhythm:** Body sizes use increased line-heights (minimum 1.5× to 1.6× ratio) to let multi-line task notes and descriptions breathe.
- **Understated Weights:** Never use weights heavier than 700. Reserve 700 exclusively for page titles and milestone counters. Body copy remains at 400, while interactive links and meta chips utilize 500 or 600.
- **Completed Task States:** When a task is resolved, apply strikethrough styling accompanied by a transition to `text-secondary` (`#717182`) to demote visual prominence without illegibility.

## Layout & Spacing

Layouts adhere to an airy, uncluttered 12-column responsive fluid grid designed to prevent dense visual clustering.

### Grid Architecture & Breakpoints
- **Desktop (≥ 1024px):** 12 columns, `margin: 2.5rem`, `gutter: 1.5rem`. Max application content wrapper is capped at `1200px` for optimal eye travel. The persistent left navigation rail occupies 256px fixed width, leaving the remaining viewport to dynamic task views and calendar panels.
- **Tablet (768px - 1023px):** 8 columns, `margin: 2rem`, `gutter: 1.25rem`. Navigation collapses to an icon bar or drawer.
- **Mobile (< 768px):** 4 columns, `margin: 1.25rem`, `gutter: 1rem`. Bottom tab bar handles primary destinations; todo stacks collapse to full-width card structures.

### Spacing Philosophy
White space is treated as an active functional component, not empty void. Ample gaps (`space-lg` and `space-xl`) isolate different project groups or daily time blocks, preventing cognitive fatigue.

## Elevation & Depth

Depth in this design system is gentle and tactile, constructed by balancing fine structural outlines with ambient, warm light diffusion. High-contrast drop shadows and hard black blurs are strictly prohibited.

### Tiers of Depth
- **Level 0 (Flat Canvas):** `#F7F7FB` background with zero shadow.
- **Level 1 (Resting Cards & Todo Items):** Crisp `#FFFFFF` surface accompanied by a 1px solid border (`#ECECF2`) and a micro-diffused ambient shadow:
  - `box-shadow: 0 1px 3px 0 rgba(37, 37, 54, 0.03), 0 4px 12px 0 rgba(37, 37, 54, 0.02);`
- **Level 2 (Hovered Cards & Interactive Rows):**
  - `box-shadow: 0 2px 6px 0 rgba(117, 101, 217, 0.04), 0 8px 20px 0 rgba(37, 37, 54, 0.05);`
  - Subtle upward translation of `translateY(-1px)`.
- **Level 3 (Floating Action Menus, Modals & Popovers):** Pure white surface bounded by `#ECECF2`, elevated above a soft backdrop dimming overlay (`rgba(37, 37, 54, 0.20)`):
  - `box-shadow: 0 12px 32px -4px rgba(37, 37, 54, 0.08), 0 4px 12px -2px rgba(37, 37, 54, 0.04);`

## Shapes

The design system embraces an approachable, rounded-corner geometry that softens productivity workflows while maintaining orderly modular grids.

### Shape Scale Rules
- **Base Components (`rounded` / 0.5rem - 8px):** Checkbox boxes, inner input fields, micro date badges, and icon buttons.
- **Medium Components (`rounded-lg` / 1rem - 16px):** Todo card rows, popover menus, banner callouts, and modal interiors.
- **Large Containers (`rounded-xl` / 1.5rem - 24px):** Primary dashboard content cards, side drawer sheets, and major section groupings.
- **Pill Geometry (`rounded-full` / 9999px):** Status chips, project categories, quick-add floating trigger buttons, and avatar circles.

## Components

### Buttons
- **Primary:** Solid `#7565D9` background, white label text, `border-radius: 9999px` (pill) or `0.75rem`. Hover transitions to `#6353C7`. Focus ring displays a 2px offset outline of `rgba(117, 101, 217, 0.40)`.
- **Secondary / Subtle:** Surface `#F1EFFF` with `#5B4BB8` text. Hover transitions to `#E6E3FC`.
- **Ghost:** Transparent background with `#717182` text. Hover shifts to `#F7F7FB` surface and `#252536` text.

### Checkboxes
- **Idle:** 20px × 20px rounded square (`rounded: 6px`) with 1.5px solid border `#E2E2EA` on `#FFFFFF` base. Hover shifts border to `#7565D9`.
- **Checked (Active/Success):** Fills smoothly with `#10B981` (soft emerald) or `#7565D9` with a clean white micro-checkmark icon. Triggers a delicate strike-through and 40% opacity fade on the associated task title.

### Chips & Badges
- Tag pills with `font-size: 0.75rem`, `padding: 0.25rem 0.75rem`, and full rounded corners.
- Category pills use tint pairings:
  - Study / Work: `#F1EFFF` background with `#5B4BB8` text.
  - Urgent / Priority: `#FEF2F2` background with `#DC2626` text.
  - Personal / Balance: `#ECFDF5` background with `#059669` text.

### Input Fields
- Surface is `#FFFFFF` with a 1px border of `#E2E2EA` and `rounded: 0.75rem`.
- Padding is `0.75rem 1rem`. Placeholder text is colored in `#717182`.
- Active focus state transitions border color to `#7565D9` and provides a non-intrusive shadow ring (`0 0 0 3px rgba(117, 101, 217, 0.15)`).

### Todo Cards & Task Rows
- Encased in `#FFFFFF` with 1px `#ECECF2` outline and Level 1 elevation shadow.
- Interior items align with flex rows: checkbox on left, title and description centered, metadata chips and due date aligned to the right.
- Drag-and-drop handles remain invisible until mouse hover, maintaining a clutter-free reading scan.

### Progress & Streak Trackers
- Minimalist linear bars: 6px height with `#ECECF2` track and `#10B981` or `#7565D9` smooth indicator fill.
- Streak counters feature clean, monospaced digits paired with a small subtle icon, celebrating progress gently without hyperactive animations.