# AGENTS.md — silica-theme

## Project

An **app-agnostic LCD color theme** — a color palette and theming system
inspired by the soft colors of beige/gray LCDs.

**Goals:**
- Single source of truth for colors
- Light and dark variants
- Grounded by real app integrations (see Integrations)

**Non-goals:**
- WCAG compliance tracking (nice aspirational target, not a requirement)
- Build systems, package managers, or distribution packaging

## Color format

Colors are authored in **hex** (e.g., `#c0c5ce`).
The canonical palette lives in `palette.json`.

## Integrations

When changing the palette, update these directories:

| Integration | Directory | Variants |
|---|---|---|
| Alacritty | `alacritty/` | dark |
| CSS | `css/` | light + dark (`prefers-color-scheme`) |

## Naming

"silica" — an understated, single-word name evoking sand, crystal, and
matte surfaces, mapping to the reflective, non-emissive LCD aesthetic.

## Constraints

No CI, no distribution packaging.
