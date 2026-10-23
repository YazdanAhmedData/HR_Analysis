# 👥 HR Analytics Dashboard | Workforce Insights

<img width="100%" alt="HR analytics dashboard screenshot" src="https://github.com/user-attachments/assets/528f25b5-50e4-405b-8b70-86b31506d66e" />

**Portfolio case study · People analytics · Dashboard reporting**

## Executive Summary
This project explores employee/workforce information in a spreadsheet-based analysis and dashboard. It demonstrates how HR records can be organised into a clearer reporting view to support workforce monitoring and questions about employee composition, departments, roles and performance.

## Business Problem
HR teams often need to answer routine workforce questions quickly: how many people are in different groups, how is the workforce distributed, and which trends deserve investigation? A structured dashboard can make recurring reporting more consistent and help leaders identify where further analysis is needed.

This project is descriptive. It should support questions for HR teams, not make unsupported judgements about individual employees.

## Business Questions
- How is the workforce distributed across the available departments and roles?
- What employee demographic or performance patterns are visible in the dataset?
- Which departments or groups differ on the measures included in the workbook?
- What measures could be monitored consistently in a recurring HR report?
- What additional fields would be needed to investigate hiring, attrition or workforce planning?

## KPI Framework
Use only measures that are actually calculated in the workbook and label the population/time period clearly.

| KPI | Definition / calculation | Business use |
|---|---|---|
| Headcount | Distinct employee IDs or employee records, depending on data grain | Workforce size |
| Department mix | Department headcount ÷ total headcount | Workforce allocation |
| Role distribution | Headcount by job role | Role coverage and planning |
| Performance distribution | Employee count by available performance category | Review patterns and follow-up needs |
| Workforce trend | Headcount by period, where dates exist | Monitor change over time |
| Attrition rate *(if exit data exists)* | Exits in period ÷ defined average or opening headcount | Retention monitoring |

**Metric integrity:** the repository's current workbook should be treated as the source of truth for which fields and calculations are actually present. Do not infer attrition, diversity, or performance outcomes if the required data is absent.

## Insights & Decision Use
A recruiter-facing HR project should connect each chart to a decision:
- **Department/role distribution:** identify where workforce capacity is concentrated and where a deeper staffing review may be useful.
- **Performance breakdowns:** explore patterns at an aggregate level and check sample sizes before drawing conclusions.
- **Recurring reporting:** standardise KPI definitions and date filters so HR and business leaders compare like with like.
- **Data gaps:** note missing fields that prevent stronger conclusions, such as join dates, exit dates, role history or a consistent performance rubric.

These are analytical interpretations to validate against the displayed dashboard, not claims about a specific department or employee group.

## Tools & Project Files
| File | Purpose |
|---|---|
| `employee_data_google_sheets.xlsx` | Employee dataset used for analysis |
| `HR DASHBOARD.pdf` | Exported dashboard/report |
| `README.md` | Project documentation |

The project uses spreadsheet-based data preparation and dashboard reporting. Review the workbook and PDF to confirm the exact visualisation tool and calculated fields.

## How to Review
1. Open `employee_data_google_sheets.xlsx` and inspect column names, record grain and missing values.
2. Review `HR DASHBOARD.pdf` alongside the screenshot above.
3. Trace each KPI back to its source column and calculation.
4. Confirm filters and denominators before using a metric in a business recommendation.

## Data Quality, Ethics & Limitations
- Workforce records can contain sensitive personal information. Avoid publishing identifiable employee-level data.
- Small groups should not be ranked or compared without context.
- Descriptive patterns do not establish why an employee performed a certain way or why a department differs.
- Document date ranges, missingness and metric definitions.
- Do not claim hiring, attrition or diversity insights unless the necessary fields are available.

## Next Steps
- Add a concise data dictionary and metric definitions.
- Include verified headline findings and their implications from the dashboard.
- Add a repeatable refresh process and quality checks.
- If historical data is available, add time-based headcount/attrition analysis with a clearly defined denominator.

## Skills Demonstrated
Spreadsheet data handling · HR KPI framing · Dashboard interpretation · Business reporting · Analytical communication

## Author
**Yazdan Ahmed** · [GitHub Portfolio](https://github.com/YazdanAhmedData)
