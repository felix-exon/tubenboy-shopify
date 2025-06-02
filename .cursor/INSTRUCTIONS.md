# Project Instructions

## Style Consistency
- Always use the accent color (`--color-accent`) and other CSS variables for colors, spacing, and typography.
- Use consistent text sizes and spacing throughout all templates and sections.
- Follow the style guide in `.cursor/STYLEGUIDE.md` for details.

## Language & Translations
- The main language is **German**. All translation keys must exist in `locales/de.default.json`.
- Always provide an English translation in `locales/en.json` for every new or changed key.
- If unsure about an English translation, use the German value as a placeholder and mark it for review.

## Testing
- Regularly run `shopify theme check` and `shopify theme test` to ensure there are no errors or warnings.
- Do not commit code that causes theme check/test errors or warnings.

## Contribution
- See `.cursor/CONTRIBUTING.md` for more details on workflow and best practices. 