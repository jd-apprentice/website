# Shell comparison caption overlap: evidence

Before and after captures for the HorneroOS website home page shell comparison.

- Captured 2026-11-20 with Chromium against the local Astro dev server.
- Desktop viewport: 1280x900. Mobile viewport: 390x844.
- `before-*` comes from `main` before the fix. `after-*` comes from the `fix/look-compare-caption` branch.
- `*-caption-*` crops show only the caption row, where the two captions overlapped.
- Range position is part of each file name (30, 60, 85 percent).

The fix keeps the wipe on the images, renders one caption under the pair and stops the divider at the image edge.
