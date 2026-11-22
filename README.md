# NHS A&E Performance Analysis

## Overview

This project analyses publicly available NHS England monthly A&E statistics to explore attendance volumes and four-hour performance across Type 1 A&E departments.

The analysis covers April 2025 to March 2026.

## Objectives

- Analyse monthly A&E attendance volumes.
- Calculate four-hour performance.
- Compare performance across providers.
- Identify trends and variations.
- Present findings through a Power BI dashboard.

## Dataset

Source: NHS England – A&E Attendances and Emergency Admissions 2025–26.

https://www.england.nhs.uk/statistics/statistical-work-areas/ae-waiting-times-and-activity/ae-attendances-and-emergency-admissions-2025-26/

Only publicly available aggregated statistics were used.
No identifiable patient data was used.

## Tools Used

- Python (Pandas, Matplotlib)
- SQL (SQLite)
- Power BI
- Jupyter Notebook
- GitHub

## Methodology

1. Downloaded the official NHS England monthly data.
2. Inspected and cleaned the dataset.
3. Performed data quality and validation checks.
4. Used SQL and Python to analyse attendance volumes and four-hour performance.
5. Compared monthly trends and provider performance.
6. Developed a Power BI dashboard to present findings.

## Key Findings

### Monthly Performance

- Four-hour performance varied throughout the reporting year.
- Performance increased from 59.79% in April 2025 to 62.70% in July 2025.
- It subsequently declined, reaching its lowest point of 57.04% in January 2026.
- Performance recovered in February and March, reaching 63.89% in March.
- March recorded the highest four-hour performance, while January recorded the lowest.

### Provider Comparison

- University Hospitals Birmingham NHS Foundation Trust had the highest annual attendance volume among the providers displayed.
- Royal Free London NHS Foundation Trust recorded the highest four-hour performance among the providers displayed, at 66.43%.
- Barts Health NHS Trust recorded the lowest performance among those displayed, at 55.95%.
- The difference between these two provider percentages was 10.48 percentage points.


## Dashboard

<img width="848" height="411" alt="image" src="https://github.com/user-attachments/assets/cf537eca-f509-44f6-a5e6-b5b753bb9330" />

## Limitations

- Analysis focuses on Type 1 A&E departments.
- Data is aggregated monthly.
- Provider comparisons are not adjusted for differences in patient mix or hospital capacity.
- Missing data may affect comparisons.
- One financial year is insufficient to establish long-term trends or causation.

## Recommendations

- Monitor attendance volumes alongside waiting-time performance.
- Investigate sustained provider-level variation.
- Improve consistency of reporting.
- Consider additional operational indicators for future analysis.

## Project Structure

- data/ – Source and processed datasets
- notebooks/ – Python analysis and SQL queries
- dashboard/ – Power BI report
- visuals/ – Dashboard screenshots
- reports/ – Data quality and analysis summaries
