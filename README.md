![Project Preview](preview.png)

# Income and Diabetes Mortality at the County Level

This project examines how income and health outcomes align across U.S. counties. The central question is:

**Do counties with lower median household income experience higher rates of diabetes mortality?**

The dataset used here is **synthetic**, but designed to resemble typical county-level socioeconomic and health indicators.  
The goal of the analysis is not to draw real-world conclusions, but to demonstrate a clean workflow for investigating policy-relevant relationships using R.

---

## Project Overview

The analysis focuses on five primary variables:

- Median household income  
- Diabetes mortality (deaths per 100,000 people)  
- Region  
- Urban vs. rural classification  
- Population size  

The workflow includes:

1. Data cleaning and preparation  
2. Exploratory data analysis  
3. Simple and multivariable regression modeling  
4. Policy-oriented interpretation  
5. Discussion of limitations and possible extensions  

---

## Key Findings

Because the dataset is synthetic, the results are not intended to reflect actual U.S. counties. In this example:

- Median income is not a strong predictor of diabetes mortality.  
- Urban/rural status and regional classification add little explanatory power.  
- Most variation in mortality remains unexplained by the available variables.  

This highlights a common issue in applied policy analysis: socioeconomic indicators alone may not fully explain health disparities without additional demographic, behavioral, and clinical data.

---

## Repository Structure

```
income_diabetes_mortality.Rmd   # Full analysis in R Markdown
health_income_county.csv        # Synthetic dataset used in the analysis
README.md                       # Project description
```

---

## Running the Analysis

1. Clone or download the repository.  
2. Open `income_diabetes_mortality.Rmd` in RStudio or another R-compatible editor.  
3. Ensure the CSV file is in the same directory as the Rmd file.  
4. Install required packages if needed:

```
install.packages(c("tidyverse", "janitor"))
```

5. Knit the file to HTML to reproduce all results and visualizations.

---

## Methods and Tools

- **Language:** R  
- **Libraries:** `tidyverse`, `janitor`  
- **Document format:** R Markdown  
- **Analytical focus:** exploratory data analysis, linear modeling, policy interpretation  

---

## Future Extensions

Potential enhancements include:

- Repeating the analysis with real county-level data (e.g., CDC WONDER, County Health Rankings)  
- Adding demographic variables such as age structure or insurance coverage  
- Exploring non-linear models or interaction effects  
- Incorporating spatial data and mapping  

---

## Author

Created by **Trevor Reader** as part of an applied analytics and public policy research portfolio.
