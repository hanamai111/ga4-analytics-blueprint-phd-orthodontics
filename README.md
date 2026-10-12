# GA4-1: GP Analytics Blueprint

IBM 6500 | Group 6 | PhD Orthodontics

Shared Quarto infrastructure for one HTML report containing the four assigned deliverables.

## Files and rendering

- Main report: `ga4-1-analytics-blueprint.qmd`
- RStudio project: `GA4-1-GP-Analytics-Blueprint.Rproj`
- Render: `quarto render` (or the RStudio Render button).
- Output: `docs/ga4-1-analytics-blueprint.html`; `docs/index.html` redirects to the report.
- Publication: GitHub Pages from `main`  `/docs`.
- Track completed work in `CONTRIBUTIONS.md`.

## Section ownership

| Member | Member Name | Responsibility |
|--------|-------------|----------------|
| 1 | Han Mai | Quarto Integration & Final Review |
| 2 | Pei Yun Chuang | Analytics Blueprint |
| 3 | Willy Su | KPI Tree / Metric Hierarchy |
| 4 | Xueying Luo | Event / Parameter Map |
| 5 | Yujia Luo | Validation Checklist + Test Cases |

## Simple collaboration workflow

Use one main QMD. Pull before editing; edit only your assigned section. Coordinate editing times because all members share this file. Save, commit your section with a clear message, pull again, resolve conflicts together, and push.

## Consistency guidance

Agree on definitions before final integration: Qualified Consultation Lead, Consultation Inquiry, Engaged Session, CTA Click, Form Start, Successful Form Submission, Service Area, and campaign/channel/landing page/device dimensions. The proposed North Star and proxy are unconfirmed; do not present them as established client facts.

The KPI Tree must match the Analytics Blueprint; the Event Map must support its KPIs; validation cases must test those same events and parameters. Explicitly document unavailable data and assumptions.

Final integration: reviewed 2026-10-11. Canvas submission pending.

Repository: https://github.com/hanamai111/ga4-analytics-blueprint-phd-orthodontics

Published report: https://hanamai111.github.io/ga4-analytics-blueprint-phd-orthodontics/
