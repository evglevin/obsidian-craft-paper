This repository contains an Obsidian app theme.

## Project files

- `theme.css` — main theme styles and CSS variable overrides.
- `manifest.json` — theme metadata; the folder name must exactly match `manifest.json.name`.

## Styling rules

- Prefer overriding Obsidian CSS variables instead of writing fragile selectors.
- Put general variables under `body`.
- Put color-scheme-specific variables under `.theme-light` and `.theme-dark`.
- Use `:root` sparingly, mainly for variables that truly need to be global.
- Keep selectors low-specificity.
- Avoid `!important`.

## Assets

- Keep fonts, images, and other assets local.
- Do not load remote assets or make network calls.
