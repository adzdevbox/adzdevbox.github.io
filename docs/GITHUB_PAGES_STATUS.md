# GitHub Pages Status

## Active Context

PROJECT -> APP -> TASK

Task: Reader docs/site GitHub Pages live verification.

Repository:

https://github.com/adzdevbox/adzdevbox.github.io

## Live URLs

Primary live URL:

https://adz-dev-coding.pl/

Reader Privacy Policy URL candidate:

https://adz-dev-coding.pl/reader/privacy/

GitHub Pages URL candidate:

https://adzdevbox.github.io/

## Verification Evidence

Checked on 2026-05-15.

Live route checks over HTTPS returned HTTP 200:

- `https://adz-dev-coding.pl/`
- `https://adz-dev-coding.pl/apps.html`
- `https://adz-dev-coding.pl/privacy/`
- `https://adz-dev-coding.pl/support/`
- `https://adz-dev-coding.pl/reader/`
- `https://adz-dev-coding.pl/reader/privacy/`
- `https://adz-dev-coding.pl/reader/support/`
- `https://www.adz-dev-coding.pl/`

DNS checks:

- `adz-dev-coding.pl` resolves to GitHub Pages A records:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `www.adz-dev-coding.pl` CNAME resolves to `adzdevbox.github.io`.

Repository checks:

- branch: `main`
- origin: `https://github.com/adzdevbox/adzdevbox.github.io.git`
- required root route files are present
- sitemap includes `https://adz-dev-coding.pl/reader/privacy/`
- `robots.txt` points to `https://adz-dev-coding.pl/sitemap.xml`
- `CNAME` contains only `adz-dev-coding.pl`

Content safety checks:

- no missing required route files found
- no broken internal links found in local static checks
- no backend, cookie, analytics, script, or form-processing constructs found
- no obvious secret/token/private-data patterns found
- no Play Console private screenshots or sensitive files observed in the repository file list

## Remaining Manual Steps

- In GitHub Pages settings, enable or confirm Enforce HTTPS if the GitHub UI allows it.
- Replace the Phase 1 privacy scaffold with final reviewed legal/privacy text before treating the page as final compliance material.
- Update Play Console only after the operator confirms the final privacy text is ready for submission.

## Not Validated

- Play Console acceptance
- final legal/privacy compliance
- Android runtime validation
- provider/data-boundary validation
- production release readiness

## Risk Notes

- The Reader Privacy Policy page is reachable, but the current text is still a Phase 1 scaffold and explicitly not final legal copy.
- GitHub UI DNS/HTTPS status can lag behind DNS and curl evidence.
