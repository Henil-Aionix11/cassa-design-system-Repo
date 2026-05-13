# CASSA.io — Unified Design System

> Merged from 28 authenticated pages of https://app.cassa.io
> Generated: May 13, 2026
> Source tool: designlang v12.9.0
> Pages analyzed: Dashboard, Actions, Annual Leave, Activities, Cost Tracker, Memos, Operator Checklists, Purchase Orders, Reports, Tasks, Timesheets, Training/Exams, Variations, Issues, Plant Tracking, Waste Tracking, SDS Register, SWMS, Scheduled Actions, Employees, Locations, Marketplace, Chat Bot, Edit Profile, Company Create, Purchase Order Index

---

## 1. Brand Identity

- **App Name:** CASSA.io (BMS Global)
- **Logo (PNG):** `https://app.cassa.io/img/cassa_logo_new.png` — 182 × 55px (aspect ratio 3.31:1)
- **Favicon:** `https://app.cassa.io/img/casa-32x32.ico` — 32 × 32px
- **Component Library:** Bootstrap (confidence 0.6)
- **Material Language:** Flat / Material-You hybrid
- **Page Type:** Dashboard-centric SPA

---

## 2. Color Palette

### Primary Colors

| Role | Hex | RGB | HSL | Total Usage |
|------|-----|-----|-----|-------------|
| Primary | `#337ab7` | rgb(51, 122, 183) | hsl(208, 56%, 46%) | 1,336 |
| Secondary | `#ed5565` | rgb(237, 85, 101) | hsl(354, 81%, 63%) | 61 |
| Accent | `#016aae` | rgb(1, 106, 174) | hsl(204, 99%, 34%) | 26 |
| Link Hover | `#1c84c6` | rgb(28, 132, 198) | hsl(201, 75%, 44%) | 21 |
| Legacy Primary | `#428bca` | rgb(66, 139, 202) | hsl(208, 56%, 53%) | 170 |

### Neutral Colors

| Hex | RGB | HSL | Total Usage | Role |
|-----|-----|-----|-------------|------|
| `#676a6c` | rgb(103, 106, 108) | hsl(204, 2%, 41%) | 33,464 | Body text, borders |
| `#ffffff` | rgb(255, 255, 255) | hsl(0, 0%, 100%) | 15,710 | Backgrounds, card surfaces |
| `#66788a` | rgb(102, 120, 138) | hsl(210, 15%, 47%) | 5,592 | Secondary text, sidebar links |
| `#000000` | rgb(0, 0, 0) | hsl(0, 0%, 0%) | 3,086 | Headings, strong text |
| `#a3aeb9` | rgb(163, 174, 185) | hsl(210, 14%, 68%) | 1,812 | Input borders, disabled text |
| `#999c9e` | rgb(153, 156, 158) | hsl(204, 3%, 61%) | 758 | Muted text, placeholders |
| `#555555` | rgb(85, 85, 85) | hsl(0, 0%, 33%) | 952 | Dark text variant |
| `#e5e6e7` | rgb(229, 230, 231) | hsl(210, 4%, 90%) | 356 | Input borders |
| `#e7eaec` | rgb(231, 234, 236) | hsl(204, 12%, 92%) | 200 | Table borders, dividers |
| `#dfe4ed` | rgb(223, 228, 237) | hsl(219, 27%, 90%) | 561 | Sidebar text |
| `#c4c4c4` | rgb(196, 196, 196) | hsl(0, 0%, 77%) | 54 | Disabled states |
| `#414d58` | rgb(65, 77, 88) | hsl(209, 15%, 30%) | 104 | Dark surface variant |
| `#777777` | rgb(119, 119, 119) | hsl(0, 0%, 47%) | 102 | Tertiary text |

### Background Colors

| Hex | Usage | Where |
|-----|-------|-------|
| `#2f4050` | Sidebar | Dark sidebar navigation background |
| `#f1f5f8` | Content area | Main content background, page body |
| `#ffffff` | Cards/Panels | Card surfaces, modals, dropdowns |
| `#f2dede` | Error alert | Danger/error alert background |

### Status / Semantic Colors

| Role | Hex | RGB | Usage |
|------|-----|-----|-------|
| Success | `#1ab394` | rgb(26, 179, 148) | Badges, success buttons |
| Success Alt | `#10b981` | rgb(16, 185, 129) | 91 uses |
| Warning | `#f8ac59` | rgb(248, 172, 89) | Warning labels |
| Warning Alt | `#f59e0b` | rgb(245, 158, 11) | 110 uses |
| Danger | `#ed5565` | rgb(237, 85, 101) | Delete buttons, error badges |
| Danger Alt | `#d14343` | rgb(209, 67, 67) | 48 uses |
| Danger Dark | `#a94442` | rgb(169, 68, 66) | Error text |
| Info | `#1c84c6` | rgb(28, 132, 198) | Info buttons, links |
| Info Alt | `#1e90ff` | rgb(30, 144, 255) | Border accents |

