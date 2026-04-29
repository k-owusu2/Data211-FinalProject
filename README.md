# Sleep Tracking Analysis — DATA 211 Course Project

**Kofi Owusu | Metropolitan State University | Spring 2026**

## Overview
A personal data science project tracking nightly sleep hours over 21 consecutive days (April 5 – April 25, 2026). Data was collected, cleaned, visualized, and statistically analyzed to determine whether my average sleep significantly differs from the recommended 8 hours.

## Research Question
Is my average nightly sleep significantly different from the recommended 8 hours?

## Hypotheses
- **H₀:** My average nightly sleep equals 8 hours (μ = 8)
- **H₁:** My average nightly sleep does not equal 8 hours (μ ≠ 8)

## Key Results
| Statistic | Value |
|---|---|
| Mean Sleep | 6.88 hours |
| Median Sleep | 7.0 hours |
| Std Deviation | 1.77 hours |
| Min | 3.5 hours |
| Max | 10.5 hours |
| t-statistic | -2.902 |
| p-value | 0.0088 |
| 95% CI | [6.08, 7.69] |
| Decision | Reject H₀ |

There is statistically significant evidence (p = 0.0088 < 0.05) that my average nightly sleep of 6.88 hours is significantly less than the recommended 8 hours.

## Repository Contents
```
├── sleep_data.xlsx               # Raw dataset (day, sleep_hours)
├── Data211FinalProject_Owusu_Kofi.Rmd   # RMarkdown analysis file
├── Data211FinalProject_Owusu_Kofi.pdf   # Knitted PDF output
├── presentation/                 # Final presentation slides
└── README.md
```

## Tools Used
- **R / RMarkdown** — statistical analysis and visualization
- **ggplot2** — line graph, box plot, scatter plot
- **readxl** — importing Excel dataset
- **Statistical test** — one-sample t-test

## How to Run
1. Clone the repository
2. Open `Data211FinalProject_Owusu_Kofi.Rmd` in RStudio
3. Make sure `sleep_data.xlsx` is in the same folder
4. Click **Knit to PDF**
