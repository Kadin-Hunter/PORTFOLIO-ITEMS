# HunterOPS Portfolio Maintenance

This repository publishes the HunterOPS project index. Preserve its established visual system unless the owner explicitly requests a redesign.

- Keep the dark HunterOPS mark, violet/cyan palette, editorial typography, and restrained card-icon glow.
- Desktop project cards must have equal width and equal height. Use the responsive auto-fit grid only; never introduce featured spans, masonry placement, `nth-child` sizing, or uneven cards.
- Preserve the mobile progression: responsive desktop grid, two columns on tablet, one content-safe column on phone.
- Keep project cards in alphabetical display order using their explicit inline `order` values.
- Treat `.project`, `.card-main`, `.description`, and `.visit` as layout infrastructure. Do not remove or rename them.
- Titles are capped at two lines and descriptions at four lines so a copy change cannot displace card CTAs. Put longer detail on the linked project page.
- Preserve the Cliptory App Store button, privacy/no-data-collection language, feedback invitation, native external-microphone note for Neper, and every verified destination link.
- Before publishing, inspect the full diff, run `git diff --check`, and verify desktop and mobile layouts plus changed links.

If a requested change conflicts with these rules, ask the owner before altering the design system.
