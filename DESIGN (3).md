---
name: UpCrew Design System
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daef'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2b'
  on-surface-variant: '#434655'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#9d4300'
  on-secondary: '#ffffff'
  secondary-container: '#fd761a'
  on-secondary-container: '#5c2400'
  tertiary: '#006229'
  on-tertiary: '#ffffff'
  tertiary-container: '#007e37'
  on-tertiary-container: '#c1ffc5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#ffdbca'
  secondary-fixed-dim: '#ffb690'
  on-secondary-fixed: '#341100'
  on-secondary-fixed-variant: '#783200'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#f9f9ff'
  on-background: '#141b2b'
  surface-variant: '#dce2f7'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The brand personality is energetic, collaborative, and professional. It targets modern teams and workforce management sectors, evoking a sense of upward momentum and reliable partnership. 

The design style follows a **Corporate / Modern** aesthetic with subtle **Minimalist** influences. It prioritizes clarity and functional efficiency while using vibrant accent colors to highlight human interaction and progress. The visual mood is clean and structured, utilizing the brand logo—a stylized 'U' resembling a crew—either as a standalone symbol for compact spaces (like avatars or favicons) or paired with its bold, geometric typography for full branding.

## Colors
The palette is rooted in a high-contrast foundation to ensure accessibility and professional appeal.

- **Primary (Blue - #2563EB):** Used for primary actions, active states, and brand-heavy components.
- **Secondary (Orange - #F97316):** Reserved for highlights, notifications, and secondary brand elements that signify "people" or "activity" based on the logo's central figure.
- **Tertiary (Green - #22C55E):** Utilized for success states, growth indicators, and positive completion metrics.
- **Neutral (Dark Navy - #111827):** Applied to primary text, headers, and heavy structural elements to provide a grounded, high-contrast feel.
- **Surface (White - #FFFAFA):** A warm off-white background to reduce eye strain compared to pure hex white while maintaining a clean, professional look.

## Typography
The system uses a tiered font strategy to balance personality with utility. 

**Plus Jakarta Sans** is the headline face, chosen for its approachable yet modern geometric forms that mirror the logo's curves. **Inter** serves as the workhorse for body copy, ensuring maximum readability across data-dense screens. **Geist** is introduced for labels and technical data, providing a precise, developer-friendly clarity for UI metadata and small status indicators.

## Layout & Spacing
The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

A consistent 8px-based spatial system governs all internal padding and margins. Layouts should prioritize "Safe Zones"—generous outer margins—to maintain the minimalist feel. On desktop, the content container has a maximum width of 1280px. For data-heavy dashboard views, the gutter scales down to 16px to maximize information density while maintaining vertical rhythm.

## Elevation & Depth
Depth is conveyed through **Tonal Layers** and **Ambient Shadows**. 

Surfaces are categorized by their "z-index" relative to the background:
- **Level 0 (Background):** #FFFAFA.
- **Level 1 (Cards/Sections):** White with a subtle 1px border (#E2E8F0).
- **Level 2 (Interactive/Floating):** Soft, diffused shadows with a slight blue tint (rgba(37, 99, 235, 0.05)) to tie the elevation back to the primary brand color.
- **Level 3 (Modals/Overlays):** High-diffusion shadows with a 16px blur, creating a clear separation from the workspace.

## Shapes
The shape language is defined as **Rounded**, mimicking the circular terminals and friendly curves of the brand logo. Standard UI components (Inputs, Buttons, Cards) use a 0.5rem base radius. Larger containers or feature sections scale up to 1.5rem to create a softer, more inviting interface.

## Components
- **Buttons:** Primary buttons use the Blue (#2563EB) background with White text. Secondary buttons use a transparent background with a Blue border. Action-oriented icons should use the Secondary Orange to draw attention to "human" actions (e.g., adding a crew member).
- **Chips:** Used for status tags. "In Progress" uses Blue, "Complete" uses Green, and "Warning" uses Orange. Backgrounds for chips should be 10% opacity of the color with 100% opacity text for high legibility.
- **Input Fields:** Use a 1px border (#D1D5DB) that shifts to 2px Blue (#2563EB) on focus. Labels use the Geist font in Neutral navy.
- **Cards:** Cards are pure white with a 0.5rem corner radius and a very subtle Level 1 shadow.
- **Lists:** Use Neutral navy for primary text and Inter body-md for secondary metadata. Dividers are light grey (#F1F5F9).
- **Navigation:** Top navigation features the full logo (Symbol + Text), while collapsed sidebars use only the Symbol. Active states are indicated by a 4px Blue vertical bar on the left.