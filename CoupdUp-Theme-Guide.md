# CoupdUp Theme Guide

## Brand Colors

### Primary Colors
- **Brand Primary:** `#f3d7c6` - Warm peach (primary buttons, CTAs, highlights)
- **Brand Secondary:** `#d9efe6` - Soft mint green (accents, icons, secondary elements)
- **Background Primary:** `#f9f6f2` - Warm off-white (main backgrounds)
- **Background Secondary:** `#fdfaf7` - Very light warm white (section backgrounds, cards)

### Accent Colors
- **Light Accent:** `#fde2cc` - Cream/light peach (feature icons, subtle highlights)
- **Glass Effect:** `rgba(255,255,255,0.6)` - Semi-transparent white (overlays, navigation)

## Text Colors

### Hierarchy
- **Primary Text:** `#1f2937` - Charcoal gray (headings, important text)
- **Body Text:** `#374151` - Standard gray (main content, descriptions)
- **Muted Text:** `#6b7280` - Medium gray (secondary content, captions)
- **Light Text:** `#9ca3af` - Light gray (placeholder text, subtle labels)

## Interactive States

### Hover Effects
- **Primary Hover:** `#f3d7c6` with 80% opacity
- **Secondary Hover:** `#f3d7c6` with 30% opacity
- **Text Hover:** `#1f2937` (darker text on hover)

### Focus States
- Use primary brand color (`#f3d7c6`) for focus rings and active states

## Gradients

### Brand Gradient
- **Direction:** Linear, top-left to bottom-right
- **Colors:** `#fde2cc` → `#d9efe6`
- **Usage:** Logos, hero elements, premium features

### Subtle Gradient
- **Direction:** Linear, top to bottom
- **Colors:** `#f9f6f2` → `#fdfaf7`
- **Usage:** Large background areas, subtle depth

## Design Principles

### Color Usage Guidelines

1. **Primary Actions:** Always use `#f3d7c6` for main CTAs and primary buttons
2. **Secondary Actions:** Use borders with `#d9efe6` or light hover states
3. **Information Hierarchy:** Use text color progression from `#1f2937` to `#9ca3af`
4. **Backgrounds:** Layer `#f9f6f2` (main) with `#fdfaf7` (sections) for depth
5. **Accents:** Use `#fde2cc` and `#d9efe6` alternately for feature icons and highlights

### Accessibility
- All color combinations meet WCAG 2.1 AA contrast requirements
- Primary text (`#1f2937`) on light backgrounds provides 7:1+ contrast ratio
- Muted text (`#6b7280`) maintains 4.5:1+ contrast ratio

### Theme Personality
- **Warm & Approachable:** Peachy, cream tones create friendliness
- **Trustworthy:** Muted, sophisticated color choices
- **Clean & Modern:** High contrast, plenty of white space
- **Premium Feel:** Subtle gradients and refined color palette

## Implementation Examples

### Buttons
```css
/* Primary Button */
background: #f3d7c6;
color: #1f2937;
hover: #f3d7c6 (80% opacity);

/* Secondary Button */
border: 1px solid #d9efe6;
color: #374151;
hover: #f3d7c6 (30% opacity);
```

### Cards & Sections
```css
/* Main Card */
background: #fdfaf7;
border: 1px solid rgba(229, 231, 235, 1);

/* Feature Highlight */
background: #fde2cc or #d9efe6;
```

### Text Styling
```css
/* Heading */
color: #1f2937;
font-weight: 600;

/* Body Text */
color: #374151;
font-weight: 400;

/* Caption */
color: #6b7280;
font-size: 0.875rem;
```

## Color Palette Summary

| Purpose | Hex Code | RGB | Usage |
|---------|----------|-----|-------|
| Primary Brand | `#f3d7c6` | rgb(243, 215, 198) | CTAs, highlights |
| Secondary Brand | `#d9efe6` | rgb(217, 239, 230) | Accents, icons |
| Background Main | `#f9f6f2` | rgb(249, 246, 242) | Page backgrounds |
| Background Alt | `#fdfaf7` | rgb(253, 250, 247) | Cards, sections |
| Light Accent | `#fde2cc` | rgb(253, 226, 204) | Subtle highlights |
| Text Primary | `#1f2937` | rgb(31, 41, 55) | Headings |
| Text Body | `#374151` | rgb(55, 65, 81) | Main content |
| Text Muted | `#6b7280` | rgb(107, 114, 128) | Secondary content |
| Text Light | `#9ca3af` | rgb(156, 163, 175) | Placeholders |

---

*Use this theme guide to create consistent, on-brand designs for the CoupdUp app and related materials.*