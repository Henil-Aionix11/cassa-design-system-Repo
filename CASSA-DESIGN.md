# Design System — Surgitutor

Design tokens extracted from [surgitutor.ai](https://www.surgitutor.ai/).

---

## Logo

- **Source**: `https://app.surgitutor.ai/logo.png`
- **Dimensions**: 1024 x 1024px
- **Background**: `rgba(247, 251, 249, 0.9)`

### Favicons

| Type | URL |
|------|-----|
| icon | `https://app.surgitutor.ai/logo.png` |
| shortcut icon | `https://app.surgitutor.ai/logo.png` |
| apple-touch-icon | `https://app.surgitutor.ai/logo.png` |
| favicon.ico | `https://www.surgitutor.ai/favicon.ico` |

---

## Colors

### Semantic

| Role | Hex | RGB | Usage |
|------|-----|-----|-------|
| **Primary** | `#617c75` | `rgb(97, 124, 117)` | CTAs, active states, key interactive elements |
| **Text** (CSS var `--text`) | `#0f2f29` | `rgb(15, 47, 41)` | Primary text, headings, body copy |
| **Secondary / Accent** | `#11856f` | `rgb(17, 133, 111)` | Hero badge, accent links, highlights |
| **Surface** | `#ffffff` | `rgba(255, 255, 255, 0.88)` | Page backgrounds, cards, overlays |
| **On-surface** | `#0c5f50` | `rgb(12, 95, 80)` | Badge text, pill labels, secondary text |

### Full Palette

| Color | Hex | Count | Confidence | Sources |
|-------|-----|-------|------------|---------|
| Teal Gray | `#617c75` | 70 | high | brand-tag, top-nav, hero-subtitle |
| White | `#ffffff` | 48 | high | site-header, nav-cta, studio-shell |
| Emerald | `#11856f` | 36 | high | hero-badge, access-link |
| Dark Teal | `#0f2f29` | 513 | -- | text, borders (most used raw color) |
| Deep Teal | `#0c5f50` | 85 | -- | badge text, pill labels |

### LCH / OKLCH Values

| Hex | LCH | OKLCH |
|-----|-----|-------|
| `#617c75` | `lch(49.79% 11.31 176.87)` | `oklch(56.29% 0.033 177.46)` |
| `#0f2f29` | `lch(16.96% 13.58 178.61)` | `oklch(27.92% 0.039 179.04)` |
| `#11856f` | `lch(49.55% 35.49 174.47)` | `oklch(55.24% 0.1 175.13)` |

### Hover/Focus States

| State | Color |
|-------|-------|
| Hover overlay | `rgba(255, 255, 255, 0.824)` |

---

## Typography

### Font Families

| Font | Source | Variable Font |
|------|--------|---------------|
| **Space Grotesk** | Google Fonts | Yes |
| **Plus Jakarta Sans** | Google Fonts | Yes |
| Arial | System fallback | No |

### Heading Styles (Space Grotesk)

| Size | Rem | Weight | Line Height | Letter Spacing |
|------|-----|--------|-------------|----------------|
| 89.6px | 5.60rem | 700 | 0.95 (tight) | -4.48px |
| 39.2px | 2.45rem | 700 | 1.08 (tight) | -1.372px |
| 33.6px | 2.10rem | 700 | 1.02 (tight) | -1.008px |
| 16.32px | 1.02rem | 700 | 1.22 (tight) | -- |

### Body / UI Styles (Plus Jakarta Sans)

| Context | Size | Rem | Weight | Line Height | Letter Spacing | Transform |
|---------|------|-----|--------|-------------|----------------|-----------|
| heading | 16.32px | 1.02rem | 700 | 1.22 | -- | -- |
| heading | 16px | 1.00rem | 400 | -- | -- | -- |
| heading | 15.68px | 0.98rem | 400 | 1.70 (relaxed) | -- | -- |
| heading | 14.4px | 0.90rem | 400 | 1.60 (relaxed) | -- | -- |
| heading | 14.08px | 0.88rem | 400 | 1.70 (relaxed) | -- | -- |
| link | 16px | 1.00rem | 400 | -- | -- | -- |
| link | 16px | 1.00rem | 700 | -- | -- | -- |
| link | 14.72px | 0.92rem | 400 | -- | -- | -- |
| link | 14.72px | 0.92rem | 700 | -- | -- | -- |
| caption | 13.76px | 0.86rem | 600 | -- | -- | -- |
| caption | 13.44px | 0.84rem | 400 | -- | -- | -- |
| caption | 13.12px | 0.82rem | 400 | -- | -- | -- |
| caption | 13.12px | 0.82rem | 700 | -- | -- | -- |
| caption | 13.12px | 0.82rem | 700 | 0.4992px | uppercase | -- |
| caption | 13.12px | 0.82rem | 600 | -- | -- | -- |
| caption | 12.8px | 0.80rem | 700 | -- | -- | -- |
| caption | 12.48px | 0.78rem | 700 | 0.4992px | uppercase | -- |
| caption | 12.48px | 0.78rem | 700 | -- | -- | -- |
| caption | 12.16px | 0.76rem | 700 | 0.4864px | uppercase | -- |
| caption | 12.16px | 0.76rem | 700 | 0.9728px | uppercase | -- |

---

## Spacing

**Base system**: 8px

| px | rem | Usage frequency |
|----|-----|-----------------|
| 2px | 0.13rem | 2 |
| 4px | 0.25rem | 3 |
| 6px | 0.38rem | 6 |
| 8px | 0.50rem | 2 |
| 9px | 0.56rem | 58 |
| 10px | 0.63rem | 56 |
| 12px | 0.75rem | 22 |
| 14px | 0.88rem | 38 |
| 16px | 1.00rem | 7 |
| 18px | 1.13rem | 38 |
| 20px | 1.25rem | 2 |
| 22px | 1.38rem | 8 |
| 24px | 1.50rem | 95 |
| 26px | 1.63rem | 2 |
| 30px | 1.88rem | 2 |
| 34px | 2.13rem | 1 |
| 40px | 2.50rem | 8 |
| 72px | 4.50rem | 1 |

---

## Border Radius

| Value | Count | Confidence | Used on |
|-------|-------|------------|---------|
| 14px | 7 | medium | img, button, a, div |
| 16px | 5 | medium | div |
| 18px | 6 | medium | div |
| 20px | 1 | low | email CTA |
| 22px | 14 | high | card, div, article |
| 24px | 50 | high | header, article, card, div |
| 30px | 2 | low | div |
| 32px | 5 | medium | div, card |
| 999px | 94 | high | div, span, badge, card (pill shape) |

---

## Borders

| Style | Color | Count | Confidence | Used on |
|-------|-------|-------|------------|---------|
| 1px solid | `rgba(15, 47, 41, 0.1)` | 87 | high | button, div, article, span, card |
| 1px solid | `rgba(15, 47, 41, 0.06)` | 6 | medium | div |
| 1px solid | `rgba(255, 255, 255, 0.72)` | 6 | medium | div, card |
| 1px solid | `rgba(17, 133, 111, 0.12)` | 5 | medium | div, span |
| 1px solid | `rgba(17, 133, 111, 0.1)` | 3 | low | span |
| 1px solid | `rgba(17, 133, 111, 0.18)` | 3 | low | div, a |
| 1px solid | `rgba(17, 133, 111, 0.14)` | 2 | low | div |
| 1px solid | `rgba(255, 255, 255, 0.88)` | 1 | low | header |
| 1px solid | `rgba(255, 255, 255, 0.78)` | 1 | low | div |

---

## Shadows

| Shadow | Count | Confidence |
|--------|-------|------------|
| `rgba(15, 47, 41, 0.05) 0px 14px 30px 0px` | 59 | high |
| `rgba(15, 47, 41, 0.08) 0px 24px 70px 0px` | 7 | high |
| `rgba(15, 47, 41, 0.04) 0px 10px 22px 0px` | 3 | medium |
| `rgba(15, 47, 41, 0.06) 0px 12px 32px 0px` | 2 | low |
| `rgba(17, 133, 111, 0.18) 0px 16px 32px 0px` | 2 | low |
| `rgba(15, 47, 41, 0.05) 0px 14px 28px 0px` | 2 | low |
| `rgba(15, 47, 41, 0.08) 0px 18px 44px 0px, rgba(255, 255, 255, 0.7) 0px 1px 0px 0px inset` | 1 | low |
| `rgba(17, 133, 111, 0.14) 0px 12px 24px 0px` | 1 | low |
| `rgba(34, 197, 94, 0.01) 0px 0px 0px 7.71px` | 1 | low |
| `rgba(15, 47, 41, 0.06) 0px 18px 36px 0px` | 1 | low |

---

## Components

### Buttons

#### 1. Nav CTA (Primary)

| Property | Default | Hover |
|----------|---------|-------|
| Background | `rgba(0, 0, 0, 0)` | `rgba(255, 255, 255, 0.9)` |
| Color | `rgb(255, 255, 255)` | -- |
| Padding | `0px 20px` | -- |
| Border Radius | 14px | -- |
| Border | none | -- |
| Shadow | `rgba(17, 133, 111, 0.18) 0px 16px 32px` | `rgba(17, 133, 111, 0.22) 0px 20px 36px` |
| Font | 14.72px / 700 | -- |
| Transform | none | `translateY(-2px)` |

#### 2. Ghost Button (Secondary)

| Property | Default | Hover |
|----------|---------|-------|
| Background | `rgba(255, 255, 255, 0.72)` | `rgba(255, 255, 255, 0.9)` |
| Color | `rgb(15, 47, 41)` | -- |
| Padding | `0px 20px` | -- |
| Border Radius | 14px | -- |
| Border | `1px solid rgba(15, 47, 41, 0.1)` | -- |
| Shadow | `rgba(15, 47, 41, 0.06) 0px 12px 32px` | `rgba(17, 133, 111, 0.22) 0px 20px 36px` |
| Font | 16px / 700 | -- |
| Transform | none | `translateY(-2px)` |

#### 3. CTA Surface (Contact)

| Property | Default |
|----------|---------|
| Background | `rgba(0, 0, 0, 0)` |
| Color | `rgb(15, 47, 41)` |
| Padding | `30px` |
| Border Radius | 32px |
| Border | `1px solid rgba(255, 255, 255, 0.72)` |
| Shadow | `rgba(15, 47, 41, 0.08) 0px 24px 70px` |
| Font | 16px / 400 |

### Badges / Pills

#### Subtle Pill (studio-chip)

| Property | Value |
|----------|-------|
| Background | `rgba(255, 255, 255, 0.76)` |
| Color | `rgb(12, 95, 80)` |
| Padding | `9px 12px` |
| Border Radius | 999px |
| Border | `1px solid rgba(15, 47, 41, 0.1)` |
| Font | 13.12px / 700 |
| Transform | uppercase |
| Letter Spacing | 0.4992px |

#### Outline Pill (studio-chip-strong)

| Property | Value |
|----------|-------|
| Background | transparent |
| Color | `rgb(12, 95, 80)` |
| Padding | `9px 12px` |
| Border Radius | 999px |
| Border | `1px solid rgba(15, 47, 41, 0.1)` |
| Font | 13.12px / 700 |
| Transform | uppercase |
| Letter Spacing | 0.4992px |

#### Filled Pill (preview-pill)

| Property | Value |
|----------|-------|
| Background | `rgba(17, 133, 111, 0.08)` |
| Color | `rgb(12, 95, 80)` |
| Padding | `9px 14px` |
| Border Radius | 999px |
| Border | `1px solid rgba(17, 133, 111, 0.14)` |
| Font | 12.48px / 700 |

### Links

| Color | Hex | Weight | Text Decoration |
|-------|-----|--------|-----------------|
| Dark Teal | `rgb(15, 47, 41)` / `#0f2f29` | 400 | none |
| Muted Teal | `rgb(97, 124, 117)` / `#617c75` | 400 | none |
| White | `rgb(255, 255, 255)` | 700 | none |
| Deep Teal | `rgb(12, 95, 80)` / `#0c5f50` | 700 | none |

---

## Breakpoints

| Breakpoint | Usage |
|------------|-------|
| 1120px | Desktop |
| 820px | Tablet |
| 560px | Mobile |

---

## Do's and Don'ts

- Do use `999px` border-radius for pill-shaped badges and tags
- Do use rounded corners (14px-24px) consistently across interactive elements
- Do use the primary color (`#617c75`) sparingly -- only for the most important action per screen
- Do maintain 4.5:1 contrast ratio for all body text (WCAG AA)
- Do use `translateY(-2px)` hover effect on buttons for subtle lift
- Do use low-opacity teal shadows (`rgba(15, 47, 41, 0.05)`) for card elevation
- Don't mix border-radius values arbitrarily -- stick to the scale: 14, 22, 24, 32, 999px
- Don't use borders heavier than 1px -- the design uses exclusively 1px solid borders
- Don't use text-decoration on links -- all links use `text-decoration: none`
