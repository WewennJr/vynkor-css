# vynkor-css

Vynkor's centralized design system, served at [css.vynkor.fr](https://css.vynkor.fr/vynkor.css).

## Usage

Want to use Vynkor's style on your page? Just drop this line into your `<head>`:

```html
<link rel="stylesheet" href="https://css.vynkor.fr/vynkor.css">
```

That's it. No build step, no dependencies.

## What's included

- **Variables** — colors, spacing, border radius, transitions
- **Reset** — normalized cross-browser base
- **Typography** — Space Grotesk, headings, body, code blocks
- **Buttons** — primary, secondary, ghost, danger + sizes
- **Forms** — inputs, textarea, select, checkbox, labels, hints
- **Cards** — card, card-elevated, stat-card
- **Badges & Alerts** — info, success, warning, danger variants
- **Tables** — responsive with wrapper
- **Navigation** — navbar, sidebar
- **Utilities** — flex, grid, spacing, text helpers

## Theme

Default theme: **Dark Navy** — `#0a0f1a` background, `#1d6fa5` blue accent, Space Grotesk font.

Seasonal and event themes will be available in `themes/` as optional overrides:

```html
<link rel="stylesheet" href="https://css.vynkor.fr/vynkor.css">
<link rel="stylesheet" href="https://css.vynkor.fr/themes/halloween.css">
```

## Structure

```
vynkor-css/
├── vynkor.css       # Main stylesheet
├── themes/          # Optional theme overrides (coming soon)
└── README.md
```