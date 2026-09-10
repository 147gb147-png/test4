# Technical Scorecard

Browser version of the DuBois Chemicals **Technical Scorecard** site-audit form
(*Fact finding, not fault finding*), converted from the Word `.docx` original.

`technical-scorecard.html` is a single self-contained file — open it in any
browser, no server or build step.

## What it does

- **Visit details** — customer, date, attendees, DuBois rep.
- **Scorecard** — 8 metrics (A–G, I). Click the description that matches what
  you saw on site to score it 0–3.
- **Weighted total** — recalculated live as
  `(A×2)+(B×2)+(C×3)+(D×2)+(E×3)+F+G+I`, out of a maximum of 45.
  Row colour and the left-edge stripe carry the weighting: Critical ×3,
  Very Important ×2, Important ×1.
- **Tier** — the total lands the audit in Tier 1 (<15), 2 (15–25), 3 (25–35) or
  4 (35–45), and the matching Recommended Actions block is highlighted.
  Boundary scores count toward the higher tier.
- **Detailed Summary** — free-text notes per metric plus overall recommendations.
- **Export to PDF** — opens the browser print dialog; choose *Save as PDF*.
  The print stylesheet lays the sheet out for portrait US Letter.

- **Theme** — *Auto / Light / Dark*. Auto follows the operating system;
  an explicit choice overrides it and is remembered per device. The PDF is
  always laid out light-on-white whatever the screen theme.

A draft is kept in the browser's local storage, so a part-finished audit
survives a refresh. *Clear form* wipes it; the theme choice is stored
separately and survives it.