### Full Unique Color Inventory (64 colors detected)

Top 20 by usage:

| Hex | Contexts | Total Count |
|-----|----------|-------------|
| `#676a6c` | text, border | 33,464 |
| `#ffffff` | text, border, background | 15,710 |
| `#66788a` | text, border, background | 5,592 |
| `#000000` | text, border, background | 3,086 |
| `#a3aeb9` | background, text, border | 1,812 |
| `#2f4050` | background, border, text | 1,743 |
| `#337ab7` | background, border, text | 1,336 |
| `#555555` | text, border | 952 |
| `#999c9e` | text, border | 758 |
| `#dfe4ed` | text, border | 561 |
| `#f1f5f8` | background, border | 478 |
| `#e5e6e7` | text, border | 356 |
| `#e7eaec` | text, border | 200 |
| `#428bca` | text, border | 170 |
| `#f59e0b` | text, background, border | 110 |
| `#414d58` | background | 104 |
| `#777777` | text, border | 102 |
| `#a7b1c2` | background, text, border | 92 |
| `#10b981` | text, background, border | 91 |
| `#a94442` | text, border | 83 |

---

## 3. Typography

### Font Families

| Family | Total Usage | Purpose | Source |
|--------|-------------|---------|--------|
| `Open Sans` | 12,611 | Primary — body, headings, UI | Google Fonts |
| `Manrope` | 2,609 | Secondary — sidebar, navigation | Google Fonts |
| `Raleway` | 308 | Accent — certain headings | Google Fonts |
| `Helply-Inter` | 270 | Chat widget (CASSA Support) | Self-hosted |
| `Arial` | 1 | Fallback | System |

### Icon Fonts

| Family | Source |
|--------|--------|
| Glyphicons Halflings | Self-hosted (Bootstrap 3) |
| FontAwesome | Self-hosted |
| summernote | Self-hosted (rich text editor) |

### Type Scale

| Size (px) | Size (rem) | Weight | Line Height | Letter Spacing | Used On |
|-----------|------------|--------|-------------|----------------|---------|
| 140px | 8.75rem | 400 | 140px | normal | Icons (large decorative) |
| 30px | 1.875rem | 700 | 33px | normal | h2, page titles |
| 24px | 1.5rem | 700 | 33.6px | normal | h3 |
| 22px | 1.375rem | 400–700 | 31.43px | normal | h4, section titles |
| 21px | 1.3125rem | 700 | 21px | normal | Button icons |
| 18px | 1.125rem | 600 | 25.71px | normal | Sidebar nav items, buttons |
| 16px | 1rem | 400 | 22.86px | normal | Links, paragraph text |
| 15px | 0.9375rem | 700 | 21.43px | normal | h5, strong text, labels |
| 14px | 0.875rem | 400 | 20px | normal | Body default, inputs, table cells |
| 13px | 0.8125rem | 400–600 | 14.3–18.57px | normal | Small text, table headers |
| 12px | 0.75rem | 400 | 17.14px | normal | Captions, helper text |
| 11px | 0.6875rem | 600 | 11px | normal | Badges, micro text |
| 10px | 0.625rem | 400 | normal | normal | Minimal/hidden text |

### Heading Scale

```css
h2 { font-family: 'Open Sans'; font-size: 30px; font-weight: 700; line-height: 33px; }
h3 { font-family: 'Open Sans'; font-size: 24px; font-weight: 700; line-height: 33.6px; }
h4 { font-family: 'Open Sans'; font-size: 22px; font-weight: 400; line-height: 31.43px; }
h5 { font-family: 'Open Sans'; font-size: 15px; font-weight: 700; line-height: 21.43px; }
```

### Body Text

```css
body {
  font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-size: 14px;
  font-weight: 400;
  line-height: 20px;
  color: #676a6c;
}
```

### Font Weights in Use

| Weight | Usage | Purpose |
|--------|-------|---------|
| 400 | Most common | Body text, inputs, labels |
| 500 | Navigation | Sidebar links, badges |
| 600 | Emphasis | Sub-headers, small bold |
| 700 | Headings | Page titles, section headers |

---

## 4. Spacing System

**Base unit:** 2px

