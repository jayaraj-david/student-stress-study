# Investigating Stress Factors and Coping Mechanisms for Students

A primary quantitative research study examining the relationship between stress factors, coping behaviours, and overall stress levels among students.

**Course:** Research Methodology and Multivariate Analysis (AMS506PR)  
**Institution:** Department of Applied Mathematical Science, Gujarat University  

---

## Overview

This study investigates two key questions:

1. **Which stress factors significantly predict overall student stress?** (Part I — Multiple Linear Regression)
2. **Does coping frequency meaningfully reduce student stress?** (Part II — Simple Linear Regression)

Data was collected via a primary Likert-scale survey (1–5) from **109 students** using judgmental sampling across age, gender, and education groups.

---

## Variables

| Variable | Type | Role |
|----------|------|------|
| Age | Quantitative | Demographic |
| Gender | Nominal | Demographic |
| Education Level | Nominal | Demographic |
| Overall Stress | Ordinal (1–5 Likert) | Dependent Variable |
| Academic Workload | Ordinal (1–5 Likert) | Independent Variable (X₁) |
| Peer Pressure | Ordinal (1–5 Likert) | Independent Variable (X₂) |
| Social Isolation | Ordinal (1–5 Likert) | Independent Variable (X₃) |
| Financial Issues | Ordinal (1–5 Likert) | Independent Variable (X₄) |
| Health Issues | Ordinal (1–5 Likert) | Independent Variable (X₅) |
| Family Expectations | Ordinal (1–5 Likert) | Independent Variable (X₆) |
| Lack of Support | Ordinal (1–5 Likert) | Independent Variable (X₇) |
| Coping Frequency | Ordinal (1–5 Likert) | Independent Variable |

---

## Sample Profile

| Variable | Category | Frequency | % |
|----------|----------|-----------|---|
| Gender | Female | 54 | 49.5% |
| | Male | 55 | 50.5% |
| Age | < 18 | 7 | 6.4% |
| | 18–21 | 64 | 58.7% |
| | 22–25 | 38 | 34.9% |
| Education | High School / Diploma | 8 | 7.3% |
| | Undergraduate | 71 | 65.1% |
| | Postgraduate | 30 | 27.5% |

---

## Part I — Stress Factors and Overall Stress

**Method:** Multiple Linear Regression (SPSS)  
**Dependent Variable:** Overall Stress  
**Independent Variables:** Academic Workload, Peer Pressure, Social Isolation, Financial Issues, Health Issues, Family Expectations, Lack of Support

### Model Performance

| R | R² | Adjusted R² | Std. Error |
|---|----|-------------|------------|
| 0.799 | **0.639** | 0.614 | 0.8073 |

The model explains **63.9% of the variance** in overall stress (F = 25.537, p < 0.001).

### Significant Predictors

| Factor | β (Standardized) | p-value | Significant? |
|--------|-----------------|---------|--------------|
| Academic Workload | 0.323 | < 0.001 | Yes |
| Financial Issues | 0.345 | < 0.001 | Yes |
| Peer Pressure | 0.160 | 0.039 | Yes |
| Family Expectations | 0.167 | 0.027 | Yes |
| Social Isolation | 0.033 | 0.683 | No |
| Health Issues | 0.087 | 0.223 | No |
| Lack of Support | 0.006 | 0.931 | No |

**Key Finding:** Academic workload and financial concerns are the strongest predictors of student stress, followed by peer pressure and family expectations.

---

## Part II — Coping Frequency and Overall Stress

**Method:** Simple Linear Regression (SPSS)  
**Dependent Variable:** Overall Stress  
**Independent Variable:** Coping Frequency

### Model Performance

| R | R² | Adjusted R² |
|---|----|-------------|
| 0.616 | 0.379 | 0.373 |

### Result

| Predictor | B (Unstandardized) | β (Standardized) | p-value |
|-----------|-------------------|-----------------|---------|
| Coping Frequency | –0.795 | **–0.616** | < 0.001 |

**Key Finding:** Higher coping frequency significantly reduces overall stress (β = –0.616, p < 0.001). Students who engage in coping strategies more frequently report meaningfully lower stress levels.

---

## Repository Structure

```
student-stress-study/
├── README.md
├── data/
│   └── project_dataset.csv       ← Raw survey responses (anonymised)
├── analysis/
│   └── output.pdf                ← SPSS output (regression tables, ANOVA)
└── report/
    └── presentation.pdf          ← Full research presentation
```

> **Note:** Analysis was conducted in SPSS. The output PDF contains all regression tables, ANOVA results, and coefficient tables.

---

## Tools & Methods

- **Statistical Software:** SPSS
- **Methods:** Multiple Linear Regression, Simple Linear Regression, Descriptive Analysis
- **Survey Design:** Likert scale (1–5), primary data collection
- **Sampling:** Judgmental sampling across age, gender, and education groups

---

## References

1. Akgün, S., & Ciarrochi, J. (2003). Learned Resourcefulness Moderates the Relationship Between Academic Stress and Academic Performance. *Educational Psychology, 23*, 287–294.
2. Aldwin, C., & Greenberger, E. (1987). Cultural differences in the predictors of depression. *American Journal of Community Psychology, 15*(6), 789–813.
3. Banks, J., & Smyth, E. (2015). 'Your whole life depends on it': Academic stress and high-stakes testing in Ireland. *Journal of Youth Studies, 18*(5), 598–616.
4. Ji, H., & Zhang, L. (2011). Research on college students' stresses and coping strategies. *Asian Social Science, 7*(10), 30.
5. Kai-Wen, C. (2009). A study of stress sources among college students in Taiwan. *Journal of Academic and Business Ethics, 2*, 1.
6. Robotham, D. (2008). Stress among higher education students: Towards a research agenda. *Higher Education, 56*(6), 735–746.
7. Sarros, J. C., & Densten, I. L. (1989). Undergraduate student stress and coping strategies. *Higher Education Research & Development, 8*(1), 47–57.

---

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt this material with appropriate credit.
