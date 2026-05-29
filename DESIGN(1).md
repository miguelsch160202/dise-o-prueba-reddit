---
name: Lumina Narrative
colors:
  surface: '#f7fafc'
  surface-dim: '#d7dadc'
  surface-bright: '#f7fafc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f6'
  surface-container: '#ebeef0'
  surface-container-high: '#e5e9eb'
  surface-container-highest: '#e0e3e5'
  on-surface: '#181c1e'
  on-surface-variant: '#5b403a'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f3'
  outline: '#8f7069'
  outline-variant: '#e3beb6'
  surface-tint: '#b52603'
  primary: '#b52603'
  on-primary: '#ffffff'
  primary-container: '#ff5a36'
  on-primary-container: '#5a0c00'
  inverse-primary: '#ffb4a3'
  secondary: '#585e6c'
  on-secondary: '#ffffff'
  secondary-container: '#dde2f3'
  on-secondary-container: '#5e6473'
  tertiary: '#545f72'
  on-tertiary: '#ffffff'
  tertiary-container: '#8893a8'
  on-tertiary-container: '#212c3d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad2'
  primary-fixed-dim: '#ffb4a3'
  on-primary-fixed: '#3d0600'
  on-primary-fixed-variant: '#8c1900'
  secondary-fixed: '#dde2f3'
  secondary-fixed-dim: '#c1c6d7'
  on-secondary-fixed: '#161c27'
  on-secondary-fixed-variant: '#414754'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#f7fafc'
  on-background: '#181c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-reading:
    fontFamily: Newsreader
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 32px
  body-ui:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  container-max-width: 1200px
  reading-width: 680px
---

## Brand & Style

The design system is built to facilitate the dual nature of a community-driven news and writing platform: the urgency of information and the immersion of storytelling. The brand personality is **vibrant, intellectual, and inviting**, aiming to lower the barrier for new writers while providing a professional stage for established voices.

The aesthetic follows a **Modern/Minimalist** approach with a focus on editorial clarity. By utilizing a "content-first" hierarchy, the UI recedes to let the prose shine, using heavy whitespace and purposeful hits of color to guide user interaction and signify community energy. The goal is to evoke a sense of belonging and creative inspiration.

## Colors

The palette is anchored by a vibrant **Deep Coral** primary color, chosen to stimulate creativity and signify "active" community nodes. This is balanced by a **Deep Navy** secondary color that provides the necessary professional weight for news-oriented content.

- **Primary (#FF5A36):** Used for primary actions, progress indicators, and highlight states.
- **Secondary (#1A202C):** Reserved for high-level navigation and primary headers to ensure authority.
- **Backgrounds:** Utilize a "Soft White" (#FFFFFF) for the main reading canvas and "Ice Gray" (#F7FAFC) for container backgrounds and sidebars to reduce eye strain during long-form reading sessions.
- **Success/Warning/Error:** Standard functional signaling should be used sparingly, maintaining the Coral primary as the hero of the interface.

## Typography

This design system employs a sophisticated pairing of **Newsreader** for editorial content and **Inter** for functional UI elements. 

- **The Reading Experience:** Long-form story content and news articles must use `body-reading`. The serif typeface is optimized for legibility at larger sizes (20px+) with a generous line height (1.6) to ensure a comfortable rhythm.
- **The Interface:** Inter provides a neutral, highly legible framework for navigation, buttons, and metadata. 
- **Hierarchy:** Use `display-lg` for story titles and `headline-md` for forum section headers. Captions and metadata (like "5 min read" or "Author Name") should use `label-sm`.

## Layout & Spacing

The layout utilizes a **12-column fluid grid** for discovery pages and a **centered, narrow column** for reading experiences. 

- **Rhythm:** All spacing is derived from a base **8px unit**. Padding and margins should scale in increments of 8 (e.g., 16, 24, 32, 48, 64).
- **Reading Focus:** For stories and articles, the text container is limited to a `reading-width` of 680px to maintain optimal line lengths for comprehension.
- **Breakpoints:**
  - **Mobile (<768px):** 1-column layout, 16px side margins.
  - **Tablet (768px - 1024px):** 2-column discovery (Sidebar + Main), 24px margins.
  - **Desktop (>1024px):** Full 12-column capability with a 1200px max-width container.

## Elevation & Depth

Visual hierarchy is established through a combination of **tonal layering** and **ambient shadows**. 

- **Surface Levels:** The primary background is the lowest level. Card elements and navigation bars sit one level above, distinguished by a subtle white background and a soft shadow.
- **Shadow Character:** Shadows should be extremely diffused and low-opacity. Use a slight warm tint (`rgba(255, 90, 54, 0.04)`) for shadows on primary-related elements to maintain the "vibrant" brand feel.
- **Interactive Depth:** On hover, cards should slightly lift (increase shadow spread) rather than change color, reinforcing the "tactile paper" metaphor.

## Shapes

The shape language is **friendly and approachable**, moving away from harsh edges to foster a sense of community safety.

- **Base Radius:** Standard UI components like input fields and buttons use a **0.5rem (8px)** radius.
- **Large Radius:** Story cards and featured containers use a **1rem (16px)** radius to create a distinct "soft" look that differentiates them from the more utilitarian UI.
- **Interactive Elements:** Checkboxes and small tags use a **4px** radius to maintain crispness at smaller scales.

## Components

### Buttons
- **Primary:** Solid Coral (#FF5A36) with white text. High emphasis.
- **Secondary:** Deep Navy (#1A202C) outline with matching text. For secondary actions like "Save to Library."
- **Ghost:** No border or background. Used for navigation and low-priority actions like "Cancel."

### Story Cards
Cards are the primary unit of discovery. They feature a 2:3 aspect ratio cover image on the left or top, a `headline-sm` title, and a `label-sm` metadata row. Use `rounded-lg` (16px) for the card container.

### Input Fields
Inputs use a light gray stroke (#E2E8F0) and an 8px radius. Upon focus, the border transitions to Primary Coral with a 2px outer glow (soft shadow).

### Community Chips
Used for genre tags and forum categories. These should be pill-shaped with a subtle background tint of the primary color at 10% opacity and `label-bold` text.

### Feed Items
Forum threads and news updates should use a horizontal layout with a clear distinction between the "User Avatar" (circular) and the "Thread Title" (`headline-sm`).