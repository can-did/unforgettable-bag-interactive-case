# Source Integrity Report

## Repository

`can-did/unforgettable-bag-interactive-case`

## Branch

`recovery/source-integrity-v1`

## Current decision

**SOURCE INTEGRITY PASSED**

The approved source package is complete in this recovery branch. Codex implementation remains blocked until PR #5 is reviewed and merged into `main`.

## Verified documents

- `README.md` — full project overview and current gate;
- `AGENTS.md` — source precedence, role boundaries and stop conditions;
- `docs/project-brief.md` — approved career framing, evidence limits and author role;
- `docs/storyboard.md` — Storyboard v2 with seven sections;
- `docs/content.md` — approved public copy, seven mechanics steps, four metrics and three limitations;
- `docs/visual-spec.md` — approved layout, typography, palette, motion and asset paths;
- `docs/codex-tasks/01-static-foundation.md` — restricted Task 01 v2.

## Rejected implementation

The previous `index.html`, `styles.css` and `script.js` were removed from this recovery branch and are not an implementation baseline.

## Verified assets

All seven required public assets exist and are recorded in `assets/asset-register.csv` with source, SHA-256 and dimensions:

1. `assets/images/web/01-hero-bag.webp` — real bag image from the approved Wix landing;
2. `assets/images/web/02-qr-tag-closeup.webp` — real QR asset from the approved Wix landing;
3. `assets/images/web/03-landing-mechanics.webp` — real mechanics visual from the approved Wix landing;
4. `assets/images/web/04-bonus-6.webp` — real 6-bonus visual;
5. `assets/images/web/05-mastercard-bonus.webp` — real Mastercard bonus visual;
6. `assets/images/web/06-store-poster.webp` — exact store poster photographed during the project and attached to the 2021-04-26 Gmail thread;
7. `assets/images/web/07-report-redacted.webp` — publication-safe derivative of the real transaction report attached to the 2021-09-10 Mastercard thread.

## Privacy verification

`07-report-redacted.webp` contains no bag IDs, loyalty-card IDs, receipt numbers, store numbers or store addresses. It preserves only the verified public-safe structure: date, time, city, payment method, payment system, check amount and customer segment.

## Consistency verification

- seven page sections are identical across Storyboard v2 and Content Pack;
- the mechanics contains seven steps in the same order;
- only the four approved metrics are permitted;
- all three real limitations are preserved;
- author and team responsibilities are separated;
- Task 01 may change only `index.html` and `styles.css`;
- Task 01 cannot start from this branch or from an unmerged PR;
- no placeholder asset is accepted as a source.

## Next gate

1. independently review PR #5;
2. merge PR #5 only after status `ACCEPTED`;
3. verify the same files in `main`;
4. only then create and launch Task 01 v2.