| Token | Value | Rem | Common Usage |
|-------|-------|-----|--------------|
| spacing-1 | 1px | 0.0625rem | Borders |
| spacing-2 | 2px | 0.125rem | Input padding (vertical) |
| spacing-4 | 4px | 0.25rem | Badge padding |
| spacing-6 | 6px | 0.375rem | Button padding (vertical) |
| spacing-10 | 10px | 0.625rem | Footer padding |
| spacing-12 | 12px | 0.75rem | Button padding (horizontal), input padding |
| spacing-14 | 14px | 0.875rem | Card gaps |
| spacing-15 | 15px | 0.9375rem | Footer padding, section gaps |
| spacing-18 | 18px | 1.125rem | Card padding |
| spacing-20 | 20px | 1.25rem | Section padding |
| spacing-22 | 22px | 1.375rem | Panel padding |
| spacing-25 | 25px | 1.5625rem | Large button padding |
| spacing-30 | 30px | 1.875rem | Page title margin |
| spacing-34 | 34px | 2.125rem | Header height related |
| spacing-40 | 40px | 2.5rem | Section gaps |
| spacing-50 | 50px | 3.125rem | Large section spacing |
| spacing-52 | 52px | 3.25rem | Sidebar icon area |
| spacing-247 | 247px | 15.4375rem | Sidebar width (collapsed) |
| spacing-270 | 270px | 16.875rem | Sidebar width (expanded) |

---

## 5. Border Radii

| Token | Value | Usage |
|-------|-------|-------|
| `radius-none` | 0px | Modals, dropdowns, badges (Bootstrap default) |
| `radius-xs` | 2px | Inputs, small buttons |
| `radius-sm` | 4px | Standard buttons, cards, inputs (most common) |
| `radius-md` | 5px | Alternate button style |
| `radius-lg` | 10px | Large cards, panels |
| `radius-full` | 50px | Avatar images, round buttons |
| `radius-pill` | 9999px | Pills, fully rounded elements |

---

## 6. Elevation & Shadows

### Shadow Scale

**xs** — Subtle glow (sidebar, dropdowns)
```css
box-shadow: rgba(86, 96, 117, 0.7) 0px 0px 3px 0px;
```

**sm** — Card shadow (default)
```css
box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 3px 0px;
```

**sm-alt** — Tailwind-style subtle
```css
box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0) 0px 0px 0px 0px, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
```

**md** — Content area subtle
```css
box-shadow: rgba(0, 0, 0, 0.04) 0px 0px 10px 0px;
```

**md-alt** — Panel shadow
```css
box-shadow: rgb(238, 238, 238) 4px 4px 8px 0px;
```

**lg** — Dropdown/modal overlay
```css
box-shadow: rgba(0, 0, 0, 0.176) 0px 6px 12px 0px;
```

**lg-alt** — Marketplace card hover (marketplace, training pages)
```css
box-shadow: rgba(0, 0, 0, 0.07) 4px 2px 20px 1px;
```

**sm-inset** — Edit profile toggle switches
```css
box-shadow: rgb(223, 223, 223) 0px 0px 0px 0px inset;
```

**xs-inset** — Company create form inputs
```css
box-shadow: rgba(0, 0, 0, 0.075) 0px 1px 1px 0px inset;
```

**card-flat** — Company create card bottom border
```css
box-shadow: rgb(221, 221, 221) 0px 3px 0px 0px;
```

**sm-left** — Edit profile sidebar shadow
```css
box-shadow: rgba(0, 0, 0, 0.1) -1px 1px 3px 0px;
```

**sm-dark** — Edit profile card emphasis
```css
box-shadow: rgba(0, 0, 0, 0.4) 0px 1px 3px 0px;
```

### Z-Index Map

| Layer | Z-Index | Elements |
|-------|---------|----------|
| Base | 1–2 | Sidebar navigation, sticky elements |
| Dropdown | 1000 | Top navbar, dropdown menus |
| Modal | 1050+ | Modals, alerts |
| Toast/Overlay | 2147483647 | Loading bars (pace.js), critical overlays |

---

## 7. Breakpoints & Responsive

| Name | Value | Type | Usage |
|------|-------|------|-------|
| xs | 280px | min-width | Smallest mobile |
| xs-max | 350px | max-width | Small mobile cap |
| sm | 480px | min-width | Mobile landscape |
| sm-max | 599px | max-width | Mobile cap |
| sm-alt | 600px | min-width | Tablet start |
| md | 768px | min/max-width | Tablet |
| md-alt | 782px | min-width | Tablet wide |
| lg | 960px | min-width | Desktop start |
| lg-alt | 992px | max-width | Desktop threshold |
| lg-wide | 1024px | max-width | Small desktop cap |
| xl | 1170px | min-width | Large desktop |
| xl-alt | 1200px | max-width | XL threshold |
| xl-wide | 1280px | min-width | Wide desktop |
| 2xl | 1600px | min-width | Ultra-wide |

