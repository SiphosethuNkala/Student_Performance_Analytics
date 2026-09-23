# Student Performance Analytics

A business intelligence and data analysis portfolio project by **Siphosethu Nomthandazo Nkala**, analysing student academic performance, attendance, and pass/fail outcomes, and presenting the findings in an interactive Excel dashboard.

## Overview

This project analyses a dataset of 15 students across Grades 10-12 and three subjects (Mathematics, Science, History), tracking Term 1 and Term 2 scores, attendance rates, and pass/fail outcomes. The goal was to identify performance patterns - by subject, by grade, and by individual student trend - that would help a school identify students needing support.

## What's in this project

| File | Description |
| `Student_Performance_Dashboard.xlsx` | Interactive dashboard — KPI cards, pass-rate-by-subject and average-score-by-grade tables, a Term 1→Term 2 change tracker, an attendance risk list, and charts. Built entirely on live formulas, so it recalculates automatically if the source data changes. |
| `students.csv` | Cleaned source data (15 students, 8 fields each). |

## Key findings

- **Overall pass rate: 80%** (12 of 15 students), with **History at 100%** and **Science the lowest at 67%**.
- **Grade 11 has the highest average Term 2 score (75.4)**, while Grade 12 is lowest (66.8).
- The three failing students (Lucas Sithole, Mason van Wyk, Minenhle Khumalo) all sit in Mathematics or Science, and two of the three also appear on the attendance risk list (below 90% attendance) - suggesting attendance and subject performance are worth investigating together, not separately.
- **Minenhle Khumalo improved the most between terms** (+13 points), despite still failing overall - a case where the trend line matters as much as the raw score for identifying who's turning a corner.

## Skills demonstrated

- **Data Analysis:** grouping, aggregation, trend calculation (Term 1 vs Term 2 change), conditional filtering (attendance risk)
- **Business Intelligence / Excel:** live-formula KPI dashboards, COUNTIFS/AVERAGEIF-based summary tables, chart selection
- **Data Cleaning:** extracting and structuring raw records into an analysis-ready format

## How to explore it

Open `Student_Performance_Dashboard.xlsx` in Excel and go to the **Dashboard** tab - all figures are live formulas referencing the **Data_Students** tab, so you can edit the underlying data and watch the dashboard update.

## Author

Siphosethu Nomthandazo Nkala
[LinkedIn](https://www.linkedin.com/in/siphosethu-nomthandazo-nkala-289893379) · siphonkala2001@gmail.com
