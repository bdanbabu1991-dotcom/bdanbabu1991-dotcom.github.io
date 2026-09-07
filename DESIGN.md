---
name: Executive Analytics Dark
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#7bd0ff'
  on-secondary: '#00354a'
  secondary-container: '#00a6e0'
  on-secondary-container: '#00374d'
  tertiary: '#d0bcff'
  on-tertiary: '#3c0091'
  tertiary-container: '#a078ff'
  on-tertiary-container: '#340080'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#c4e7ff'
  secondary-fixed-dim: '#7bd0ff'
  on-secondary-fixed: '#001e2c'
  on-secondary-fixed-variant: '#004c69'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d0bcff'
  on-tertiary-fixed: '#23005c'
  on-tertiary-fixed-variant: '#5516be'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
  surface-base: '#0B0F19'
  surface-card: '#111827'
  surface-glass: rgba(17, 24, 39, 0.72)
  surface-elevated: '#1E293B'
  border-subtle: rgba(255, 255, 255, 0.08)
  border-glow: rgba(99, 102, 241, 0.35)
  accent-cyan: '#38BDF8'
  accent-violet-light: '#818CF8'
  text-primary: '#F8FAFC'
  text-secondary: '#94A3B8'
  text-muted: '#64748B'
  kpi-accent: '#22D3EE'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  stat-metric:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.03em
  stat-metric-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 32px
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-3xs: 0.125rem
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  container-padding-mobile: 1.25rem
  container-padding-tablet: 2rem
  gutter-mobile: 0.75rem
  gutter-desktop: 1.5rem
---

## Brand & Style

This design system establishes an executive-grade, technical portfolio interface crafted specifically for senior data analysts, BI consultants, and analytics leaders. The visual style merges **Glassmorphism** with **Modern Corporate Dark Mode**, projecting deep quantitative rigor, business acumen, and technical fluency. 

The aesthetic radiates precision, clarity, and authority. Deep cosmic navy surfaces ground the experience, while hyper-luminescent indigo, violet, and electric cyan accents guide the eye to pivotal metrics, architectural data pipelines, and project breakthroughs. The emotional response is one of unquestionable operational credibility and sophisticated modern engineering—delivering high signal-to-noise ratios across every viewport.

## Colors

The palette is engineered around deeply saturated dark backgrounds accented by high-energy spectral highlights:

- **Primary (`#6366F1` - Electric Indigo)**: Anchors primary call-to-actions, active navigation highlights, and interactive states.
- **Secondary (`#38BDF8` - Cyan Luster)**: Drives secondary interaction vectors, data visualizer accents, and technical metric callouts.
- **Tertiary (`#8B5CF6` - Vivid Violet)**: Provides contextual richness in badges, gradients, and analytical category headers.
- **Neutral (`#0B0F19` - Void Slate)**: Deep foundation color optimized for low eye fatigue during rigorous dashboard and mobile portfolio consumption.

### Application Guidelines
- Layer elevation progressively: background surfaces start at `#0B0F19`, transitioning to frosted containers at `#111827` (with `0.72` alpha blending), up to floating action panels at `#1E293B`.
- Content hierarchy relies strictly on `text-primary` (`#F8FAFC`) for titles and data figures, down to `text-secondary` (`#94A3B8`) for narrative summaries, avoiding raw uncalibrated white on pure black.

## Typography

Typography establishes a crystalline balance between executive punch and data clarity:

- **Headlines & KPI Metrics (`Plus Jakarta Sans`)**: Employs geometric weight, wide apexes, and modern proportions. Gives executive titles, project names, and key metrics immediate visual gravitas.
- **Body & Functional Microcopy (`Inter`)**: Delivers tall x-heights, distinct aperture contours, and optimal scanability for technical skill listings, architecture writeups, and dashboard summaries.
- **Metric Formatting**: Numerical data points leverage tabular figures (`tnum`) where comparative scanning is required.

## Layout & Spacing

The layout is built upon an uncompromising 8pt baseline grid with an integrated 4pt micro-subgrid for compact badges and icon aligners.