---

## 8. Motion & Animation

### Duration Tokens

| Token | Value | Usage |
|-------|-------|-------|
| `duration-xs` | 150ms | Hover states, focus rings |
| `duration-md` | 300ms | Standard transitions |
| `duration-lg` | 400ms | Panel slides |
| `duration-xl` | 500ms | Page transitions |

### Easing Families

| Name | Value | Usage |
|------|-------|-------|
| Spring | `cubic-bezier(0.8, 0.5, 0.2, 1.4)` | Bouncy interactions |
| Ease-in-out | `ease` | Standard hover/focus |
| Linear | `linear` | Opacity fades |
| Material | `cubic-bezier(0.4, 0, 0.2, 1)` | Smooth slide-in |

### Common Transitions

```css
transition: all 0.3s cubic-bezier(0.8, 0.5, 0.2, 1.4);  /* Spring bounce */
transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;  /* Input focus */
transition: opacity 0.15s linear;  /* Fade in/out */
transition: transform 0.3s ease-out;  /* Slide transforms */
transition: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);  /* Material motion */
```

### Keyframe Animations

```css
@keyframes progress-bar-stripes {
  0% { background-position: 40px 0px; }
  100% { background-position: 0px 0px; }
}

@keyframes fa-spin {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(359deg); }
}

@keyframes bounce {
  0%, 20%, 50%, 80%, 100% { transform: translateY(0px); }
  40% { transform: translateY(-30px); }
  60% { transform: translateY(-15px); }
}

@keyframes flash {
  0%, 50%, 100% { opacity: 1; }
  25%, 75% { opacity: 0; }
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.1); }
  100% { transform: scale(1); }
}

@keyframes rubberBand {
  0% { transform: scale(1); }
  30% { transform: scaleX(1.25) scaleY(0.75); }
  40% { transform: scaleX(0.75) scaleY(1.25); }
  60% { transform: scaleX(1.15) scaleY(0.85); }
  100% { transform: scale(1); }
}

@keyframes sk-waveUploadStretchDelay {
  /* Upload progress wave animation */
  0%, 40%, 100% { transform: scaleY(0.4); }
  20% { transform: scaleY(1); }
}

/* SweetAlert modal animations (marketplace, training pages) */
@keyframes showSweetAlert {
  0% { transform: scale(0.7); }
  45% { transform: scale(1.05); }
  80% { transform: scale(0.95); }
  100% { transform: scale(1); }
}

@keyframes hideSweetAlert {
  0% { transform: scale(1); }
  100% { transform: scale(0.5); }
}

@keyframes slideFromTop {
  0% { top: 0%; }
  100% { top: 50%; }
}

@keyframes slideToTop {
  0% { top: 50%; }
  100% { top: 0%; }
}

/* Page entrance animations (dashboard, plant tracking) */
@keyframes fadeInDown {
  0% { opacity: 0; transform: translateY(-20px); }
  100% { opacity: 1; transform: translateY(0); }
}

@keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}

@keyframes slideDown {
  0% { transform: translateY(-100%); }
  100% { transform: translateY(0); }
}
```

---

## 9. Components

### Buttons

**Total instances across app:** 250+
**Base style:**

```css
.button {
  font-family: 'Open Sans', sans-serif;
  font-size: 14px;
  font-weight: 400;
  padding: 6px 12px;
  border-radius: 4px;
  border: 1px solid transparent;
  cursor: pointer;
  transition: all 0.3s cubic-bezier(0.8, 0.5, 0.2, 1.4);
}
```

**Variants:**

| Variant | Background | Color | Border | Usage |
|---------|-----------|-------|--------|-------|
| Primary | `#337ab7` | `#ffffff` | transparent | Main actions (Add New, Save) |
| Default | `#ffffff` | `#66788a` | transparent | Secondary actions (Filter, Cancel) |
| Success | `#1ab394` | `#ffffff` | `#1ab394` | Positive actions (Approve, Read) |
| Warning | `#f8ac59` | `#ffffff` | `#f8ac59` | Caution actions (Pending) |
| Danger | `#ed5565` | `#ffffff` | `#ed5565` | Destructive actions (Delete, Reject) |
| Info | `#1c84c6` | `#ffffff` | `#1c84c6` | Informational (View, Details) |
| Muted | `#f1f5f8` | `#66788a` | transparent | Low-emphasis (Export, Print) |
| Disabled | `#f1f5f8` | `#c4c4c4` | transparent | Inactive state |

