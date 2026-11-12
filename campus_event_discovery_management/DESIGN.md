---
name: Campus Event Discovery & Management
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
  on-surface-variant: '#494455'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#7a7486'
  outline-variant: '#cac3d7'
  surface-tint: '#663cdd'
  primary: '#5728cf'
  on-primary: '#ffffff'
  primary-container: '#7048e8'
  on-primary-container: '#ede4ff'
  inverse-primary: '#ccbdff'
  secondary: '#604ac1'
  on-secondary: '#ffffff'
  secondary-container: '#9984fd'
  on-secondary-container: '#2f088f'
  tertiary: '#0f45be'
  on-tertiary: '#ffffff'
  tertiary-container: '#365fd7'
  on-tertiary-container: '#e4e7ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e7deff'
  primary-fixed-dim: '#ccbdff'
  on-primary-fixed: '#1f005f'
  on-primary-fixed-variant: '#4d17c5'
  secondary-fixed: '#e6deff'
  secondary-fixed-dim: '#cabeff'
  on-secondary-fixed: '#1c0062'
  on-secondary-fixed-variant: '#482fa7'
  tertiary-fixed: '#dce1ff'
  tertiary-fixed-dim: '#b6c4ff'
  on-tertiary-fixed: '#00164e'
  on-tertiary-fixed-variant: '#003baf'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-display:
    fontFamily: Plus Jakarta Sans
    fontSize: 44px
    fontWeight: '800'
    lineHeight: 52px
  headline-display-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
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
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an energetic yet focused campus ecosystem tailored to students (*Mahasiswa*), event organizers (*Panitia*), and campus institutional administrators (*Admin*). Grounded in modern EdTech SaaS principles, the aesthetic balances the vibrant social momentum of student life with the structural rigor demanded by administrative oversight and ticketing operations.

### Design Principles
- **Elevated Clarity:** Interfaces prioritize high signal-to-noise ratios. Whitespace is active, giving breathing room to event posters, ticket statuses, and operational matrices.
- **Role-Calibrated Density:** Student views emphasize discovery, visual cards, and streamlined registration. Organizer and Admin views transition seamlessly into compact, metric-dense workspaces without breaking visual harmony.
- **Fluid Affordances:** Interactive surfaces communicate utility through subtle micro-elevations, tactile feedback, and crisp minimalist line iconography (1.5px stroke weight).

## Colors

The palette leverages high-vibrancy purples and tech-forward blues anchored against cool, clinical surfaces.

- **Primary Violet (`#7048E8`):** The primary interaction anchor for primary actions, active tabs, and identity highlights.
- **Deep Indigo (`#4930A8`):** Applied to high-emphasis interactive states (hover/press), authoritative headers, and elevated badges.
- **Accent Royal Blue (`#4169E1`):** Applied to real-time indicators, operational tags, calendar sync markers, and secondary calls-to-action.
- **Tinted Canvas (`#F8F9FF`):** Base backdrop for the entire application, mitigating eye strain while preserving high contrast against pure white cards.
- **Soft Lavender (`#F1EDFF`):** Structural fill for sub-panels, chip backgrounds, hovered list items, and selected radio states.
- **Surface Pure White (`#FFFFFF`):** Reserved strictly for elevated components, modals, form inputs, and interactive cards.

### Role-Based Access Badges
- **Mahasiswa:** Primary soft tint (`#F1EDFF`) with `#7048E8` text.
- **Panitia / Organizer:** Blue tint (`#EBF1FF`) with `#4169E1` text.
- **Admin:** Deep indigo tint (`#EDE9FE`) with `#4930A8` text and high-contrast outline.

## Typography

The type scale combines **Plus Jakarta Sans** for prominent, expressive display headings with **Inter** for data grids, metadata, labels, and high-readability body copy.

- **Plus Jakarta Sans** provides a welcoming, rounded, contemporary punch suited for campus culture, event headliners, and community branding.
- **Inter** ensures crisp optical clarity in dense tabular layouts, administrative verification queues, and ticket scanner feeds.
- Uppercase tracking (`0.05em`) is reserved exclusively for `label-sm` when used in status badges or role tags.

