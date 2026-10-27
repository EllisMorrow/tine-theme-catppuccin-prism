# Adaptation notes

Both modes are based on the official open-source Catppuccin Latte and Mocha palettes, the pair referenced by Codex. They are independently mapped to Tine semantic roles; selected surface and text adjustments are documented below.

## Sources

- palette: https://github.com/catppuccin/palette/blob/07d02aa110ef9eb7e7427afca5c73ba9cf7f8ebd/palette.json
- license: https://github.com/catppuccin/palette/blob/07d02aa110ef9eb7e7427afca5c73ba9cf7f8ebd/LICENSE

## Mapping decisions

- light secondary adjusted from #5c5f77 to #565971 for readability on selection and other declared surfaces, including amber marks.
- light link adjusted from #1e66f5 to #1852c8 for readability on selection and other declared surfaces, including amber marks.
- light tag adjusted from #8839ef to #7632d0 for readability on selection and other declared surfaces, including amber marks.
- dark link adjusted from #89b4fa to #8eb7fa for readability on selection and other declared surfaces, including amber marks.
- Base, mantle, primary text and mauve accent follow the upstream Latte / Mocha palette. Secondary text starts from subtext1. Tine surface tiers and quiet selection backgrounds are host adaptations.
- Amber marks mix 20% upstream yellow into the canvas and use explicit readable foregrounds.
- The 21-token API does not control fonts, task marker colors, arbitrary hover rules or every syntax color; no exact Codex UI reproduction is claimed.

## Validation

Local 0.1.0 preview passed Tine's official manifest checker without errors or warnings. A synthetic Chromium fixture verified 21 tokens per mode and light → dark → light switching. Main-canvas body contrast: light 7.06:1, dark 11.34:1; links: 6.03/8.05:1; tags: 5.92/8.07:1. Code, mark and chosen-body pairs also passed the scoped 4.5:1 checks. The user supplied real Windows screenshots of the complete light and dark palettes after testing; these are included in both READMEs. The captures show the public welcome page, not every interaction or platform. Do not treat calculated contrast as proof of all application states or platforms.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.

Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.
