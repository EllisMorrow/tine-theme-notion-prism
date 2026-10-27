# Local check summary

- Theme: Notion · Prism 0.1.1
- Manifest SHA-256: `fce69f199745cf623154f2e010a0422174bb76d02bacd0d118b89646cdc01a95`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 12.26:1, title 12.26:1, link 5.56:1, tag 5.56:1, code 11.15:1, mark 10.63:1, chosen 10.52:1.
  - Dark: body 12.45:1, title 12.45:1, link 5.53:1, tag 5.53:1, code 10.99:1, mark 10.86:1, chosen 10.73:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