**Size variants:**

| Size | Padding | Font Size |
|------|---------|-----------|
| xs | 1px 5px | 12px |
| sm | 4px 18px | 13px |
| md (default) | 6px 12px | 14px |
| lg | 6px 25px | 14px |
| icon-only | 1px 6px | 22px (border-radius: 50%) |

### Cards / Panels

```css
.card {
  background-color: #ffffff;
  border-radius: 4px;
  box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 3px 0px;
  padding: 0;
  border: none;
}

.card-header {
  padding: 15px 20px;
  border-bottom: 1px solid #e7eaec;
}

.card-body {
  padding: 15px 20px;
}
```

### Inputs

```css
.input {
  background-color: #ffffff;
  color: #676a6c;
  border: 1px solid #e5e6e7;
  border-radius: 4px;
  font-size: 14px;
  font-weight: 400;
  padding: 6px 12px;
  line-height: 20px;
  transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}

.input:focus {
  border-color: #1c84c6;
  box-shadow: 0 0 0 0.2rem rgba(28, 132, 198, 0.25);
}

.input-sm {
  padding: 2px 12px;
  border-radius: 2px;
}

.select {
  background-color: #ffffff;
  color: #676a6c;
  border: 1px solid #a3aeb9;
  border-radius: 2px;
  padding: 4px 18px;
  font-size: 13px;
}
```

### Navigation — Sidebar

```css
.sidebar {
  background-color: #2f4050;
  width: 270px;  /* expanded */
  position: fixed;
  height: 100vh;
  z-index: 1;
  font-family: 'Manrope', sans-serif;
}

.sidebar-link {
  color: #a7b1c2;
  font-size: 14px;
  font-weight: 500;
  padding: 14px 20px;
  display: block;
  text-decoration: none;
  transition: all 0.3s;
}

.sidebar-link:hover,
.sidebar-link.active {
  color: #ffffff;
  background-color: #293846;
}

.sidebar-icon {
  color: #a7b1c2;
  width: 18px;
  margin-right: 10px;
}
```

### Navigation — Top Bar

```css
.topbar {
  background-color: #ffffff;
  box-shadow: rgba(0, 0, 0, 0.04) 0px 0px 10px 0px;
  padding: 0;
  position: static;
  z-index: 1000;
  height: 62px;
}

.topbar-link {
  color: #66788a;
  font-size: 14px;
  font-weight: 400;
  padding: 15px 20px;
}
```

### Footer

```css
.footer {
  background-color: #ffffff;
  color: #676a6c;
  font-size: 14px;
  padding: 10px 15px;
  border-top: 1px solid #e7eaec;
}
```

### Modals

```css
.modal-content {
  background-color: #ffffff;
  border-radius: 0px;
  box-shadow: rgba(0, 0, 0, 0.3) 0px 1px 3px 0px;
  border: none;
}

.modal-header {
  padding: 15px 20px;
  border-bottom: 1px solid #e7eaec;
}

.modal-body {
  padding: 15px 20px;
}

.modal-footer {
  padding: 15px 20px;
  border-top: 1px solid #e7eaec;
}

/* Wide modal variant (marketplace, training pages) */
.modal-lg {
  max-width: 850px;
}
```

### Dropdowns

```css
.dropdown-menu {
  background-color: #ffffff;
  border-radius: 0px;
  box-shadow: rgba(86, 96, 117, 0.7) 0px 0px 3px 0px;
  border: 1px solid #676a6c;
  padding: 0;
}

.dropdown-item {
  color: #676a6c;
  font-size: 14px;
  padding: 6px 12px;
}

.dropdown-item:hover {
  background-color: #f1f5f8;
}
```

### Tables

```css
.table {
  width: 100%;
  border-collapse: collapse;
  font-size: 14px;
  color: #676a6c;
}

.table th {
  font-weight: 600;
  padding: 8px;
  border-bottom: 2px solid #e7eaec;
  background-color: #ffffff;
}

.table td {
  padding: 8px;
  border-top: 1px solid #e7eaec;
}

.table-striped tr:nth-child(even) {
  background-color: #f9f9f9;
}

.table-bordered {
  border: 1px solid #808080;
}
```

### Badges / Labels

```css
.badge {
  background-color: #337ab7;
  color: #ffffff;
  font-size: 14px;
  font-weight: 500;
  padding: 2px 8px;
  border-radius: 0px;
  display: inline-block;
}
```

