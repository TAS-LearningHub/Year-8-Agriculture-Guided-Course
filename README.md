# Year 8 Agriculture guided course

A Year 8, Stage 4 introductory unit contributing to a 100-hour Agriculture Technology elective. It is aligned to the NSW **Agriculture Technology 7–10 Syllabus (2024)**, implemented from 2027.

The local delivery pattern is 20 weeks, 50 × 60-minute periods, 5 periods per fortnight and an average 2.5 hours per week. Additional study is required to complete the 100-hour elective.

The authorised Agriculture Drive folder is the primary unit source. Its Year 8/2026 folder supplies 11 numbered lesson packages covering agriculture, food security, beef, dairy, horticulture, pork and poultry. The modules keep that order but do not claim equal two-week allocations. Exact period placement and all practical, animal-care, local safety, project-plan, assessment and submission requirements remain **Teacher to confirm**.

## Student routes

- `index.html` — course landing page and eleven-module pathway
- `module.html?module=1` through `module.html?module=11` — three named theory sections, exactly ten source-grounded student-learning checks per section, and written evidence
- `folio.html` — exactly 12 locally autosaving evidence records, JSON backup/restore and 12-page Print / Save PDF

## Local build and checks

```powershell
node scripts/build-data.mjs
node scripts/validate-course.mjs
node scripts/serve.mjs
```

The content build reads bounded Module 1–11 handoffs authored in signed-in ChatGPT one named theory section at a time. The release validator checks counts, student-learning question quality, source coverage, stale scaffold content, outcome mapping, visual records, plan status and local links.

Browser storage is specific to the current browser, profile and device. It is evidence preparation, not cloud submission.
