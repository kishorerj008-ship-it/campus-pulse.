---
name: CampusPulse Event Engine
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
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#4648d4'
  on-secondary: '#ffffff'
  secondary-container: '#6063ee'
  on-secondary-container: '#fffbff'
  tertiary: '#005338'
  on-tertiary: '#ffffff'
  tertiary-container: '#006e4b'
  on-tertiary-container: '#67f4b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#e1e0ff'
  secondary-fixed-dim: '#c0c1ff'
  on-secondary-fixed: '#07006c'
  on-secondary-fixed-variant: '#2f2ebe'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
The design system embodies the momentum, intellectual curiosity, and social vibrancy of contemporary collegiate life. It bridges structured academic authority with dynamic extracurricular social discovery. The aesthetic is clean, energetic, modern, and highly legible, borrowing functional clarity from top-tier SaaS platforms while infusing collegiate warmth and spontaneous student culture.

Visual pillars:
- **Kinetic Structure:** Information is modular, high-density, and scannable. Event schedules, maps, and tags are crisply contained.
- **Electric Accentuation:** High-energy indigo and electric violet tones command attention for key actions, live states, and trending activities, offset by grounded slate surfaces.
- **Approachable Modernity:** Soft, generous corner radii paired with micro-subtle atmospheric shadows make interacting with calendars, RSVPs, and student club cards feel tactile and fluid.

## Colors
The color architecture balances focused legibility with vibrant social signifiers. 

- **Primary (`#4F46E5`):** Deep Indigo. Used for primary calls-to-action, navigation active states, high-priority filters, and verified event markers.
- **Secondary (`#6366F1`):** Electric Iris. Used for interactive hover states, dynamic tags, live stream/now-happening badges, and gradient accents.
- **Tertiary / Success (`#10B981`):** Crisp Emerald. Dedicated strictly to affirmative states: confirmed RSVP, ticket claimed, free food/perks tags, and open capacity indicators.
- **Neutral Palette:** 
  - Canvas Surface: `#F8FAFC` (Slate 50) delivers an airy, clean foundation.
  - Surface Card / Raised: `#FFFFFF` (Pure White).
  - Borders & Dividers: `#E2E8F0` (Slate 200).
  - Muted Text & Icons: `#64748B` (Slate 500).
  - High-Contrast Body Text: `#1E293B` (Slate 800).
  - Headings & Primary Ink: `#0F172A` (Slate 900).

## Typography
The system balances structural personality and utilitarian speed. **Plus Jakarta Sans** provides a geometric, warm, and distinctly youthful quality to titles, display banners, and badges. **Inter** handles data tables, event itineraries, long-form descriptions, and metadata with unmatched neutral clarity at tight sizing.

Guidelines:
- All card titles, modal titles, and section headers use Plus Jakarta Sans with subtle negative letter-spacing for a modern, publication-grade feel.
- Metadata attributes (e.g., date, venue location, attendee counts) utilize Inter in `body-sm` or `caption` weights to ensure high-density scannability without visual fatigue.
- Tag and pill typography must use `label-sm` in bold or semibold uppercase/title-case to stand distinct from surrounding body prose.

## Layout & Spacing
The layout follows a 12-column responsive fluid grid designed for dashboard feeds, multi-column filters, and discovery hubs.

- **Breakpoints:**
  - **Mobile (< 768px):** 4-column layout. Gutter: `1rem` (`gutter-sm`), Margin: `1rem` (`margin-sm`). Reflows discovery feeds into vertical single-card stacks; filter controls transition into sticky bottom drawers.
  - **Tablet (768px – 1024px):** 8-column layout. Gutter: `1.5rem`, Margin: `1.5rem`. Enables side-by-side card viewing (2-column grids) with expandable filter banners.
  - **Desktop (> 1024px):** 12-column layout. Max container width: `1280px` centered. Gutter: `1.5rem`, Margin: `2rem`. Dedicated 3-column sticky sidebar for categories, calendars, and live campus alerts; 9-column grid for primary event cards (3 columns of 3 units).
- **Rhythm:** Spacing follows strict multiples of 4px/8px. Card inner padding is strictly `1.5rem` (`space-lg`) on desktop and `1rem` (`space-md`) on mobile.

