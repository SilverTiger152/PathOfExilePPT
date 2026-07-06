---
name: Atlas Archive
colors:
  surface: '#111417'
  surface-dim: '#111417'
  surface-bright: '#37393d'
  surface-container-lowest: '#0b0e11'
  surface-container-low: '#191c1f'
  surface-container: '#1d2023'
  surface-container-high: '#272a2e'
  surface-container-highest: '#323538'
  on-surface: '#e1e2e7'
  on-surface-variant: '#e3beb8'
  inverse-surface: '#e1e2e7'
  inverse-on-surface: '#2e3134'
  outline: '#aa8984'
  outline-variant: '#5a403c'
  surface-tint: '#ffb4a8'
  primary: '#ffb4a8'
  on-primary: '#690000'
  primary-container: '#8b0000'
  on-primary-container: '#ff907f'
  inverse-primary: '#b52619'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#b6c4ff'
  on-tertiary: '#05297a'
  tertiary-container: '#203c8c'
  on-tertiary-container: '#94abff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#920703'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#dce1ff'
  tertiary-fixed-dim: '#b6c4ff'
  on-tertiary-fixed: '#00164e'
  on-tertiary-fixed-variant: '#264191'
  background: '#111417'
  on-background: '#e1e2e7'
  surface-variant: '#323538'
  deep-obsidian: '#0B0E11'
  void-black: '#050607'
  blood-crimson: '#8B0000'
  golden-currency: '#D4AF37'
  ethereal-blue: '#1E3A8A'
  stone-gray: '#333333'
  parchment-white: '#E0D7C6'
typography:
  headline-xl:
    fontFamily: Source Serif 4
    fontSize: 48px
    fontWeight: '900'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '800'
    lineHeight: 32px
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '700'
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 14px
spacing:
  unit: 4px
  gutter: 24px
  margin-edge: 32px
  container-max: 1280px
---

## Brand & Style

The design system is engineered to evoke the "Gritty Dark Fantasy" of the Wraeclast universe. It targets a professional player base that demands both deep immersion and extreme information density. The aesthetic is a hybrid of **High-Contrast Dark Mode** and **Tactile Skeuomorphism**, drawing inspiration from the Atlas of Worlds and in-game inventory management.

The UI should feel "heavy"—composed of stone, iron, and ancient parchment. It prioritizes a sense of danger and reward through the use of blood-red accents and metallic gold highlights. While the environment is dark and atmospheric, the utility remains sharp and professional, ensuring that complex item stats and passive tree guides are instantly legible.

## Colors

The palette is anchored in **Deep Obsidian**, providing a near-black canvas that allows vibrant game-related colors to pop. 

- **Primary (Blood Crimson):** Reserved for critical actions, health-related data, and destructive interactions.
- **Secondary (Golden Currency):** Used for highlighting rare items, headers, and rewarding UI elements.
- **Tertiary (Ethereal Blue):** Dedicated to mana, energy shield, or magical property descriptors.
- **Neutrals:** Utilize varying shades of "Stone Gray" for borders and "Parchment White" for body text to reduce eye strain against the dark background while maintaining high contrast.

## Typography

This design system uses a deliberate contrast between ancient and modern fonts.

- **Headlines:** Use **Source Serif 4** (a stand-in for the heavy gothic Exocet style) at high weights. These should be treated as "etched" into the UI, often appearing in Golden Currency or Blood Crimson.
- **Body Text:** Use **Inter** for all guide content and descriptions. The clean, neutral sans-serif ensures that long-form build guides are readable even during intense gameplay sessions.
- **Technical Labels:** Use **JetBrains Mono** for item stats, damage numbers, and code-like data. The monospaced nature reflects the mechanical complexity of game systems.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to mimic the structured feel of an RPG inventory or a master's chronicle. 

- **Desktop (12-column):** Elements align to a rigid 12-column grid with generous 24px gutters. 
- **Tablet (8-column):** Margins shrink to 24px, and card grids reflow to two columns.
- **Mobile (4-column):** Margins shrink to 16px. All grids collapse to a single column vertical stack.

Use a 4px base spacing unit. Card groups (like item sets) should use tight 8px gaps, while major sections (like "Gems" vs "Equipment") should be separated by at least 48px to create a clear hierarchy.

## Elevation & Depth

Depth is conveyed through **Tonal Layering** and **Metallic Outlines** rather than soft shadows.

1.  **Background:** Deep Obsidian with a subtle "Noise" or "Stone Texture" overlay at 5% opacity.
2.  **Surface:** Mid-tone gray (#1A1D21) with a 1px solid border.
3.  **Raised:** Use "Iron" borders—a 2px gradient border transitioning from Dark Gray to Light Metallic Gray.
4.  **Interactive:** Hover states trigger an "Ethereal Glow"—a localized outer glow using Ethereal Blue or Golden Currency with a 15px blur radius, simulating a magical aura.

Avoid soft ambient shadows; use crisp, high-contrast borders to define element boundaries.

## Shapes

The shape language is strictly **Sharp (0px)**. Rounded corners conflict with the gritty, stone-carved aesthetic. All cards, buttons, and input fields must have hard 90-degree angles. To prevent the UI from looking dated, use thin (1px) inner-bevel borders to simulate the "chiseled" edges of stone or the forged edges of metal plates.

## Components

- **Cards:** Use a "Stone Slab" style. Background is #1A1D21. Border is 1px solid #333. Header area of the card should have a 1px Golden Currency bottom border.
- **Buttons (Primary):** Solid Blood Crimson background with white text. On hover, add a 2px Golden Currency inner border.
- **Buttons (Secondary):** Transparent background with a 1px Iron-gray border. Text is Parchment White.
- **Input Fields:** Darker than the surface (#050607), sharp corners, with a subtle inner shadow to look "recessed" into the UI.
- **Chips/Badges:** Use JetBrains Mono. Magical items get Ethereal Blue text/border; Rare items get Golden Currency; Unique items get a specific Burnt Orange (#AF641D) accent.
- **Mod Lists:** For item descriptions, use a bulleted list where the bullet is a small, glowing diamond icon. Alternate row colors slightly to help with tracking complex stat blocks.
- **Progress Bars (Life/Mana):** Use thick, non-rounded bars. Life is Blood Crimson; Mana is Ethereal Blue. Use a subtle glass-like highlight on the top 50% of the bar.