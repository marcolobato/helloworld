# Project Instructions

## Always Read Before Building

Before writing any HTML, CSS, or JavaScript for this project, you MUST read and reference these files:

1. **`styleguide.html`** — The source of truth for all UI components (buttons, cards, typography, etc.). If a component exists here, reuse its exact structure and class names.
2. **`style.css`** — The main stylesheet with all existing rules and utility classes. Do not add styles that already exist here.
3. **`theme/light-hc.css`** and **`theme/dark-hc.css`** — Material Design High Contrast color tokens. All colors MUST come from these token files — never hardcode hex values.

## Missing Component Check

After reading the styleguide, if the task requires a UI component that does NOT exist in `styleguide.html`, you must:

1. **Stop and flag it clearly** — Tell me with a message like:
   > ⚠️ **Missing Component:** `[component name]` is not yet in the styleguide. Do you want me to build it and add it there first?
2. **Wait for my confirmation** before proceeding to build it.
3. If I say yes, build the component in the styleguide first, then use it in the project — not the other way around.

## Rules for This Project

- Never introduce a new component without checking the styleguide first.
- Never use a color that isn't a token from `light-hc.css` or `dark-hc.css`.
- Never duplicate styles that already exist in `style.css`.
- Always keep the styleguide up to date — it is a living document.