## Elevation & Depth
Depth is constructed through ambient, soft-toned elevation rather than harsh skeuomorphic shading. The system layers pure white elements over a cool `#F8FAFC` foundation.

- **Level 0 (Flat / Canvas):** Surface color `#F8FAFC`. Zero elevation.
- **Level 1 (Default Cards & Containers):** Pure `#FFFFFF` fill with a crisp boundary outline (`1px solid #E2E8F0`) and an ambient tinted drop shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Hovered Cards & Segmented Controls):** Applied on active hover to elevate event cards: `0 10px 15px -3px rgba(79, 70, 229, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`. Note the subtle tinting of the primary indigo into the ambient spread.
- **Level 3 (Modals, Overlays, Floating Action Buttons):** `0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`. Accompanied by a frosted neutral backdrop scrim (`rgba(15, 23, 42, 0.4)` with `backdrop-filter: blur(8px)`).

## Shapes
A roundedness value of 2 defines the baseline geometry, creating friendly, modern, and ergonomic components.

- **Standard Base Elements:** Buttons, text fields, search bars, and dropdown menus use `0.5rem` (8px) to `0.75rem` (12px) corners.
- **Content Cards & Panels (`rounded-xl` / `rounded-2xl`):** Primary event discovery cards, club summary banners, and calendar flyouts use `1rem` (16px) or `1.25rem` (20px) to establish a friendly, contemporary consumer feel.
- **Badges, Avatar Cutouts, and Interactive Chips:** Styled as full pills (`9999px`) to cleanly contrast with rectangular content cards.
- **Image Assets:** Event cover thumbnails use nested radii: exactly `0.75rem` (12px) when seated inside a `1rem` (16px) parent card.

## Components

### Buttons
- **Primary:** Background `#4F46E5`, text `#FFFFFF`, font `label-md`. Height 44px (desktop) / 48px (mobile). Corner radius `0.75rem`. Subtle transition to `#4338CA` on hover.
- **Secondary / Ghost:** White background, `1px solid #E2E8F0`, text `#1E293B`. Hover state shifts surface to `#F1F5F9`.
- **Action (Success / RSVP):** Background `#10B981`, text `#FFFFFF`. Used strictly for "Attending" or "Check In" states.

### Chips & Badges
- **Campus Category Badges:** Pill-shaped (`rounded-full`), padding `4px 12px`. Light indigo tint background (`#EEF2FF`), text `#4F46E5`, font `label-sm`.
- **Status Badges (e.g., 'Happening Now'):** Electric pulse dot (4px green or secondary purple) + text. Background `#ECFDF5`, text `#065F46` for open; `#FEF2F2` / `#991B1B` for sold-out events.

### Event Cards
- Structured layout: Cover image with top-right pill tag (Free Food, Academic, Greek Life, Arts). Below the image: 
  - Date/time lockup with highlighted primary-color month/day square badge.
  - Title in `headline-sm` (`Plus Jakarta Sans`), 2-line clamp.
  - Location row with subtle map-pin icon and attendee facepile stack (+X others).
  - Hover state: Card shifts upward by 2px with Level 2 elevation and border color transitioning from `#E2E8F0` to `#C7D2FE`.

### Input Fields & Search Bars
- Background `#FFFFFF`, border `1px solid #CBD5E1`, corner radius `0.75rem`, height 44px. Font `body-md`.
- Focus ring: `2px solid #6366F1` with an outer soft halo `0 0 0 4px rgba(99, 102, 241, 0.15)`.
- Global campus search contains integrated category hotkeys (`Cmd + K`) badge in muted slate.

### Selection Controls (Checkboxes & Radios)
- Checkboxes: `0.375rem` (6px) rounded corners. When checked, filled with `#4F46E5` with a crisp white checkmark icon.
- Radios: Circular with concentric indigo dot indicator upon selection.

### Custom Component: Attendee Facepile & Capacity Tracker
- Overlapping 28px circular avatars bordered with 2px of pure `#FFFFFF`.
- Linear capacity progress bar: 6px height, rounded full, slate track `#E2E8F0` with fill indicator turning from `#4F46E5` to `#10B981` upon reaching confirmation thresholds.