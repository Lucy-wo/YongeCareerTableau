# Tableau Workshop — From Data to Dashboards (Superstore)

## Summary
A two-session, hands-on Tableau workshop that takes you from **connecting data** to **building interactive dashboards** with the Sample Superstore dataset. By the end, participants can confidently create core visuals, assemble dashboards with actions, and understand what’s covered on the **Tableau Desktop Specialist** exam.

---

## Goal
- Teach the **end-to-end Tableau workflow**: connect → prepare → analyze → share.
- Build an **interactive sales & profitability dashboard** (filters, parameters, actions).
- Prepare attendees for the **Desktop Specialist**-level skills (data connections, charts, table calcs, dashboards).

---

## Procedure
1. **Data & Setup**
   - Load *Sample – Superstore* (Excel).
   - Review data types, metadata, and basic cleaning (rename, split, pivot, joins/unions).

2. **Core Visuals**
   - Bar/line/scatter, maps with geographic roles, combined & dual-axis charts.
   - Sorting, grouping, sets, bins; quick table calculations (running total, YoY, percent difference).

3. **Analytics Layer**
   - Reference lines, trend lines, LOD-style alternatives via table calcs for segment views.
   - Parameters for user-controlled metrics (e.g., profit vs. profit ratio).

4. **Dashboarding**
   - Build Sales Overview and Profitability Deep-Dive dashboards.
   - Add interactivity: filter, highlight, and URL actions; mobile layout basics.

5. **Packaging & Sharing**
   - Save as `.twbx`, export images/PDF, and publish (Public/Server/Cloud).

---

## Result
- **Packaged workbook (.twbx)** with:
  - Region/Segment performance dashboard
  - Product & Category profitability view
  - Map with state/city drill, action-driven navigation
- Clean, reusable **Superstore** data source with curated fields and number formats.

---

## Business Impact
- **Self-serve analytics:** Reduce ad-hoc reporting by enabling business users to answer routine questions.
- **Faster decisions:** Interactive dashboards shorten the time from question to insight.
- **Consistent metrics:** Shared data source and standardized calculations improve trust and alignment.

---

## Next Steps to Make It Better
1. **Data Ops**
   - Add data refresh pipeline (extracts/schedules) and a certified data source.
2. **Analytics Depth**
   - Introduce cohort/forecast sheets, parameterized scenarios, and level-of-detail (LOD) expressions.
3. **Design & UX**
   - Apply a design system (color/typography), add tooltips with mini-charts, and mobile-first layouts.
4. **Governance**
   - Document metric definitions, owners, and change logs; add row-level security if publishing to Server/Cloud.
5. **Certification Prep**
   - Practice Specialist-level tasks (joins/unions, calcs, filters, dashboard actions) and take timed mocks.

---

## Getting Started
```text
1) Install Tableau Desktop (or use Tableau Public if you don’t have a license)
2) Open the packaged workbook (.twbx) or connect to “Sample – Superstore.xls”
3) Explore the worksheets, then open the dashboards and interact with filters/actions
````

## Repository Structure (suggested)

```
.
├── workbooks/
│   └── tableau-workshop.twbx        # final packaged workbook
├── data/
│   └── Sample - Superstore.xls      # source dataset (if included)
├── docs/
│   └── workshop-slides.pdf          # optional slides/handout
└── README.md
```

## Acknowledgments

* Dataset: Tableau “Sample – Superstore”
* Tools: Tableau Desktop / Tableau Public
