---
name: Modern High-Contrast Delivery
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#584237'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#8c7164'
  outline-variant: '#e0c0b1'
  surface-tint: '#9d4300'
  primary: '#9d4300'
  on-primary: '#ffffff'
  primary-container: '#f97316'
  on-primary-container: '#582200'
  inverse-primary: '#ffb690'
  secondary: '#565d79'
  on-secondary: '#ffffff'
  secondary-container: '#d8deff'
  on-secondary-container: '#5a627e'
  tertiary: '#515f74'
  on-tertiary: '#ffffff'
  tertiary-container: '#8d9bb2'
  on-tertiary-container: '#253346'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb690'
  on-primary-fixed: '#341100'
  on-primary-fixed-variant: '#783200'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#bec5e5'
  on-secondary-fixed: '#131a33'
  on-secondary-fixed-variant: '#3e4660'
  tertiary-fixed: '#d5e3fd'
  tertiary-fixed-dim: '#b9c7e0'
  on-tertiary-fixed: '#0d1c2f'
  on-tertiary-fixed-variant: '#3a485c'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
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
  container-padding: 24px
  stack-gap: 16px
  section-margin: 32px
  max-width: 480px
---

## Brand & Style

The design system for UniEats focuses on a **Modern High-Contrast** aesthetic. It targets a young, energetic demographic—specifically university students and faculty—who prioritize speed and clarity. The brand evokes a sense of reliability through its deep navy foundation, while the vibrant orange accents inject energy and appetite appeal. 

The style is characterized by "floating" container architecture, where large-radius surfaces overlap high-saturation headers. This creates a distinct vertical hierarchy that guides the user from global brand elements down into task-specific interactions.

## Colors

This design system utilizes a high-contrast light mode palette. 

- **Primary (Vibrant Orange):** Reserved for call-to-action buttons, active states, and critical brand highlights.
- **Secondary (Dark Navy):** Used exclusively for headers, status bars, and primary brand backgrounds to create a grounded, premium feel.
- **Primary Text (Dark Slate):** Provides high legibility against white surfaces without the harshness of pure black.
- **Surface & Background:** A clear distinction is made between the "Body Background" (Off-white) and "Card Surfaces" (Pure White) to provide subtle depth through color alone.

## Typography

The typography system relies entirely on **Inter**, a clean sans-serif designed for screen readability. 

- **Headers:** Titles within the Navy header use white text with bold weights and tight letter spacing for a punchy, impactful look.
- **Primary Text:** Dark Slate (#334155) is used for all body copy to ensure soft but clear contrast.
- **Labels:** Small uppercase labels are used above input fields to create a structured, "form-first" hierarchy.
- **Accessibility:** Line heights are generous (1.5x for body) to ensure ease of reading during quick navigation.

## Layout & Spacing

The design system follows a **Mobile-First Fixed Grid** model, constrained to a maximum width of 480px for desktop viewing to maintain the intimate mobile feel. 

- **The Header Offset:** The secondary color background extends behind the top 25% of the screen. Cards are positioned to overlap this background slightly, creating a layered effect.
- **Margins:** A standard 24px horizontal margin is applied to all main content containers.
- **Gaps:** A consistent 16px vertical gap is used between input elements, while 32px is used to separate distinct functional sections (e.g., login form vs. social login).

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and color layering rather than harsh borders.

- **Surface Depth:** White cards use a "Soft-Deep" shadow—low opacity (8-10%) with a large blur radius (20px-30px) and a slight Y-axis offset. This makes the cards appear to float gently above the off-white background.
- **Header Layering:** The Dark Navy header sits at the lowest Z-index, acting as a backdrop.
- **Interactive Elements:** Buttons and inputs remain flat. Depth is reserved for major containers (Cards) to keep the UI clean and avoid visual clutter.

## Shapes

The shape language is "Hyper-Rounded," emphasizing a friendly and modern consumer experience.

- **Main Containers:** Use `rounded-3xl` (32px) for large content cards that house forms and lists.
- **Inputs & Secondary Buttons:** Use `rounded-xl` (12px) to provide a distinct look from the main containers while maintaining the soft aesthetic.
- **Primary Buttons:** May use either `rounded-xl` or `rounded-full` (pill) depending on the desired emphasis, but 12px is the default for consistency with inputs.

## Components

### Buttons
- **Primary:** Vibrant Orange background, White text, Bold weight. No border.
- **Secondary/Social:** Pure White background, subtle 1px gray border or soft shadow, containing brand-colored icons (FB, Google, Apple).

### Input Fields
- **Default State:** Light gray (#F3F4F6) background, 12px corner radius. No borders.
- **Text:** Dark Slate primary text; placeholder text in a lighter slate shade.
- **Labels:** Placed externally above the field in bold, uppercase 12px type.

### Cards
- **Container:** Pure White, 32px corner radius, soft ambient shadow.
- **Padding:** 24px internal padding on all sides to prevent content from feeling cramped against the large corners.

### Segmented Control (Tabs)
- Used for switching roles (e.g., Student vs. Owner).
- Uses a "pill-in-container" approach where a white active pill slides over a light gray background track.

### Selection Controls
- **Checkboxes:** Square with slightly rounded corners (4px), using the primary orange for the checked state.