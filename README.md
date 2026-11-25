# Lion Rampant Second Edition — Offline Warband Builder

An **unofficial, offline, single-file army builder**. Open `index.html` in Chrome, Firefox, Edge or Safari. No installation or internet required. It can also be hosted on GitHub Pages as a static website.

## Features

- Drag units using the six-dot grip (mouse, touch or pen), or focus the grip and press the Up/Down arrow keys. The designated Leader is pinned to position one. Order persists in browser saves, JSON exports and printed lists.

- Independent print-only special rules glossary toggle (on by default; saved in browser). The print header contains just the warband name, unit count and points used / limit. Unit rule names remain on the profiles even when the glossary is hidden.

- Optional print-only Strength Point tracks in each unit header, between its name and points cost: six empty boxes per row (one row for 6 SP, two for 12 SP). Toggle in the toolbar; the browser remembers the setting. Off by default.

- Toggle between parchment light mode and charcoal dark mode; preference is saved in the browser.
- Medieval-inspired serif headings and burgundy/brass accents; print output remains light.

- The 11 standard second-edition Lion Rampant units, with their basic points and stats.
- Unit upgrades, point changes, dynamic stats and rule summaries.
- One embedded Leader; assign up to two purchased Leader Skills.
- Optional Holy Men & Banners upgrades.
- Optional chapter profiles/variants: Handgonners, firearm Crossbowmen, slingers, pikes, mobile schiltrons, camels, chariots (toggle off by default).
- 24-point default limit; validates 4–10 units, points, Leader selection, Levied Infantry limit, and selected incompatible upgrades.
- Duplicate units (including upgrades and custom names, excluding the Leader designation and Leader skills).
- Save/load in this browser, JSON import/export, and print-friendly roster with a dynamic, deduplicated special rules glossary.
- Italian Condottieri sample warband, as in the rulebook.

## Source references and limitations

Point costs and short-form data were checked against **Lion Rampant Second Edition** (Daniel Mersey, Osprey Games, 2022), especially Chapter 2 (printed pages 64–98), Chapter 3 (printed pages 116–119), and Leader Skills (printed pages 70–71). The interface intentionally uses concise summaries, not reproductions of the book's complete rules.

This is an **MVP** and not an official or comprehensive digital rules reference. It omits many optional scenario rules, randomly determined leader traits, and house-rule customization. Check published rules for gameplay procedures and clarify optional rule use with an opponent. The prototype has not undergone a full unit-by-unit competitive playtest.

The Dragon Rampant Builder by dickloraine (`https://github.com/dickloraine/dragon-rampant-builder`, MIT licence) was examined as a technical reference. This particular prototype is a **standalone implementation**, not a compiled fork of that React repository. A subsequent version could migrate these Lion Rampant 2e datasets into the original React/Redux structure to reuse its more advanced custom-data editor, PWA installation, and backup features.
