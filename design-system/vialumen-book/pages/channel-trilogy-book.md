# Channel Trilogy Book Page Overrides

> **PROJECT:** ViaLumen Book
> **Generated:** 2026-07-11 11:38:25
> **Page Type:** Blog / Article

> ⚠️ **IMPORTANT:** Rules in this file **override** the Master file (`design-system/MASTER.md`).
> Only deviations from the Master are documented here. For all other rules, refer to the Master.

---

## Page-Specific Rules

### Layout Overrides

- **Max Width:** 1200px (standard)
- **Layout:** Full-width sections, centered content
- **Sections:** 1. Hero with search bar, 2. Popular categories, 3. FAQ accordion, 4. Contact/support CTA

### Spacing Overrides

- No overrides — use Master spacing

### Typography Overrides

- No overrides — use Master typography

### Color Overrides

- **Strategy:** Clean, high readability. Minimal color. Category icons in brand color. Success green for resolved.

### Component Overrides

- Avoid: Single large bundle
- Avoid: Large blocking CSS files
- Avoid: Desktop-first causing mobile issues

---

## Page-Specific Components

- No unique components for this page

---

## Recommendations

- Effects: Thick 4px black borders on all major elements, hard offset shadows (4–8px, no blur), mechanical press: translateX/Y equal to shadow offset, slightly rotated cards/badges (-2deg/2deg), high-saturation color blocking, spring/linear animations only
- Performance: Split code by route/feature
- Performance: Inline critical CSS defer non-critical
- Responsive: Start with mobile styles then add breakpoints
- CTA Placement: Search bar prominent + Contact CTA for unresolved questions
