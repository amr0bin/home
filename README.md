# Clinical Reset — three-phase cleaning protocol

An interactive, single-file reference for a domestic cleaning and sanitization routine structured on clinical infection-prevention logic.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The complete interactive protocol. No build step, no dependencies. |

## Structure

The protocol is organised by interval rather than by intensity:

1. **Daily reset** — 15 minutes, evening. Touchpoint containment and end-of-day handover.
2. **Weekly reclean** — 60 minutes, Saturday morning. Zone-by-zone control, cleanest zone to contained zone.
3. **Monthly deep clean** — 120 minutes, first Saturday. Concealed reservoirs, air and moisture systems.

Shared logic — definitions, order of operations, zoning, cloth assignment, contact time, incompatible combinations, agent selection and completion criteria — is stated once in the standing-principles section and applies to all three phases.

## Interaction

- Select a phase from the tabs or the cadence figure; keyboard arrow keys move between phases.
- Check off steps to track progress within a phase. State is held in the page session only and clears on reload.
- The contact-time dial runs a 1, 2 or 5 minute interval for disinfectant dwell time.
- The page prints to a clean checklist; interactive controls are hidden in print.

## Publishing

Serve `index.html` from GitHub Pages: **Settings → Pages → Deploy from branch → root**. The page is self-contained apart from the Asap web font, which loads from Google Fonts.

## Design

- Typeface: Asap and Asap Condensed.
- Palette: `#ffffff` background, `#5d5a5b` text, `#a29f9f` accent, with `#f4f3f3` and `#d9d7d6` as derived surface and rule tones.

## Scope

This adapts clinical infection-prevention principles to a domestic environment. It is not a substitute for regulated healthcare cleaning standards and does not address settings in which clinical care is delivered. Product label instructions and safety data sheets govern all agent use.
