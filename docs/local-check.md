# Local check summary

- Theme: Catppuccin · Prism 0.1.1
- Manifest SHA-256: `d324aa06d65661c4491cf5866d9024fc9811e8240d775ac7c7e589aa37820dd3`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 7.06:1, title 7.06:1, link 6.03:1, tag 5.92:1, code 6.04:1, mark 5.99:1, chosen 6.24:1.
  - Dark: body 11.34:1, title 11.34:1, link 8.05:1, tag 8.07:1, code 8.69:1, mark 7.39:1, chosen 7.69:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
