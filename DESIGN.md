---
name: Modern Community
colors:
  surface: '#fcf8f9'
  surface-dim: '#dcd9da'
  surface-bright: '#fcf8f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f4'
  surface-container: '#f0edee'
  surface-container-high: '#eae7e8'
  surface-container-highest: '#e5e2e3'
  on-surface: '#1b1b1c'
  on-surface-variant: '#5d4038'
  inverse-surface: '#303031'
  inverse-on-surface: '#f3f0f1'
  outline: '#926f66'
  outline-variant: '#e7bdb2'
  surface-tint: '#b12d00'
  primary: '#ad2c00'
  on-primary: '#ffffff'
  primary-container: '#d83900'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb5a0'
  secondary: '#0060a9'
  on-secondary: '#ffffff'
  secondary-container: '#4ba1fd'
  on-secondary-container: '#003663'
  tertiary: '#006954'
  on-tertiary: '#ffffff'
  tertiary-container: '#00846b'
  on-tertiary-container: '#f5fff9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbd1'
  primary-fixed-dim: '#ffb5a0'
  on-primary-fixed: '#3b0900'
  on-primary-fixed-variant: '#872000'
  secondary-fixed: '#d3e4ff'
  secondary-fixed-dim: '#a2c9ff'
  on-secondary-fixed: '#001c38'
  on-secondary-fixed-variant: '#004881'
  tertiary-fixed: '#73f9d4'
  tertiary-fixed-dim: '#53dcb9'
  on-tertiary-fixed: '#002018'
  on-tertiary-fixed-variant: '#005140'
  background: '#fcf8f9'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e3'
typography:
  display-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Be Vietnam Pro
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: '1'
  headline-lg-mobile:
    fontFamily: Be Vietnam Pro
    fontSize: 22px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 48px
  container-max: 1200px
  gutter: 16px
---

## Brand & Style
The design system is engineered for high-density information environments where content hierarchy and legibility are paramount. It adopts a **Modern / Corporate** aesthetic with a heavy lean toward **Minimalism**, ensuring that the user interface recedes to highlight community discussions. 

The target audience consists of digital-native users who value efficiency and clarity. The emotional response is one of organized familiarity—users should feel they are in a structured, reliable space that facilitates deep dives into specific topics without cognitive overload. The style utilizes ample whitespace and a rigorous grid to prevent the "clutter" typically associated with message boards, creating a premium, editorial feel for user-generated content.

## Colors
The palette is anchored by a high-energy **International Orange** (#FF4500) used strictly for primary actions, notifications, and brand-critical touchpoints. This is balanced by a **Deep Blue** (#0079D3) for secondary interactive elements like links and tags, providing a familiar mental model for navigation.

The neutral scale is critical for structure. Surface colors utilize off-whites and very light grays to differentiate between the background and content cards, while the primary text color is a soft charcoal (#1A1A1B) to reduce eye strain during long-form reading compared to pure black. Success states use a vibrant teal to remain distinct from the primary orange.

## Typography
The typographic strategy employs a dual-font system to balance personality with utility. **Be Vietnam Pro** is used for headlines and titles; its slightly geometric and warm character makes community names and post titles feel approachable and modern. 

**Inter** is utilized for all body copy, comments, and interface labels. Chosen for its exceptional legibility at small sizes and its neutral, systematic tone, it ensures that long comment threads remain readable. A generous 1.6 line-height is applied to body text to facilitate scanning. Metadata (timestamps, usernames, breadcrumbs) uses the `label-sm` tier with increased letter spacing to distinguish it from the main content.

## Layout & Spacing
This design system follows a **Mobile-First, Fluid Grid** philosophy. On mobile devices, the layout uses a single-column view with 16px side margins. As the screen scales to desktop, the content adopts a 12-column grid within a 1200px max-width container, typically utilizing an 8-column main content area and a 4-column sidebar for community information and widgets.

Spacing is strictly derived from a 4px baseline grid. Significant vertical rhythm is maintained by using 24px (lg) spacing between post cards and 16px (md) padding within cards. Comment nesting is visualized through 16px left-indents, creating a clear vertical "thread" line to help users track discussions.

## Elevation & Depth
Depth is communicated through **Tonal Layering** supplemented by **Ambient Shadows**. The global background uses a subtle light-gray tint, while primary content cards are pure white, creating a natural lift.

Shadows are used sparingly to indicate interactivity and hierarchy. A "Level 1" shadow (low blur, 5% opacity) is applied to post cards to distinguish them from the background. "Level 2" shadows (larger blur, 8% opacity) are reserved for floating elements like dropdown menus, modals, and hover states on interactive cards. This approach ensures the UI feels tactile without the visual "weight" of traditional skeuomorphism.

## Shapes
The shape language is defined as **Rounded**, utilizing a base 8px (0.5rem) corner radius for main components like cards, input fields, and buttons. This radius is large enough to feel friendly and modern but small enough to maintain a professional, structured appearance.

For specific decorative or high-action elements like "Join" buttons or category chips, a `rounded-xl` (24px) or pill-shape is used to draw the eye. Conversely, nested elements like media within a post card use a slightly smaller radius (4px) to maintain visual nesting harmony.

## Components
### Buttons
Buttons feature center-aligned text in `label-md`. The Primary button is solid Orange (#FF4500) with white text. Secondary buttons use a subtle gray background with charcoal text to recede in the hierarchy.

### Cards
Post cards are the central component. They feature a white background, Level 1 shadow, and 16px internal padding. Titles use `headline-sm`. The bottom of the card houses a persistent action bar for voting, comments, and sharing.

### Chips & Tags
Used for community labels or post flairs. These utilize a `rounded-xl` shape with a light-gray background and `label-sm` typography to ensure they don't compete with primary actions.

### Discussion Threads
Comments are visually grouped by a 2px wide vertical "indent line" colored in a very light gray. This provides a clear path for the eye to follow during deep nesting.

### Input Fields
Search bars and comment inputs use an 8px radius, a 1px light-gray border, and a focus state that highlights the border in Primary Blue (#0079D3).