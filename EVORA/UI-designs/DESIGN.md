---
name: Evora Design System
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#414943'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#717972'
  outline-variant: '#c1c9c1'
  surface-tint: '#3a674f'
  primary: '#14422c'
  on-primary: '#ffffff'
  primary-container: '#2d5a42'
  on-primary-container: '#9fcfb1'
  inverse-primary: '#a1d2b3'
  secondary: '#855300'
  on-secondary: '#ffffff'
  secondary-container: '#fea619'
  on-secondary-container: '#684000'
  tertiary: '#313b4b'
  on-tertiary: '#ffffff'
  tertiary-container: '#485263'
  on-tertiary-container: '#bbc5d9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bceece'
  primary-fixed-dim: '#a1d2b3'
  on-primary-fixed: '#002112'
  on-primary-fixed-variant: '#224f38'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#d9e3f7'
  tertiary-fixed-dim: '#bdc7db'
  on-tertiary-fixed: '#121c2a'
  on-tertiary-fixed-variant: '#3d4757'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
  sidebar-width: 280px
---

## Brand & Style

The design system is engineered for high-stakes enterprise fleet management, balancing operational efficiency with a sophisticated, trustworthy aesthetic. The personality is **Intelligent, Operational, and Modern**, utilizing a "Clean Corporate" style that avoids the sterility of typical SaaS platforms by incorporating warm, organic tones inspired by infrastructure and the natural environments fleet assets inhabit.

The visual narrative is built on precision and reliability. It employs a refined mix of **Modern Corporate** layouts with **Minimalist** clarity, ensuring that data-heavy dashboards remain legible and actionable. High-quality whitespace is used to reduce cognitive load for dispatchers and fleet managers.

## Colors

The palette is grounded in a deep **Forest Green (#2D5A42)**, representing stability and infrastructure. This primary color is used for navigation, key action buttons, and successful status indicators.

**Amber (#F59E0B)** serves as the secondary color, specifically reserved for fleet assets, alerts, and high-priority data points that require immediate attention. 

The background utilizes an **Off-white/Cream (#FDFBF7)** to provide a warmer, more premium feel than standard digital grays, reducing eye strain for long-term operational use. Typography is set in **Deep Charcoal (#374151)** to ensure optimal contrast and readability without the harshness of pure black.

## Typography

The design system exclusively uses **Inter** to maintain a clean, modern, and highly legible appearance across all asset management interfaces. 

- **Headlines:** Use tighter letter spacing and semi-bold weights to establish a strong hierarchy.
- **Body Text:** Standard weight with generous line heights for maximum readability in data-dense tables.
- **Labels:** Small caps or all-caps are used for metadata, table headers, and category tags to differentiate them from actionable content.
- **Numerical Data:** For fleet metrics, ensure tabular lining is enabled to keep numbers aligned in columns.

## Layout & Spacing

The design system follows a **12-column fluid grid** for desktop, optimized for wide-screen dashboard monitoring. 

- **Layout Model:** A fixed left-hand navigation sidebar (280px) provides consistent access to infrastructure tools. The main content area uses a fluid container with 32px margins.
- **Spacing Rhythm:** Based on an 8px baseline. Use 24px gutters between dashboard cards and 16px internal padding within cards to maintain a clean, airy feel.
- **Responsive Behavior:** 
  - **Desktop (1440px+):** Full 12-column layout.
  - **Tablet (768px - 1439px):** Content reflows to 8 columns; sidebar may collapse to an icon-only rail.
  - **Mobile (<767px):** Single-column layout with 16px margins; complex tables transform into card-based list views.

## Elevation & Depth

This design system uses a **Tonal Layering** approach combined with **Subtle Ambient Shadows** to create a sophisticated sense of hierarchy.

- **Level 0 (Background):** The Off-white surface (#FDFBF7) serves as the foundation.
- **Level 1 (Cards/Containers):** White (#FFFFFF) surfaces with a 1px border (#E5E7EB) and a very soft, diffused shadow (0px 4px 20px rgba(0, 0, 0, 0.03)).
- **Level 2 (Modals/Popovers):** Higher elevation with a more pronounced shadow (0px 10px 30px rgba(0, 0, 0, 0.08)) to pull the element forward.
- **Interaction:** On hover, cards should lift slightly (y-offset increases) and the border color should shift to the Primary Forest Green at low opacity.

## Shapes

The shape language is **Rounded**, reflecting a modern and approachable enterprise tool. 

- **Standard Elements:** Buttons, input fields, and small UI components use a 0.5rem (8px) radius.
- **Large Containers:** Dashboard cards and modals use a 1rem (16px) radius for a softer, more premium aesthetic.
- **Icons:** Should follow the same corner logic—refined, slightly rounded terminals rather than sharp geometric points.

## Components

### Buttons
- **Primary:** Solid Forest Green with White text. 8px corner radius.
- **Secondary:** Transparent with 1px Forest Green border.
- **Tertiary/Ghost:** No border, Charcoal text, reveals a light green background on hover.

### Cards
- White background, 16px corner radius, subtle 1px border.
- Header section of the card should use the Label-md typography for titles.

### Input Fields
- Background color should be a very light tint of the neutral cream.
- Active state uses a 2px Forest Green border glow.
- Labels are positioned above the field in Body-sm (Bold).

### Chips & Status Indicators
- Use the Secondary Amber for "In Transit" or "Alert" statuses.
- Use Primary Green for "Available" or "Maintenance Complete".
- Backgrounds should be high-transparency versions of the status color with high-contrast text.

### Refined Iconography
- Use 24px stroke-based icons.
- Stroke weight should be "Regular" (1.5px - 2px) to match the Inter typeface weight.
- Avoid filled icons unless used as active state markers in the sidebar.