| Variant | Background | Color |
|---------|-----------|-------|
| Default | `#337ab7` | `#ffffff` |
| Success | `#1ab394` | `#ffffff` |
| Warning | `#f8ac59` | `#ffffff` |
| Danger | `#ed5565` | `#ffffff` |
| Info | `#1c84c6` | `#ffffff` |
| Green | `#1ecc2f` | `#ffffff` |
| Purple | `#7d33dd` | `#ffffff` |
| Yellow | `#dad809` | `#ffffff` |

**Pill badge variant** (Employee list page — status badges):

```css
.badge-pill {
  background-color: rgba(16, 185, 129, 0.3);  /* success example */
  color: #10b981;
  font-size: 12px;
  font-weight: 500;
  padding: 8px 31px;
  border-radius: 17.5px;
}
```

Pill badge color variants:

| Status | Background | Text Color |
|--------|-----------|------------|
| Active | `rgba(16, 185, 129, 0.3)` | `#10b981` |
| Warning | `rgba(245, 158, 11, 0.3)` | `#f59e0b` |
| Inactive | `rgba(209, 67, 67, 0.3)` | `#d14343` |

### Avatars

Found on: Employee list, Training, Marketplace pages.

```css
.avatar {
  border-radius: 50%;
  object-fit: fill;
  width: 40px;
  height: 40px;
}

.avatar-sm {
  width: 30px;
  height: 30px;
}
```

### Tabs

```css
.tab {
  color: #676a6c;
  font-size: 14px;
  font-weight: 400;
  padding: 10px 15px;
  border: none;
  border-bottom: 2px solid transparent;
  background: none;
  cursor: pointer;
}

.tab.active {
  color: #337ab7;
  border-bottom-color: #337ab7;
}
```

### Progress Bars

```css
/* Default style (most pages) */
.progress-bar {
  background-color: #337ab7;
  color: #ffffff;
  font-size: 14px;
  border-radius: 0px;
  animation: progress-bar-stripes 2s linear infinite;
}

/* Rounded style (marketplace, training, locations pages) */
.progress-bar-rounded {
  background-color: #d1fae5;
  color: #676a6c;
  font-size: 12px;
  border-radius: 20px;
}
```

### Switches / Toggles

```css
.switch {
  background-color: #337ab7;
  border-radius: 0px;
  border: 1px solid #676a6c;
}

.switch.off {
  background-color: #273a4a;
}
```

### Alerts

```css
.alert-danger {
  background-color: #f2dede;
  border: 1px solid #ebccd1;
  color: #a94442;
  padding: 15px;
  border-radius: 4px;
}
```

---

## 10. Layout System

### Structure

- **0 CSS Grid containers** — app does not use CSS Grid
- **14–34 Flex containers per page** — primary layout mechanism
- **Bootstrap grid system** — 12-column responsive grid

### Flex Patterns

| Direction / Wrap | Frequency |
|-----------------|-----------|
| row / nowrap | ~90% of flex usage |
| row / wrap | ~8% of flex usage |
| column / nowrap | ~2% of flex usage (locations page) |

### Page Layout

```
┌─────────────────────────────────────────────┐
│  Sidebar (270px)  │  Top Navbar (100%)      │
│  bg: #2f4050      │  bg: #ffffff            │
│                    │  shadow: md             │
│  Navigation        ├────────────────────────┤
│  Font: Manrope     │  Content Area           │
│  Links: #a7b1c2    │  bg: #f1f5f8            │
│                    │  padding: 20px          │
│                    │                          │
│                    │  ┌─ Card ────────────┐  │
│                    │  │ bg: #ffffff        │  │
│                    │  │ shadow: sm         │  │
│                    │  │ radius: 4px        │  │
│                    │  └───────────────────┘  │
│                    │                          │
│                    ├────────────────────────┤
│                    │  Footer                  │
│                    │  bg: #ffffff             │
└─────────────────────────────────────────────┘
```

---

## 11. Iconography

### Icon Systems

| System | Type | Usage |
|--------|------|-------|
| FontAwesome 4 | Icon font | Primary icon set (navigation, actions) — most pages |
| FontAwesome 5 Free | Icon font | Updated icons (purchase orders) — weights: 400, 900 |
| FontAwesome 5 Brands | Icon font | Brand icons (purchase orders) — weight: 400 |
| FontAwesome 6 Free | Icon font | Latest icons (purchase orders) — weights: 400, 900 |
| FontAwesome 6 Brands | Icon font | Latest brand icons (purchase orders) — weight: 400 |
| Glyphicons Halflings | Icon font | Bootstrap 3 legacy icons |
| Material Design Icons | Icon font | Marketplace, training pages |
| summernote | Icon font | Rich text editor icons |
| Inline SVG | SVG | 1–2 per page, filled style |

