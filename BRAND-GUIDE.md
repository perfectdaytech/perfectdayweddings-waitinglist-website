# PerfectDay Weddings — Brand Guide

## Brand Overview
**Tagline:** Plan Your Perfect Day — Without the Stress
**Mission:** Make wedding planning simple, beautiful, and stress-free.

---

## Color Palette

### Primary Colors
| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Sage Green | `#8FAE9A` | rgb(143, 174, 154) | Primary brand color, buttons, accents |
| Sage Dark | `#6B8C76` | rgb(107, 140, 118) | Hover states, darker accents |
| Sage Light | `#A8C4B2` | rgb(168, 196, 178) | Highlights, subtle backgrounds |

### Secondary Colors
| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Ivory | `#F7F5F0` | rgb(247, 245, 240) | Page backgrounds, light sections |
| Champagne | `#E8DCC7` | rgb(232, 220, 199) | Accent backgrounds, cards |
| Champagne Dark | `#D4C4A8` | rgb(212, 196, 168) | Borders, subtle accents |

### Neutral Colors
| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Charcoal | `#2F2F2F` | rgb(47, 47, 47) | Body text, headings, footer background |
| Charcoal Light | `#5A5A5A` | rgb(90, 90, 90) | Secondary text, descriptions |
| White | `#FFFFFF` | rgb(255, 255, 255) | Backgrounds, cards, text on dark |

---

## Typography

### Fonts
| Font | Type | Usage | Google Fonts |
|------|------|-------|--------------|
| **Playfair Display** | Serif | Headlines, titles, brand name | [Link](https://fonts.google.com/specimen/Playfair+Display) |
| **Inter** | Sans-serif | Body text, buttons, UI elements | [Link](https://fonts.google.com/specimen/Inter) |

### Font Sizes
| Element | Size | Weight | Font |
|---------|------|--------|------|
| H1 (Hero) | 48-64px (clamp: 2.5rem - 4rem) | 600 | Playfair Display |
| H2 (Section) | 32-48px (clamp: 2rem - 3rem) | 600 | Playfair Display |
| H3 (Card title) | 22-24px (1.4rem) | 600 | Playfair Display |
| Body | 16px (1rem) | 400 | Inter |
| Small/Caption | 14px (0.875rem) | 400 | Inter |
| Button | 15px (0.95rem) | 600 | Inter |
| Nav links | 14px (0.9rem) | 500 | Inter |

### Font Import
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Playfair+Display:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&display=swap" rel="stylesheet">
```

---

## Spacing

| Size | Value | Usage |
|------|-------|-------|
| XS | 0.5rem (8px) | Tight spacing, icon gaps |
| SM | 1rem (16px) | Standard element spacing |
| MD | 1.5rem (24px) | Card padding, section gaps |
| LG | 2rem (32px) | Section padding |
| XL | 4rem (64px) | Major section spacing |
| XXL | 6rem (96px) | Hero/CTA section padding |

---

## Border Radius

| Element | Radius |
|---------|--------|
| Buttons | 50px (fully rounded) |
| Cards | 16px |
| Input fields | 50px |
| Small elements | 8-12px |
| Icons/Avatars | 50% (circle) |

---

## Buttons

### Primary Button
```css
background: #8FAE9A;
color: #FFFFFF;
padding: 1rem 2rem;
border-radius: 50px;
font-weight: 600;
font-size: 0.95rem;
box-shadow: 0 4px 20px rgba(143, 174, 154, 0.4);
```
**Hover:** Background `#6B8C76`, translateY(-3px)

### Secondary Button (Outline)
```css
background: transparent;
color: #8FAE9A;
border: 2px solid #8FAE9A;
padding: 1rem 2rem;
border-radius: 50px;
```
**Hover:** Fill with primary color

### White Button (On dark backgrounds)
```css
background: #FFFFFF;
color: #6B8C76;
```

---

## Shadows

| Type | Value | Usage |
|------|-------|-------|
| Subtle | `0 2px 20px rgba(0, 0, 0, 0.1)` | Navigation, light elements |
| Card | `0 20px 50px rgba(143, 174, 154, 0.15)` | Hover states on cards |
| Button | `0 4px 20px rgba(143, 174, 154, 0.4)` | Primary buttons |
| Button Hover | `0 8px 30px rgba(143, 174, 154, 0.5)` | Button hover states |

---

## Social Media

### Handles
| Platform | Handle | URL |
|----------|--------|-----|
| Instagram | @perfectdaywed | https://instagram.com/perfectdaywed |
| TikTok | @perfectdaywed | https://tiktok.com/@perfectdaywed |
| Pinterest | @perfectdaywed | https://pinterest.com/perfectdaywed |
| Facebook | TBD | TBD |

### Brand Hashtags
- #PerfectDayWeddings
- #PerfectDayApp
- #WeddingPlanning

---

## Logo Usage

### Files
- `IMG-20260110-WA0014.png` — Main logo (transparent background)
- `IMG-20260112-WA0002.jpg` — Icon/favicon version (sage background)

### Minimum Size
- Digital: 40px width minimum
- Print: 25mm width minimum

### Clear Space
- Maintain padding equal to the height of the "P" in PerfectDay around all sides

---

## Voice & Tone

### Brand Personality
- **Warm** — Friendly and approachable
- **Elegant** — Premium feel without being pretentious
- **Reassuring** — Calm, stress-reducing language
- **Joyful** — Celebrating love and special moments

### Writing Style
- Use "you" and "your" — speak directly to the couple
- Keep sentences concise and clear
- Emphasize benefits over features
- Avoid jargon and technical terms
- Use positive, encouraging language

### Example Phrases
- "Plan your perfect day — without the stress"
- "Everything you need in one beautiful app"
- "Wedding planning should be joyful"
- "Be first up the aisle"

---

## CSS Variables (Copy & Paste)

```css
:root {
    --sage: #8FAE9A;
    --sage-dark: #6B8C76;
    --sage-light: #A8C4B2;
    --ivory: #F7F5F0;
    --champagne: #E8DCC7;
    --champagne-dark: #D4C4A8;
    --charcoal: #2F2F2F;
    --charcoal-light: #5A5A5A;
    --white: #FFFFFF;
}
```

---

## Contact

**Website:** https://perfectday-weddings.com
**Email:** hello@perfectday-weddings.com
