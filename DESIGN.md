---
name: Analytical Clarity
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
  on-surface-variant: '#43474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eef1f3'
  outline: '#74777f'
  outline-variant: '#c4c6cf'
  surface-tint: '#476083'
  primary: '#000613'
  on-primary: '#ffffff'
  primary-container: '#001f3f'
  on-primary-container: '#6f88ad'
  inverse-primary: '#afc8f0'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#110200'
  on-tertiary: '#ffffff'
  tertiary-container: '#391303'
  on-tertiary-container: '#b5785f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d4e3ff'
  primary-fixed-dim: '#afc8f0'
  on-primary-fixed: '#001c3a'
  on-primary-fixed-variant: '#2f486a'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#fdb69a'
  on-tertiary-fixed: '#351002'
  on-tertiary-fixed-variant: '#6b3a25'
  background: '#f7fafc'
  on-background: '#181c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
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
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  button-text:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  section-padding-desktop: 80px
  section-padding-mobile: 40px
---

## Brand & Style
This design system is built for a professional Data Analyst portfolio, emphasizing precision, objectivity, and narrative clarity. The aesthetic follows a **Minimalist** approach with **Corporate/Modern** influences, ensuring that complex data visualizations and project case studies remain the focal point. 

The UI should evoke a sense of trust and technical proficiency. By utilizing generous white space and a structured grid, the design allows the "data to speak," avoiding unnecessary ornamentation. Interaction patterns are subtle but intentional, reflecting the meticulous nature of data science.

## Colors
The palette is rooted in **Navy Blue**, symbolizing institutional stability and intelligence. **White** serves as the primary canvas to maintain a high-signal-to-noise ratio. 

- **Primary (Navy):** Used for headings, navigation backgrounds, and primary text to establish authority.
- **Secondary (White):** The core background color to ensure maximum readability and "breathability."
- **Accent (Warm Orange):** Reserved strictly for high-priority actions (CTAs), key data highlights, and active states.
- **Neutral (Soft Gray):** Used for subtle section dividers and card backgrounds to provide gentle depth without clutter.

## Typography
The typographic scale prioritizes hierarchy and legibility. **Montserrat** provides a geometric, modern structure for headings, while **Inter** ensures that long-form project descriptions and data labels remain highly readable.

Large headlines should use tight letter spacing to appear more "designed" and impactful. For data-heavy labels, use the uppercase `label-caps` style to differentiate metadata from body prose.

## Layout & Spacing
The design utilizes a **Fixed Grid** model for desktop (centered 12-column) and a fluid 4-column model for mobile.

- **Vertical Rhythm:** Sections are separated by significant vertical padding (`80px`) to enforce the minimalist aesthetic.
- **Project Grids:** Use a 2 or 3-column layout for project cards on desktop, collapsing to a single column on mobile.
- **Alignment:** Content is generally left-aligned to mirror the logical flow of data reports, with the exception of hero section text which may be centered for impact.

## Elevation & Depth
Depth is communicated through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Level 0 (Surface):** The primary background (#FFFFFF).
- **Level 1 (Cards):** Use a very subtle light gray background (#F4F7F9) or a 1px border (#E1E8ED). 
- **Interactive State:** On hover, cards should lift slightly using a soft, ambient shadow (0px 10px 20px rgba(0, 31, 63, 0.05)) to signal interactivity without breaking the flat, professional aesthetic.

## Shapes
A **Soft** shape language is used to balance the "hard" nature of data. Rectilinear elements are given a slight 4px (`0.25rem`) corner radius. This prevents the UI from feeling too aggressive while maintaining a professional, structured appearance. Buttons and input fields follow this consistent radius.

## Components

### Buttons
- **Primary:** Navy background with white text. High-contrast and authoritative.
- **CTA:** Warm Orange background with white text. Used only for "Hire Me" or "View Live Project."
- **Ghost:** Navy 1px outline with Navy text for secondary actions like "Download CSV" or "View Code."

### Project Cards
Cards feature a header image or data visualization thumbnail, followed by a `label-caps` category, a `headline-md` title, and a short `body-md` summary. On hover, the card background shifts slightly or the accent color appears as a thin bottom border.

### Chips / Tags
Used for technical skills (e.g., Python, SQL, Tableau). Small, rounded-sm containers with a light gray background and dark navy text. This keeps skills visible but secondary to project titles.

### Form Inputs
Clean, minimal borders (1px Gray). On focus, the border transitions to Navy. Labels are always positioned above the input in `label-caps` for clarity.

### Navigation
A sticky top bar with a transparent background that transitions to a solid White background with a subtle bottom border upon scrolling. Links use `button-text` style with an orange underline on hover.