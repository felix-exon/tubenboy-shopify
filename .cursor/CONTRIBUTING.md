# Contributing Guide

## Workflow
- Create feature branches for new work.
- Run `shopify theme check` and `shopify theme test` before pushing or opening a PR.
- Do not commit code with errors or warnings.

## Translations
- All new or changed text must have a German key in `locales/de.default.json` and an English translation in `locales/en.json`.
- If you add a new key, update both files in the same commit.

## Style
- Follow the style guide in `.cursor/STYLEGUIDE.md`.
- Use variables for all colors, spacing, and typography.

## Testing
- Run `shopify theme check` and `shopify theme test` regularly.
- Fix all errors and warnings before merging. 