### Marketplace-Specific Icon Fonts

These additional fonts appear on marketplace and training pages:

| Family | Usage |
|--------|-------|
| `proxima_novablack` | Marketplace headings |
| `proxima_nova_rgbold` | Marketplace bold text |
| `proxima_novalight` | Marketplace light text |
| `proxima_nova_rgregular` | Marketplace body |
| `proxima_novaregular_italic` | Marketplace italic |
| `proxima_novasemibold` | Marketplace semi-bold |
| `university-system` | Training/education system icons |

### Icon Styling

- **Default size:** Medium (14–18px)
- **Colors:** `#ffffff` (on dark backgrounds), `#676a6c` (on light backgrounds)
- **Style:** Filled (not outlined)

---

## 12. Image Patterns

| Pattern | Count | Key Styles |
|---------|-------|------------|
| Thumbnail | ~17 per page | `object-fit: fill; border-radius: 0px; shape: square` |
| Avatar | ~1 per page | `object-fit: fill; border-radius: 50%; shape: circular` |

**Common aspect ratios:** 1:1 (thumbnails), 3.57:1 (logo)
**Dominant image shape:** Square
**Border radius on images:** None (square) except avatars (circular)

---

## 13. Accessibility Audit

### Average WCAG Score: ~55% across pages

### Common Failing Color Pairs

| Foreground | Background | Ratio | Issue |
|------------|------------|-------|-------|
| `#777777` | `#ffffff` | 4.48:1 | Barely fails AA (needs 4.5:1) |
| `#66788a` | `#f1f5f8` | 4.15:1 | Sidebar links on light bg |
| `#ffffff` | `#ed5565` | 3.45:1 | White on danger red |
| `#ffffff` | `#1ecc2f` | 2.16:1 | White on green — critical fail |
| `#ffffff` | `#dad809` | 1.52:1 | White on yellow — critical fail |
| `#ffffff` | `#f4ad11` | 1.94:1 | White on orange — critical fail |
| `#ffffff` | `#33b750` | 2.62:1 | White on green variant |
| `#c4c4c4` | `#1c84c6` | 2.33:1 | Disabled text on info |

### Passing Color Pairs

| Foreground | Background | Ratio | Level |
|------------|------------|-------|-------|
| `#ffffff` | `#337ab7` | 4.56:1 | AA |
| `#ffffff` | `#000000` | 21:1 | AAA |
| `#ffffff` | `#7d33dd` | 6.2:1 | AA |
| `#676a6c` | `#f1f5f8` | 4.97:1 | AA |
| `#676a6c` | `#ffffff` | 5.28:1 | AA |

### Remediation Recommendations

- Replace `#1ecc2f` with `#0d8a3e` for white text (ratio 5.1:1)
- Replace `#dad809` with `#8a7d00` for white text (ratio 5.3:1)
- Replace `#f4ad11` with `#946300` for white text (ratio 5.0:1)
- Replace `#ed5565` with `#c9303e` for white text (ratio 4.6:1)

---

## 14. Design System Score

### Average Score: 71/100 (Grade: C)

| Category | Score | Notes |
|----------|-------|-------|
| Color Discipline | 80–92 | Good palette, some sprawl in status colors |
| Typography Consistency | 50 | Too many font families (5) — reduce to 2 |
| Spacing System | 85 | Well-defined scale with 2px base |
| Shadow Consistency | 100 | Clean, consistent elevation system |
| Border Radius Consistency | 90–100 | Consistent 4px default |
| Accessibility | 25–69 | Major contrast failures need fixing |
| CSS Tokenization | 50 | Many hard-coded values, low CSS variable usage |

### Strengths
- Well-defined spacing scale
- Clean elevation/shadow system
- Consistent border radii
- Strong primary color usage

### Issues
- 5 font families — reduce to 2 (Open Sans + Manrope)
- 8+ WCAG contrast failures — white text on bright status colors
- 900+ `!important` rules — prefer specificity over overrides
- 97% of CSS is unused — consider purging
- 14,000+ duplicate CSS declarations
- Only 12 CSS custom properties defined (see below)

### CSS Custom Properties Found

