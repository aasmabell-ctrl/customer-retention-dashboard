# Customer Retention & Engagement Dashboard

## Project Overview
An AI-assisted interactive dashboard developed during the Exactimo SQL and Visualisation Bootcamp to analyse user engagement, monthly activity and customer retention across joining cohorts.

## Business Objectives
- Monitor monthly active users and visit frequency.
- Compare customer retention across joining cohorts.
- Identify engagement patterns and opportunities to improve retention.

## Tools & Skills
**Tools:** Lovable AI, HTML, JavaScript, CSV data analysis

**Skills:** Cohort analysis, KPI reporting, data visualisation, data validation, business insight generation and AI-assisted development.

## Dashboard Features
- Total users and monthly active users with month-on-month comparisons.
- Week-4 retention and cohort-to-cohort comparisons.
- Visits per active user.
- Monthly activity line chart and retention curves for weeks 1–12.
- Interactive date filters, hover highlighting and data-integrity checks.

## Key Findings
1. **Monthly active users:** Declined from 392 in October to 385 in November 2026 (−1.8%).
2. **Visit frequency:** Increased from 3.99 to 4.22 visits per active user over the same period.
3. **Week-4 retention:** Fell from 38.0% for the August 2026 cohort to 31.1% for the September 2026 cohort (−6.9 percentage points).

## Business Recommendation
Investigate early customer disengagement by comparing user behaviour across joining cohorts. Consider testing onboarding improvements or targeted re-engagement initiatives, then monitor subsequent retention rates to assess their impact. The data identifies patterns but does not establish their causes.

## Validation Approach
The dashboard was evaluated by checking cohort totals against distinct user counts, confirming Week-0 retention for completed cohorts, verifying that incomplete periods remain blank, and testing how metrics respond when November 2026 records are removed. Headline figures were independently recalculated from the source CSV.

## Limitations
The dataset contains visit and joining dates, but no customer demographics, marketing exposure or reasons for disengagement. It is Exactimo training data rather than live company performance. Because the dataset includes dates through November 2026, findings should be interpreted as training-scenario results rather than observed real-world activity as of November 11, 2026.

## Development & Acknowledgements
Created as part of the Exactimo SQL and Visualisation Bootcamp. Lovable AI generated the initial dashboard implementation. My contribution included testing the controls, reviewing calculation logic, requesting and reviewing validation checks, interpreting results and developing business recommendations. Course exercise and training data credited to Exactimo.
