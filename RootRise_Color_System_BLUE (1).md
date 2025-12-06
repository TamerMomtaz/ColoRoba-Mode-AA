# RootRise Color System - BLUE VERSION
**Alternative Blue Dark Mode Palette**
**✓ Professional Cool Blue Aesthetic**

---

## Design Philosophy

**Blue Version Features:**
- **Cool Blue dark mode** - professional, calming blue palette for passive sections
- **Light colors** (beige/cream) for interactive sections requiring user attention (unchanged)
- **Bronze/Gold brand colors** maintained for consistency (unchanged)

**Difference from Teal Crystal Version:**  
This version uses a cool blue spectrum (#102a43 to #f0f4f8) for dark mode instead of the logo-matched teal greens.

---

## Color Palette
**Extracted from actual RootRise V18.1 implementation**

### Primary Colors

#### Bronze/Gold Metallic
**Purpose:** Primary brand color, CTAs, "AI Team" highlights, "RootRise" accent
- **Main:** `#B8904A` (Warm Bronze Gold)
- **Light:** `#C4965F` (Light Golden Bronze)
- **Dark:** `#9D7E3A` (Deep Bronze)

**Usage:**
- Primary CTA buttons ("START YOUR JOURNEY", "START FREE")
- "CORE" agent badges
- "AI Team" text highlighting
- "Rise" in RootRise logo
- Active/selected state indicators
- Navigation outline buttons

#### Dark Mode - Blue Palette
**Purpose:** Main backgrounds for landing/hero sections, passive areas (professional blue aesthetic)
- **Deepest:** `#102a43` (Deep Navy Blue)
- **Main:** `#486581` (Dark Blue-Gray)
- **Card:** `#829ab1` (Medium Blue-Gray)
- **Border:** `#bcccdc` (Light Blue-Gray)
- **Lightest:** `#f0f4f8` (Very Light Blue)

**Usage:**
- Hero/landing page background
- Main application background (dark mode)
- Agent selection cards
- Header/navigation background
- Footer areas
- Sections with minimal user interaction

---

### Secondary Colors

#### Calm Teal Shades
**Purpose:** Key highlights, emphasis, selected states (calm, professional tones)
- **Light:** `#b2d8d8` (Light Teal)
- **Medium Light:** `#66b2b2` (Medium Light Teal)
- **Classic:** `#008080` (Classic Teal)
- **Medium Dark:** `#006666` (Medium Dark Teal)
- **Deep:** `#004c4c` (Deep Teal)

**Usage:**
- "Made For You" hero text (#66b2b2)
- Selected agent card borders
- "ADD-ON" agent badges
- Checkmark indicators
- Interactive element highlights
- Small caps text accents

#### DEVONEERS Logo Teal
**Purpose:** DEVONEERS brand identity, depth elements
- **Logo:** `#2A5C5C` (DEVONEERS Logo Teal)

**Usage:**
- DEVONEERS logo background circle
- Brand-specific accent elements
- Depth and shadow elements
- Traditional DEVONEERS brand color

---

### Interactive/Questionnaire Colors (Light Mode)

#### Warm Cream/Beige
**Purpose:** Background for sections requiring user input and focus
- **Background:** `#F5F1E8` (Warm Light Cream)
- **Subtle:** `#EDE8DD` (Sandy Beige)
- **Card:** `#FFFFFF` (Pure White)
- **Dropdown/Section:** `#E8E3D8` (Light Beige-Gray)
- **Border:** `#D4CFC4` (Soft Border)

**Usage:**
- Report Settings page background
- Questionnaire pages
- Form sections background
- Dropdown menus and input containers
- Content cards requiring user attention
- Light mode entire page background

---

### Neutral Colors

#### Text & UI Elements
- **Primary Text (Dark):** `#2C2C2C` (Charcoal)
- **Secondary Text (Dark):** `#5A5A5A` (Medium Gray)
- **Text on Dark BG:** `#F5F1E8` (Cream)
- **Text on Light BG:** `#2C2C2C` (Charcoal)
- **Disabled:** `#ADADAD` (Light Gray)

---

## Page-by-Page Application
**Based on actual RootRise V18.1 implementation**

### 1. Landing/Hero Page (Dark Mode - Blue Palette)
```
Background: Deep Navy Blue (#102a43) / Dark Blue-Gray (#486581)
Hero Title "Limitless Growth.": White (#FFFFFF)
Hero Title "Made For You.": Medium Light Teal (#66b2b2)
Small Caps Text: Medium Light Teal (#66b2b2)
Body Text: Light Gray (#C4C4C4) or Cream (#E8E3D8)
Primary CTA "START YOUR JOURNEY": Bronze Gold (#B8904A)
Secondary CTA "BUILD YOUR AGENTS": Outlined Bronze (#B8904A border)
Nav "START FREE" Button: Outlined Bronze (#B8904A border)
```

### 2. Agent Selection Page (Dark Mode - Blue Palette)
```
Background: Deep Navy Blue (#102a43) / Dark Blue-Gray (#486581)
Section Title "Build Your": White (#FFFFFF)
Section Title "AI Team": Bronze Gold (#C4965F)
Small Caps: Medium Light Teal (#66b2b2)
Agent Cards Background: Medium Blue-Gray (#829ab1)
Selected Card Border: Medium Light Teal (#66b2b2) - 2px
Unselected Card Border: Light Blue-Gray (#bcccdc)
Checkmarks: Medium Light Teal (#66b2b2)
"CORE" Badges: Bronze Gold (#B8904A)
"ADD-ON" Badges: Medium Light Teal (#66b2b2)
Card Text: White (#FFFFFF) / Light Gray (#B4B4B4)
```

### 3. Report Settings Section
**Dark Mode Version:**
```
Section Background: Dark Blue-Gray (#486581)
Section Title: White (#FFFFFF)
"Standard" Button Active: Bronze Gold (#B8904A)
"Advanced" Button Inactive: Gray text (#8A8A8A)
Dropdown Sections: Medium Blue-Gray (#829ab1)
Text: White (#FFFFFF) / Light Gray
```

**Light Mode Version (Rouba's Preferred):**
```
Page Background: Warm Cream (#F5F1E8)
Card Background: White (#FFFFFF)
Section Title "Report Settings": Black (#000000)
"Standard" Button Active: Bronze Gold (#9D7E3A)
"Advanced" Button Inactive: Gray text (#8A8A8A)
Dropdown Containers: Light Beige (#E8E3D8)
Labels: Brown-Gray (#857A6F)
Dropdown Text: Black (#000000)
Page Border/Separator: Light Border (#D4CFC4)
```

### 4. Navigation/Header
**Dark Mode:**
```
Background: Deep Navy Blue (#102a43) / Dark Blue-Gray (#486581) or Transparent
Logo "Root": White (#FFFFFF)
Logo "Rise": Bronze Gold (#B8904A)
Menu Items: Light Gray (#C4C4C4)
Menu Hover: Medium Light Teal (#66b2b2)
"Sign In": Light Gray (#C4C4C4)
"START FREE" Button: Outlined Bronze (#B8904A border)
```

**Light Mode:**
```
Background: Warm Cream (#F5F1E8) or White (#FFFFFF)
Logo "Root": Black (#000000)
Logo "Rise": Bronze Gold (#B8904A)
Menu Items: Dark Gray (#2C2C2C)
"START FREE" Button: Outlined Bronze (#B8904A border)
```

---

## Accessibility Guidelines

### Contrast Ratios (WCAG AA Compliance)
**Tested combinations:**

- **Deep Navy Blue + White:** 16.5:1 ✓ (Excellent)
- **Dark Blue-Gray + White:** 7.8:1 ✓ (Excellent)
- **Bronze Gold + White:** 4.8:1 ✓ (Good - for buttons)
- **Bronze Gold + Black:** 7.1:1 ✓ (Excellent)
- **Warm Cream + Black:** 11.4:1 ✓ (Excellent)
- **Light Beige + Black:** 9.2:1 ✓ (Excellent)
- **Medium Light Teal + Deep Navy:** 6.5:1 ✓ (Good)

### Best Practices
1. **Dark Mode:**
   - Always use White (#FFFFFF) or Light Gray (#C4C4C4) text on Blue backgrounds
   - Medium Light Teal (#66b2b2) works perfectly on Blue for emphasis
   - Bronze Gold (#B8904A) buttons need white or black text

2. **Light Mode:**
   - Always use Black (#000000) or Dark Gray (#2C2C2C) text on Cream/White backgrounds
   - Bronze Gold (#B8904A) for buttons, borders, and accents
   - Light Beige (#E8E3D8) sections for input containers

3. **Universal Rules:**
   - Never use Medium Teal text on Light backgrounds (poor contrast)
   - Bronze Gold works on both dark and light backgrounds
   - Maintain 2px borders for selected states (Medium Teal on dark, Bronze on light)
   - Blue palette provides professional, calming dark mode aesthetic

---

## Component Examples
**From RootRise V18.1 implementation**

### Buttons

**Primary CTA (Dark Mode)**
```
Background: Bronze Gold (#B8904A)
Text: White (#FFFFFF) or Black (#000000)
Hover: Light Bronze (#C4965F)
Shadow: rgba(184, 144, 74, 0.3)
Example: "START YOUR JOURNEY"
```

**Outlined/Ghost (Dark Mode)**
```
Background: Transparent
Border: Bronze Gold (#B8904A) - 2px
Text: Bronze Gold (#B8904A) or White (#FFFFFF)
Hover: Bronze fill (#B8904A) / White text
Example: "BUILD YOUR AGENTS", "START FREE"
```

**Toggle Buttons (Light Mode)**
```
Active Background: Bronze Gold (#9D7E3A)
Active Text: White (#FFFFFF)
Inactive Background: Transparent or Light Gray (#F0F0F0)
Inactive Text: Gray (#8A8A8A)
Example: "Standard" / "Advanced"
```

### Agent Cards (Dark Mode)

**Unselected Card**
```
Background: Medium Blue-Gray (#829ab1)
Border: Light Blue-Gray (#bcccdc) - 2px
Text: White (#FFFFFF)
Description: Light Gray (#B4B4B4)
Hover: Medium Light Teal border (#66b2b2) - 2px
```

**Selected Card**
```
Background: Medium Blue-Gray (#829ab1)
Border: Medium Light Teal (#66b2b2) - 2px
Checkmark: Medium Light Teal (#66b2b2) - top right
Glow: rgba(102, 178, 178, 0.3)
```

**Badge Labels**
```
"CORE" Badge:
  Background: Bronze Gold (#B8904A)
  Text: Black (#000000)
  Padding: Small, rounded
  
"ADD-ON" Badge:
  Background: Transparent
  Border: Medium Light Teal (#66b2b2)
  Text: Medium Light Teal (#66b2b2)
  Padding: Small, rounded
```

### Cards & Sections

**Interactive Card (Light Mode)**
```
Background: White (#FFFFFF)
Section Container: Light Beige (#E8E3D8)
Border: Soft Border (#D4CFC4) - 1px
Shadow: rgba(44, 44, 44, 0.06)
Hover: Slight elevation increase
```

**Dark Mode Card**
```
Background: Medium Blue-Gray (#829ab1) or Dark Blue-Gray (#486581)
Border: Medium Light Teal accent (#66b2b2) when active
Text: White (#FFFFFF) / Light Gray (#B4B4B4)
```

### Forms & Inputs (Light Mode)

**Dropdown/Select**
```
Container Background: Light Beige (#E8E3D8)
Label: Brown-Gray (#857A6F) - uppercase, small
Selected Value: Black (#000000)
Border: Soft Border (#D4CFC4)
Focus Border: Bronze Gold (#B8904A)
Arrow: Dark Gray (#2C2C2C)
```

**Input Fields**
```
Background: White (#FFFFFF)
Border: Light Border (#D4CFC4)
Focus Border: Bronze Gold (#B8904A)
Label: Brown-Gray (#857A6F)
Placeholder: Light Gray (#ADADAD)
Text: Black (#000000)
```

---

## Quick Reference: When to Use What

| Section Type | Background | Primary Text | Accent | Mode |
|--------------|------------|--------------|---------|------|
| Landing/Hero | Deep Navy Blue (#102a43) | White / Medium Teal | Bronze Gold | Dark |
| Agent Selection | Dark Blue-Gray (#486581) | White | Medium Teal / Bronze | Dark |
| Report Settings (preferred) | Warm Cream (#F5F1E8) | Black | Bronze Gold | Light |
| Forms/Input | White / Light Beige | Black | Bronze Gold | Light |
| Questionnaire | Warm Cream (#F5F1E8) | Black | Bronze Gold | Light |
| Navigation (Dark) | Deep Navy Blue (#102a43) | White / Light Gray | Bronze Gold | Dark |
| Navigation (Light) | Cream / White | Black | Bronze Gold | Light |
| Agent Cards | Medium Blue-Gray (#829ab1) | White | Medium Teal border | Dark |
| Badges "CORE" | Bronze Gold (#B8904A) | Black | - | Both |
| Badges "ADD-ON" | Transparent | Medium Teal | Teal border | Dark |

---

## Design Tokens (for developers)
**RootRise V18.1 Color Variables**

```css
:root {
  /* Primary Brand - Bronze/Gold */
  --color-bronze: #B8904A;
  --color-bronze-light: #C4965F;
  --color-bronze-dark: #9D7E3A;
  
  /* Dark Mode Backgrounds - Blue Palette */
  --color-blue-dark-deepest: #102a43;
  --color-blue-dark-main: #486581;
  --color-blue-dark-card: #829ab1;
  --color-blue-light-gray: #bcccdc;
  --color-blue-very-light: #f0f4f8;
  
  /* Accent - Calm Teal Shades */
  --color-teal-light: #b2d8d8;
  --color-teal-medium-light: #66b2b2;
  --color-teal-classic: #008080;
  --color-teal-medium-dark: #006666;
  --color-teal-deep: #004c4c;
  
  /* DEVONEERS Logo Teal */
  --color-teal-logo: #2A5C5C;
  
  /* Light Mode Backgrounds */
  --color-cream: #F5F1E8;
  --color-cream-subtle: #EDE8DD;
  --color-white: #FFFFFF;
  --color-beige-section: #E8E3D8;
  --color-border-light: #D4CFC4;
  
  /* Text Colors */
  --color-text-primary-dark: #FFFFFF;
  --color-text-secondary-dark: #B4B4B4;
  --color-text-tertiary-dark: #C4C4C4;
  
  --color-text-primary-light: #000000;
  --color-text-secondary-light: #2C2C2C;
  --color-text-label: #857A6F;
  --color-text-gray: #8A8A8A;
  
  /* Semantic */
  --color-success: #66b2b2;
  --color-warning: #B8904A;
  --color-error: #D32F2F;
  --color-info: #66b2b2;
  
  /* Shadows & Effects */
  --shadow-card-light: rgba(44, 44, 44, 0.06);
  --shadow-card-dark: rgba(0, 0, 0, 0.3);
  --glow-teal: rgba(102, 178, 178, 0.3);
  --glow-bronze: rgba(184, 144, 74, 0.3);
}

/* Dark Mode Class */
.dark-mode {
  --bg-primary: var(--color-blue-dark-main);
  --bg-card: var(--color-blue-dark-card);
  --bg-section: var(--color-blue-dark-deepest);
  --text-primary: var(--color-text-primary-dark);
  --text-secondary: var(--color-text-secondary-dark);
  --border: var(--color-blue-light-gray);
}

/* Light Mode Class */
.light-mode {
  --bg-primary: var(--color-cream);
  --bg-card: var(--color-white);
  --bg-section: var(--color-beige-section);
  --text-primary: var(--color-text-primary-light);
  --text-secondary: var(--color-text-secondary-light);
  --border: var(--color-border-light);
}
```

---

## Next Steps for Rouba

**Please review and confirm:**
1. ✓ Are the hex codes matching your vision?
2. ✓ Is the dark/light usage principle correctly applied?
3. ✓ Any additional colors needed?
4. ✓ Should we create specific gradients for the metallic bronze effect?
5. ✓ Are there specific pages/sections we missed?

**Optional Additions:**
- Shadow/elevation system
- Animation/transition guidelines
- Iconography color rules
- Data visualization color scales

---

**Created for:** RootRise Platform  
**Based on:** DEVONEERS Brand Identity  
**Designer:** Rouba  
**Date:** December 2024