- **Mobile First Fluidity**: On mobile screens (`< 640px`), layouts run single-column card cascades with strict `1.25rem` (20px) outer edge margins, ensuring dense data delivery without horizontal cramping.
- **Skill Grids**: 2-column symmetric layout on mobile viewports scaling up to 4 or 6 columns on larger devices.
- **Metric Row Composition**: Mobile stat counters are grouped in horizontal micro-grids of 2 to 3 units, bounded by low-opacity divider strokes rather than heavy cards to maintain lightness.

## Elevation & Depth

Visual hierarchy does not rely on muddy drop-shadows; it is achieved through layered luminescence and translucent materials:

- **Base Canvas**: Absolute dark background (`#0B0F19`) featuring subtle radial mesh gradients in the upper quadrants (primary indigo and cyan blurs at 12% opacity).
- **Glassmorphic Panels**: Surfaces use `rgba(17, 24, 39, 0.72)` background fills paired with `backdrop-filter: blur(16px)` and a continuous hairline outline of `1px solid rgba(255, 255, 255, 0.08)`.
- **Luminous Active States**: Focus and hover states leverage an inner border glow (`rgba(99, 102, 241, 0.4)`) accompanied by an ambient perimeter bloom: `0 0 24px -4px rgba(99, 102, 241, 0.25)`.
- **Topmost Modals & Floating Menus**: Elevate to `#1E293B` with `0 20px 25px -5px rgba(0, 0, 0, 0.6)`.

## Shapes

The design system standardizes on an approachable yet disciplined **Rounded** geometry (scale factor 2):

- **Default Elements (Buttons, Inputs, Pill Badges)**: Feature a base radius of `0.5rem` (8px). Skill tags and chips utilize fully rounded pill contours (`rounded-full`).
- **Primary Content Cards**: Standardized at `rounded-xl` (`1rem` / 16px) to frame complex analytics projects and interactive graphs comfortably.
- **Modals and Hero Banners**: Feature large `rounded-2xl` (`1.5rem` / 24px) corners for an executive app feel.

## Components

### Buttons
- **Primary Button**: Solid gradient background running 135-degrees from `#6366F1` to `#8B5CF6`. Text in `#FFFFFF` with bold typography (`font-weight: 600`). Crisp 1px inner border highlight (`rgba(255, 255, 255, 0.2)`). Height: 44px on mobile for finger-friendly touch targets.
- **Secondary / Outlined Button**: Frosted background (`rgba(255, 255, 255, 0.03)`), border `1px solid rgba(99, 102, 241, 0.4)`. Text in `#818CF8`. Hover/Active state introduces a subtle indigo glow and text shift to `#FFFFFF`.

### Metric Counters (Stats Grid)
- **Container**: Minimal borderless or subtly bordered glass panel.
- **Number**: Rendered in `stat-metric` styling with high contrast `#F8FAFC`, optionally sporting a gradient mask (white fading to `#38BDF8`).
- **Label**: Positioned below the number in `label-sm` uppercase styling with `text-muted` (`#94A3B8`) and wide letter spacing (`0.05em`).

### Skill & Tech Tags
- **Appearance**: Pill-shaped badges (`rounded-full`) with a subtle dark backdrop (`#1E293B`), 1px perimeter stroke (`rgba(56, 189, 248, 0.2)`), and text styled in `#38BDF8` or `#818CF8`.
- **Tool Chips (SQL, Python, Power BI, DAX)**: Display a crisp colored icon on the left (18x18px) followed by 12px semi-bold typography.

### Project & Portfolio Cards
- **Structure**: Glassmorphic container with 16px border-radius, incorporating a preview media frame (dashboard viewport) with an integrated gradient overlay.
- **Content Area**: Features project headline in `headline-sm`, high-density descriptive body, technology pill rack, and an explicit action anchor ("View Project →") with hover-activated directional translate.

### Input Fields & Contact Anchors
- **Inputs**: Dark slate base (`#0F172A`), `1px solid rgba(255, 255, 255, 0.1)`, transitioning to `border-color: #6366F1` with an ambient cyan glow upon focus.
- **Action Tiles (Email, LinkedIn, Phone)**: High-touch cards with an icon tile bathed in deep indigo, clear label hierarchy, and immediate copy-to-clipboard or external-link behaviors.