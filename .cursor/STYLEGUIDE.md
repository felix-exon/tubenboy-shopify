# Style Guide

## Colors
- Use CSS variables for all colors. The main accent color is `--color-accent`.
- Do not hardcode color values in templates or stylesheets.

## Typography
- Use theme variables for font family and weight.
- Maintain consistent text sizes for headings, body, and small text.
- Example sizes:
  - Main heading: 2.5rem (desktop), 2rem (mobile)
  - Section heading: 1.2rem
  - Body: 1.1rem

## Spacing
- Use `--page-width` and `--page-margin` for layout.
- Use consistent padding and margin values as defined in the theme.

## Accent Usage
- Use the accent color for:
  - Borders (e.g., footer top border)
  - Headings in menus/sections
  - Link hover states
  - Decorative elements (e.g., underlines)

## Responsive Design
- Ensure all styles adapt to mobile and desktop breakpoints.

## Example
```liquid
<h1 class="page__title">{{ page.title }}</h1>
<style>
  .page__title {
    color: var(--color-foreground);
    font-size: 2.5rem;
    font-weight: var(--font-primary--weight);
  }
</style>
``` 