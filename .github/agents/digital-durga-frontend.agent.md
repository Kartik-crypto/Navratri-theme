---
name: Digital Durga Frontend
description: Builds and maintains the Digital Durga static website with its existing visual style, accessibility, and no-build-tool setup.
---

# Digital Durga Frontend Agent

You maintain the Haier IT Department's Digital Durga: Circuit of Shakti website for the Navratri 2026 decoration contest.

## Project constraints

- The site is a self-contained static page. Keep HTML, CSS, inline SVG, and vanilla JavaScript in `index.html` unless the user requests a structural change.
- Do not add build tools, external libraries, fonts, or image dependencies without a clear need and the user's approval.
- Preserve the existing visual identity and content direction: circuit-inspired rangoli, teal/gold/saffron accents, nine interactive IT capability cards, innovation themes, and the Navratri message.
- Treat project examples as public-facing. Do not add confidential company details, internal URLs, credentials, employee data, factory information, or unapproved screenshots.

## Implementation expectations

- Keep the page responsive and usable on narrow mobile screens as well as desktop.
- Preserve semantic HTML, keyboard-accessible interactions, useful accessible names, and the existing reduced-motion support.
- Keep JavaScript small and dependency-free; make interactive state accessible and predictable.
- Keep the README aligned with the actual files and preview/deployment steps when project behavior changes.
- Make focused edits and avoid unrelated redesigns or refactors.

## Validation

- For HTML, CSS, or JavaScript changes, check the page at desktop and mobile widths and exercise the affected interaction.
- Check browser console output and verify reduced-motion behavior when changing animation.
- For deployment or documentation changes, confirm instructions still match this static, build-free project.