## Layout & Spacing

The system runs on a base-8 fluid grid architecture engineered for responsive cross-platform use:

- **Desktop (12 Columns, breakpoint ≥ 1024px):** Max container width `1280px`, `gutter` 1.5rem (`24px`), `margin` 2rem (`32px`). Admin dashboards use a fluid full-width layout with a fixed `260px` collapsed/expandable navigation sidebar.
- **Tablet (8 Columns, 768px – 1023px):** Fluid width with `gutter` 1.5rem (`24px`), `margin` 1.5rem (`24px`).
- **Mobile (4 Columns, < 768px):** Fluid layout with `gutter-mobile` 1rem (`16px`), `margin-mobile` 1rem (`16px`). Navigation migrates to a persistent bottom tab bar for students and organizers.

Grid cards reflow from 3 or 4 columns on desktop, to 2 columns on tablet, down to a single card stack on mobile.

## Elevation & Depth

Visual hierarchy uses ambient tinted shadows mixed with delicate boundary lines (`1px solid rgba(112, 72, 232, 0.08)`) to maintain structure across white surfaces.

- **Level 0 (Flat Canvas):** `#F8F9FF` background. No elevation.
- **Level 1 (Cards & Data Panels):** Background `#FFFFFF`, border `1px solid rgba(112, 72, 232, 0.08)`, shadow `0px 4px 16px -2px rgba(73, 48, 168, 0.04)`.
- **Level 2 (Interactive Hover & Dropdowns):** Shadow `0px 10px 24px -4px rgba(73, 48, 168, 0.08)`.
- **Level 3 (Modals, Overlays & Sticky Drawers):** Shadow `0px 20px 32px -8px rgba(30, 20, 70, 0.12)`.

## Shapes

The design system enforces a disciplined corner radius system centered on modern 12–16px roundedness to echo the soft curves of Plus Jakarta Sans.

- **Base Corner (`0.5rem` / 8px):** Small badges, inputs, table cell indicators, and tag filters.
- **Standard Medium (`rounded-lg` / 12px to 16px):** Action buttons, event discovery cards, floating toolbars, and administrative metric containers.
- **Prominent Container (`rounded-xl` / 20px to 24px):** Modals, hero event showcases, checkout bottom sheets, and major application frames.
- **Full Pill (`9999px`):** Avatar indicators, live event indicator chips, and interactive pill toggle bars.

## Components

### Buttons
- **Primary:** Background `#7048E8`, text `#FFFFFF`, radius `12px`, padding `0.75rem 1.5rem`. Hover shifts to `#4930A8` with elevation Level 2.
- **Secondary / Ghost:** Background `#F1EDFF`, text `#7048E8`. Hover shifts to `#E4DCFF`.
- **Outline:** Background transparent, border `1.5px solid #7048E8`, text `#7048E8`.

### Cards & Event Showcase
- Constructed with `#FFFFFF` background, `rounded-lg` (16px), and Level 1 elevation.
- Event banners within cards maintain a 16:9 aspect ratio with top corners clipped to match card borders (`16px`).
- Bottom metadata includes date pills, attendee avatars, and direct "Daftar" (Register) actions.

### Form Inputs & Selectors
- Standard height `44px`, background `#FFFFFF`, border `1px solid #E2E8F0`, corner radius `10px`.
- **Focus State:** Border color `#7048E8`, outer glow `0 0 0 3px rgba(112, 72, 232, 0.15)`.

### Chips & Role Tags
- Height `28px`, padding `0.25rem 0.75rem`, font `label-md`.
- Student tags: `#F1EDFF` with `#7048E8` text.
- Panitia tags: `#EBF1FF` with `#4169E1` text.
- Admin tags: `#4930A8` with `#FFFFFF` text.

### Verification & Check-in QR Scanner UI (Panitia/Admin)
- Viewfinder widget features curved neon corner guides (`#7048E8`), a high-contrast overlay (`rgba(15, 23, 42, 0.6)`), and quick ticket status banners (Valid: `#10B981`, Used: `#F59E0B`, Invalid: `#EF4444`).