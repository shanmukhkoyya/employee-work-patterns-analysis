# Employee Work Patterns — Power BI Dashboard Portfolio

> **Reading note:** This is an exploratory analysis of 200 sample activity records. The custom index in this project is a learning metric, not a validated HR or employee-performance measure. It must not be used to assess or rank real people.

## Dashboard gallery

This repository contains four report images and the editable Power BI file.

| View | Screenshot |
|---|---|
| Main dashboard | ![Dashboard 1](screenshots/Dashboard1.png) |
| Employee detail view | ![Dashboard 2](screenshots/Dashboard2.png) |
| Index breakdown | ![Dashboard 3](screenshots/Dashboard3.png) |
| Analytical insights | ![Dashboard 4](screenshots/Dashboard4.png) |

**Main artifacts:** [Power BI report](laziness_data.pbix) · [CSV dataset](Laziness_Analysis_200_Records.csv)

## What is explored

The sample contains department and work-mode fields, login and active hours, idle time, break duration, task assignment and completion, missed-deadline status, meeting hours, social-media usage, performance rating, and the project-defined index.

Questions explored include:
- How do the sample index averages differ by department?
- How similar are the Office and Work From Home group averages?
- What patterns appear in task completion and missed deadlines?
- How do idle time, breaks and meeting hours vary in the supplied records?

## Snapshot of the documented results

| Measure | Result |
|---|---:|
| Activity records | 200 |
| Average project-defined index | 0.391 |
| Records with index ≥ 0.40 | 86 |
| Sales department average | 0.406 |
| Finance department average | 0.376 |
| Office average | 0.392 |
| Work From Home average | 0.390 |

The Office and Work From Home averages are very close in this sample. The comparison is descriptive and does not show that work mode causes a difference in performance.

A further documented comparison reports average social-media usage of 3.34 hours among records marked with a missed deadline and 3.52 hours among records not marked with a missed deadline. This does not establish a cause-and-effect relationship.

## What the report is intended to demonstrate

- KPI cards and department comparisons
- Work-mode and category breakdowns
- Login hours compared with completed tasks
- Employee-level detail and filters
- A Decomposition Tree for the custom index
- A What-If parameter for a hypothetical break-time change

## Reopen the analysis

1. Inspect the [sample CSV](Laziness_Analysis_200_Records.csv).
2. Open [laziness_data.pbix](laziness_data.pbix) in Power BI Desktop.
3. Review each report page and interact with its slicers and filters.
4. Check the definition and calculation of the custom index before interpreting it.

## Important limitations

- The 200 records are a sample dataset, not an established company-wide workforce study.
- The index and category thresholds are project-defined.
- The index is not a scientifically validated organisational or HR standard.
- Group differences are descriptive and do not establish cause and effect.
- No conclusion about an individual employee should be drawn from this exercise.

---

**Project author:** Shanmukh Koyya · [GitHub](https://github.com/shanmukhkoyya) · [LinkedIn](https://www.linkedin.com/in/shanmukh-koyya/) · [Email](mailto:shanmukhkoyya1234@gmail.com)
