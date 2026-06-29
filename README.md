# Employee Satisfaction Analysis Using R

This project analyzes employee satisfaction and workplace dynamics using statistical techniques in R. The analysis examines factors that influence employee job satisfaction across 3,025 survey responses from a fictional company.

## Project Overview

This analysis explores relationships between various workplace factors and employee satisfaction using:
- **Chi-squared tests** for association between categorical variables
- **One-way and Two-way ANOVA** for comparing means across groups
- **Multiple Linear Regression** to model predictors of job satisfaction

## Dataset

The dataset uses a synthetically made employee survey available on [Kaggle](https://www.kaggle.com/datasets/lainguyn123/employee-survey/data).

**Sample size:** 3,025 employee responses

## Key Variables Analyzed

- **Demographics:** Gender, Age, Job Level, Experience, Department
- **Workplace Factors:** Work-Life Balance, Work Environment, Work Load, Stress
- **Well-being:** Sleep Hours, Training Hours Per Year
- **Outcome:** Job Satisfaction

## Required R Packages

Install the required packages before running the analysis:

```r
install.packages(c("readxl", "dplyr", "ggplot2", "corrplot", "knitr", "gridExtra"))
```

## How to Run

1. Clone this repository
2. Open R or RStudio
3. Install required packages (see above)
4. Open `Project_Alexandre_Saliba.Rmd` in RStudio
5. Ensure `employee_survey.xlsx` is in the same directory
6. Click "Knit" to generate the HTML report, or run chunks individually

## Key Findings

- **Stress and Job Satisfaction:** Strong statistical association found between stress levels and job satisfaction
- **Work Environment:** Significant predictor of job satisfaction in regression analysis
- **Demographics:** Age and experience show positive correlation with training hours received
- **Sleep Hours:** No significant differences found across gender groups
- **Work Load & Environment:** No significant interaction effect on stress levels

## Statistical Tests Performed

1. **Chi-Squared Tests:**
   - Job Level vs Stress
   - Stress vs Job Satisfaction

2. **ANOVA Tests:**
   - One-way ANOVA: Sleep Hours across Gender groups
   - Two-way ANOVA: Stress levels based on Work Load and Work Environment

3. **Multiple Linear Regression:**
   - Predictors of Job Satisfaction (Stress, Work-Life Balance, Work Environment, Training Hours, Gender)

## Project Structure

```
.
├── Project_Alexandre_Saliba.Rmd    # Main analysis file
├── employee_survey.xlsx            # Dataset
├── README.md                       # This file
└── .gitignore                      # Git ignore file
```

## Author

**Alexandre Saliba**

## License

This project is for educational and portfolio purposes.