```css
/* FontAwesome 6 (purchase order pages) */
--fa-font-solid: normal 900 1em/1 "Font Awesome 6 Free";
--fa-font-regular: normal 400 1em/1 "Font Awesome 6 Free";
--fa-font-brands: normal 400 1em/1 "Font Awesome 6 Brands";
--fa-style-family-brands: "Font Awesome 6 Brands";
--fa-style-family-classic: "Font Awesome 6 Free";

/* DataTables (reports pages) */
--dt-row-selected: 13, 110, 253;
--dt-row-selected-text: 255, 255, 255;
--dt-row-selected-link: 9, 10, 11;
--dt-row-stripe: 0, 0, 0;
--dt-row-hover: 0, 0, 0;
--dt-column-ordering: 0, 0, 0;
--dt-html-background: white;
```

---

## 15. Brand Voice

- **Tone:** Neutral, professional, workplace/safety-focused
- **Pronoun posture:** Third-person
- **Heading style:** Sentence case, tight (short headings)

### Top CTA Verbs (across all pages)

| Verb | Frequency | Usage |
|------|-----------|-------|
| csv | 33 | Export buttons |
| excel | 29 | Export buttons |
| view | 29 | Action links |
| print | 11 | Export buttons |
| add | 11 | Create actions |
| filter | 6 | Filter controls |
| create | 1 | New record |
| invite | 1 | User management |

### Common Button Labels

- "Add New [Entity]" — primary creation action
- "Filter" — search/filter controls
- "CSV / Excel / Print" — export group (always together)
- "View" — detail navigation
- "Change Status" — workflow transitions
- "Pending" / "Approved" / "Rejected" — status indicators

---

## 16. Do's and Don'ts

### Do's
- Use `#337ab7` as the primary action color consistently
- Use `Open Sans` for all body text and `Manrope` for sidebar navigation
- Use `#676a6c` as the default text color
- Write headings in sentence case, keep them tight/short
- Use 4px border-radius as the default for interactive elements
- Use `#2f4050` exclusively for the sidebar background
- Use `#f1f5f8` for content area backgrounds
- Address users in third-person
- Group export actions (CSV, Excel, Print) together
- Use the defined shadow scale (xs → sm → md → lg)
- Keep spacing in multiples of the 2px base unit

### Don'ts
- Don't use more than 2 font families per page (Open Sans + Manrope)
- Don't use white text on `#1ecc2f`, `#dad809`, `#f4ad11` — they fail WCAG contrast
- Don't use `!important` — prefer specificity
- Don't invent new hex values — use the palette above
- Don't use CSS Grid — the app uses Flexbox + Bootstrap grid
- Don't add border-radius to modals (they use 0px)
- Don't use outlined icon styles — the app uses filled icons

---

## 17. Quick Start Guide

To recreate the CASSA.io design in a new project:

1. **Install fonts:**
   ```html
   <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&family=Manrope:wght@400;500;600;700&display=swap" rel="stylesheet">
   ```

2. **Set base CSS:**
   ```css
   :root {
     --color-primary: #337ab7;
     --color-secondary: #ed5565;
     --color-accent: #016aae;
     --color-success: #1ab394;
     --color-warning: #f8ac59;
     --color-danger: #ed5565;
     --color-info: #1c84c6;
     --color-sidebar-bg: #2f4050;
     --color-content-bg: #f1f5f8;
     --color-card-bg: #ffffff;
     --color-text: #676a6c;
     --color-text-dark: #000000;
     --color-text-muted: #999c9e;
     --color-text-sidebar: #a7b1c2;
     --color-border: #e7eaec;
     --color-input-border: #e5e6e7;
     --font-body: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif;
     --font-nav: 'Manrope', sans-serif;
     --font-size-base: 14px;
     --line-height-base: 20px;
     --radius-sm: 4px;
     --radius-md: 10px;
     --radius-full: 50px;
     --shadow-xs: rgba(86, 96, 117, 0.7) 0px 0px 3px 0px;
     --shadow-sm: rgba(0, 0, 0, 0.3) 0px 1px 3px 0px;
     --shadow-md: rgba(0, 0, 0, 0.04) 0px 0px 10px 0px;
     --shadow-lg: rgba(0, 0, 0, 0.176) 0px 6px 12px 0px;
     --sidebar-width: 270px;
     --spacing-base: 2px;
   }

   body {
     font-family: var(--font-body);
     font-size: var(--font-size-base);
     line-height: var(--line-height-base);
     color: var(--color-text);
     background-color: var(--color-content-bg);
   }
   ```

3. **Design tokens:** Copy the color/spacing/shadow values from this document into your token system
4. **Tailwind users:** Map the CSS variables above to your `tailwind.config.js` `extend` section
5. **Figma:** Use the color palette and type scale tables to recreate tokens in Figma variables

---

_Generated by merging 28 page extractions from https://app.cassa.io_
_Compatible with Claude Design System, Cursor, and any AI coding agent._
