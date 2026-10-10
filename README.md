# GA4-1: GP Analytics Blueprint

IBM 6500 | Group 6 | PhD Orthodontics

Shared Quarto infrastructure for one HTML report containing the four assigned deliverables. This is initial setup; final content is pending.

## Files and rendering

- Main report: `ga4-1-analytics-blueprint.qmd`
- RStudio project: `GA4-1-GP-Analytics-Blueprint.Rproj`
- Render: `quarto render` (or the RStudio Render button).
- Output: `docs/ga4-1-analytics-blueprint.html`; `docs/index.html` redirects to the report.
- Publication: GitHub Pages from `main`  `/docs`.
- Track completed work in `CONTRIBUTIONS.md`.

## Section ownership

| Member | Responsibility |
|--------|----------------|
| 1 | Quarto Integration & Final Review: structure, consistency, rendering, GitHub links, final submission coordination |
| 2 | Analytics Blueprint |
| 3 | KPI Tree |
| 4 | Event / Parameter Map |
| 5 | Validation Checklist + Test Cases |

## Simple collaboration workflow

Use one main QMD. Pull before editing; edit only your assigned section. Coordinate editing times because all members share this file. Save, commit your section with a clear message, pull again, resolve conflicts together, and push. Never force push. Member 1 manages YAML, configuration, appendix, and regenerated HTML. Other members should avoid editing generated HTML. Collaborator invitations are pending exact GitHub usernames.

## Consistency guidance

Agree on definitions before final integration: Qualified Consultation Lead, Consultation Inquiry, Engaged Session, CTA Click, Form Start, Successful Form Submission, Service Area, and campaign/channel/landing page/device dimensions. The proposed North Star and proxy are unconfirmed; do not present them as established client facts.

The KPI Tree must match the Analytics Blueprint; the Event Map must support its KPIs; validation cases must test those same events and parameters. Explicitly document unavailable data and assumptions. No tracking implementation or test results are claimed by this setup.

Final delivery requires QMD + HTML, with clickable repository and verified GitHub Pages links in the appendix. Do not submit the initial skeleton to Canvas.
