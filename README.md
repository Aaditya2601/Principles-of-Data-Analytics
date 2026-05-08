# What Drives Success?
## Factors Influencing Employment and Salary Outcomes for International Graduates

## Overview
This project analyses how selected characteristics of international graduates relate to employment outcomes and salary levels. The focus is on language ability, education level, and internship experience, using statistical methods introduced in the *Principles of Data Analytics* course.

The analysis is split into two outcomes:
- Employment status (categorical)
- Salary (continuous, employed graduates only)

---

## Research Questions
1. How do language proficiency, education level, and internship experience relate to employment status?
2. How do the same factors relate to salary outcomes for employed graduates?

---

## Data
- **Source:** `cleaned_dataset.csv`
- **Sample size:** 300,000 international graduates
- **Coverage:** Demographics, education, employment status, and salary

### Variables
**Predictors**
- Language proficiency
- Education level
- Internship experience
- University ranking

**Outcomes**
- Employment status (Employed, Unemployed, Continuing Education)
- Annual salary (USD)

----

## Descriptive Summary
- Mean age: 30.5  
- Employed: 52%  
- Internship experience: 65%  
- Mean salary (employed graduates): \$58,094  

---

## Methodology

### Employment Status (Categorical)
- Chi-square tests of independence
- Effect size measured using Cramér’s V
- Interaction analysis between key predictors

### Salary (Continuous)
- One-way and two-way ANOVA
- Tukey’s HSD for post-hoc comparisons
- Conceptual multiple linear regression to assess combined effects
- Assumptions checked for variance homogeneity

---

## Results

### Employment Status
- All predictors and interactions were statistically significant (p < 0.001)
- Strongest individual associations:
  - Language proficiency (V = 0.281)
  - Education level (V = 0.277)
- Strongest interaction:
  - Language × Education (V = 0.400)

Graduates with higher education levels and stronger language proficiency show the highest employment rates.

---

### Salary
- Salary differs significantly across education levels and language proficiency groups
- Internship experience has a larger impact on salary for Bachelor’s graduates than for PhD holders
- Language-related salary differences widen at higher education levels

---

## Limitations
- Job sector data is missing for a large subset of observations
- Regression assumptions were not exhaustively tested
- Findings indicate association, not causation

---

## Future Work
- Multinomial logistic regression for employment outcomes
- Salary analysis by job sector
- Examination of gender-based salary differences

---

## References
See project documentation for full reference list.
