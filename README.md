# Income, Poverty, and Diabetes Mortality

**An Applied Data Analysis Demonstration Using County-Level Data**

This repository contains a reproducible applied data analysis examining the relationship between income, poverty, and diabetes-related mortality across U.S. counties.

The project is designed as a **portfolio-quality demonstration** of data cleaning, exploratory analysis, and regression modeling in R, with an emphasis on clear communication, reproducibility, and policy-relevant interpretation.

---

## Motivation

This project was developed to showcase applied analytical skills relevant to **data analysis, public policy, and health economics**. Understanding how socioeconomic conditions relate to health outcomes is central to policy evaluation and resource allocation.

The analysis emphasizes:
- Structured data cleaning and preparation
- Exploratory data analysis (EDA)
- Regression-based association analysis
- Clear interpretation of statistical results
- Reproducible analytical workflows

This project is not intended as a definitive causal study, but rather as an example of **how to translate data into policy-relevant insight**.

---

## Overview

The analysis explores how county-level income and poverty measures relate to diabetes mortality rates using a cross-sectional dataset.

Key components include:
- Data cleaning and variable construction
- Visualization of income–health relationships
- Regression models linking income and poverty to mortality outcomes
- Discussion of limitations and interpretation

---

## Live Report

A rendered version of the analysis is available here:

👉 https://treader-analytics.github.io/income-diabetes-mortality/

The live report contains all figures, tables, and model results generated directly from the analysis pipeline.

---

## Data

The dataset used in this project is **synthetic and anonymized**, created for demonstration purposes. It reflects realistic distributions of county-level income, poverty rates, and diabetes mortality, but does **not** represent actual individual-level health records.

Dataset location:
```
data/health_income_county.csv
```

Variables include:
- Median household income
- Poverty rate
- Diabetes mortality rate

---

## Methods

The analysis proceeds in four stages:
1. Data loading and cleaning
2. Exploratory visualization
3. Regression modeling
4. Interpretation of results

Standard linear regression models are used to estimate associations between socioeconomic variables and diabetes mortality rates.

Results are interpreted as **associational**, not causal.

---

## Repository Structure

```
├── data/
│   └── health_income_county.csv
├── reports/
│   └── income_diabetes_mortality.Rmd
├── figs/
│   └── preview.png
├── docs/
│   └── index.html
├── README.md
└── .gitignore
```

---

## Reproducibility

To reproduce the analysis locally:

```r
rmarkdown::render("reports/income_diabetes_mortality.Rmd")
```

All figures and results in the live report are generated directly from the analysis code.

---

## Tools & Packages

Key R packages used include:
- `dplyr`, `readr`, `tibble` — data manipulation
- `ggplot2` — visualization
- `rmarkdown` — reproducible reporting

---

## Author

**Trevor Reader**  
B.A. Mathematics & Statistics  
Applied Data Analysis • Policy Analysis • Health & Economic Systems

---

## Notes

This project is intended as a professional portfolio example demonstrating analytical reasoning, data storytelling, and reproducible workflows. It is designed to complement other applied econometrics and policy-focused projects in this portfolio.
