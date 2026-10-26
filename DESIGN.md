---
name: Cybernetic Velocity
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
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00a572'
  on-tertiary-container: '#00311f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Space Grotesk
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system embodies high-throughput infrastructure, digital telemetry, and automated social media growth operations. Built for power users, service brokers, and digital agencies, the interface prioritizes algorithmic speed, operational clarity, and precision-engineered density. 

The aesthetic blends **Dark Cyberpunk Utility** with **Ultra-Modern SaaS Glassmorphism**. Deep oceanic navy backdrops establish a low-fatigue workspace for extended nocturnal sessions. Crisp, semi-translucent glass membranes, luminescent cobalt and violet conduits, and calibrated border illumination direct focal energy directly toward transactional velocity and state changes.

Key design principles:
- **Kinetic Precision:** Every indicator, telemetry chart, and status pulse communicates live processing.
- **Controlled Luminescence:** Neon accents (#3B82F6, #8B5CF6) serve as active states and data calls, never passive decoration.
- **Architectural Density:** Information packaging optimizes screen real estate for massive service catalogs, log streams, and order queues without visual clutter.

## Colors

The palette establishes high-contrast optical hierarchy against multi-tiered dark surfaces:

- **Canvases & Surfaces:** Canvas background rests on `#0B0F19`, with secondary container panels stepping up to `#111827` and higher elevated popovers/dialogs at `#1E293B`.
- **Primary Conduits (Electric Blue):** `#3B82F6` and `#4F46E5` anchor primary actions, active telemetry lines, progress bars, and high-priority focus rings.
- **Secondary Luminescence (Vivid Violet):** `#8B5CF6` and `#A855F7` distinguish service category tags, API key visualizers, special promotional balances, and secondary metric spikes.
- **Status Tiers:**
  - Success/Completed: Emerald Green (`#10B981`) for completed tasks, balance increments, and operational endpoints.
  - In-Progress/Pending: Amber (`#F59E0B`) for processing batches, API rate throttles, and queued tasks.
  - Error/Cancelled: Rose (`#EF4444`) for failed webhooks, depleted balance, and order cancellation.
- **Structural Lines:** Borders utilize refined slate tones (`#1E293B` default, `#334155` hover/active) to maintain strict geometric boundaries without stark visual breaks.

## Typography

The typographic hierarchy establishes clear structural zoning:

- **Space Grotesk** serves as the display engine. Its geometric, slightly mechanical proportions give dashboard analytics, panel cards, and section banners an authoritative, high-tech punch.
- **Geist** handles standard operational prose, descriptive tooltips, form labels, and table content, selected for its neutral readability, neutral contrast, and precision screen rendering.
- **JetBrains Mono** drives all telemetry: order IDs, price rates per 1,000, API keys, JSON payload inspectors, timestamps, and order status tallies.

Rules for implementation:
- All financial balances and volumetric counters must be styled with tabular figures using the label or monospace family to prevent horizontal jitter during real-time balance streaming.
- Monospace subheads must be styled in uppercase with letter-spacing for category kickers (`label-sm`).

## Layout & Spacing

The layout model is governed by a responsive **fluid-to-structured grid system** calibrated for multi-pane management, high-volume tables, and operational stats:

- **Desktop (1280px+):** 12-column dynamic fluid layout with `1.5rem` gutters, pinned collapsible command sidebar (width: 260px or collapsed to 72px), and variable content pane.
- **Tablet (768px – 1279px):** 8-column layout with `1rem` gutters. Metric cards reflow into a 2x2 matrix; secondary sidebars collapse to slide-out drawers.
- **Mobile (<768px):** 4-column layout with `1rem` canvas margins. Tables switch to card-based horizontal scrolls or stacked key-value summaries. Quick-action order submission bars pin to the bottom sheet.

Vertical rhythm adheres strictly to 4px/8px baselines. Data tables leverage ultra-compact vertical cell paddings (`space-sm`) to maximize visible records above the fold.

## Elevation & Depth

This design system avoids heavy opaque shadows, leaning instead on **translucent backdrop blurs, luminous edge refraction, and multi-tier ambient glow**:

- **Ground Level (Base Canvas):** Pure solid `#0B0F19`. Un-elevated.
- **Tier 1 (Cards, Tables, Containers):** Background `rgba(17, 24, 39, 0.75)` overlaid with a `backdrop-filter: blur(16px)` and a crisp perimeter border `1px solid rgba(51, 65, 85, 0.6)`.
- **Tier 2 (Popovers, Select Menus, Flyouts):** Background `rgba(30, 41, 59, 0.90)` with `backdrop-filter: blur(24px)`, bordered with `1px solid rgba(99, 102, 241, 0.3)` and an ambient drop-glow: `0 12px 32px -4px rgba(0, 0, 0, 0.65), 0 0 16px -2px rgba(59, 130, 246, 0.15)`.
- **Active & Focus Glows:** Active input fields, focused table rows, and interactive buttons cast an external optical halo: `box-shadow: 0 0 0 1px #3B82F6, 0 0 14px 0 rgba(59, 130, 246, 0.4)`. Violet variants cast `0 0 14px 0 rgba(139, 92, 246, 0.4)`.

## Shapes

The design system implements a refined, geometric corner radius profile (`roundedness: 2`):

- **Default Element Radius (`0.5rem` / 8px):** Applied to inputs, standard buttons, badge containers, filter chips, and dropdown selections.
- **Container Radius (`rounded-lg` / `1rem` / 16px):** Standard for analytical cards, modular data panes, modal frames, and dynamic order sheets.
- **Nested Inner Surfaces (`rounded-sm` / `0.25rem` / 4px):** Code snippets, table row selection highlights, and micro status pills.
- **Full Radius (Pill):** Reserved exclusively for live status beacons, connection health pings, and notification quantity counters.

## Components

### Buttons
- **Primary Cyber:** Linear gradient background from `#3B82F6` to `#4F46E5`. White text (`Geist Medium`), `0.5rem` radius, subtle top-edge highlight (`inset 0 1px 0 rgba(255, 255, 255, 0.2)`). Hover casts a concentrated electric blue halo: `0 0 20px rgba(59, 130, 246, 0.5)`.
- **Secondary Luminescent:** Transparent glass fill with `1px solid rgba(139, 92, 246, 0.4)` border. Violet text (`#A855F7`). Hover triggers `rgba(139, 92, 246, 0.1)` background tint and full border brightness.
- **Ghost/Tertiary:** No border, transparent canvas, slate-300 text. Hover triggers `rgba(30, 41, 59, 0.6)` surface fill.

### Data Tables (Dense Operational Grid)
- **Container:** Dark glassmorphic frame with sticky headers.
- **Headers:** Monospaced `label-sm` font, all caps, text color `#64748B`, bottom border `1px solid #1E293B`, subtle background `rgba(11, 15, 25, 0.8)`.
- **Rows:** Height set to 44px for high density. Default row alternating between pure `#111827` and subtle `#0F172A`. Hover transitions row surface to `rgba(59, 130, 246, 0.05)` with an active left edge border of 2px in `#3B82F6`.
- **Numbers & Rates:** Formatted strictly with `JetBrains Mono` right-aligned.

### Input Fields & Selectors
- **Base State:** Background `rgba(15, 23, 42, 0.8)`, border `1px solid #334155`, text `#F8FAFC`, placeholder `#475569`.
- **Active / Focus:** Border shifts to `#3B82F6` with an electric blur halo (`0 0 12px rgba(59, 130, 246, 0.35)`).
- **Service Selector Dropdown:** Includes categorized icon prefixes (Instagram, YouTube, Telegram, TikTok) with small neon indicator pings for API status (instant vs slow start).

### Status Badges & Chips
- **Success (Completed):** Background `rgba(16, 185, 129, 0.12)`, border `1px solid rgba(16, 185, 129, 0.3)`, text `#10B981`. Accompanied by a static emerald dot beacon.
- **Pending / Processing:** Background `rgba(245, 158, 11, 0.12)`, border `1px solid rgba(245, 158, 11, 0.3)`, text `#F59E0B`. Accompanied by a pulsing amber dot.
- **Failed / Cancelled:** Background `rgba(239, 68, 68, 0.12)`, border `1px solid rgba(239, 68, 68, 0.3)`, text `#EF4444`.

### Metrics & Telemetry Cards
- **Structure:** Surface `rgba(17, 24, 39, 0.65)`, blurred at 16px, framed in `1px solid #1E293B`.
- **Header:** Uppercase category label in `label-sm` slate text, followed by massive metric display in `Space Grotesk` (`headline-md`).
- **Footer:** Inline mini sparkline or telemetry trend graph bathed in an electric blue or violet fill gradient fading to alpha 0 at the base.