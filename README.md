# Inflation–Wage Growth–Age Cohorts (STAT 5205)
**Inflation's Uneven Hand: Quantifying Age-Cohort Differences in Nominal Wage Growth Response to CPI**

This project examines whether **nominal wage growth responds differently to CPI inflation across age cohorts** (16–24, 25–54, 55+). Using CPI inflation and wage growth data by age group, we estimate **OLS linear regression models with age-group interaction terms** to quantify heterogeneous inflation pass-through to wages.

---

## 1. Project Overview
- **Question**: Do different age cohorts experience different wage growth responses when inflation changes?
- **Inputs**: CPI inflation + nominal wage growth by age cohort
- **Method**: Linear regression (OLS) with cohort indicators and CPI interaction terms
- **Outputs**: Estimated CPI sensitivity by cohort, model diagnostics, and interpretation in the final report

---

## 2. Data
This repository includes two input datasets in the **repo root**:

- `age.csv` — nominal wage growth series by age cohort (e.g., 16–24, 25–54, 55+)
- `cpi.csv` — CPI inflation series

> Tip (Windows/Excel): export as **CSV UTF-8** to avoid encoding issues.

---

## 3. Method (Core Specification)
We model nominal wage growth as a function of CPI inflation and allow the CPI effect to vary by age group using interaction terms.

Conceptually:
- Baseline wage growth differs by cohort
- CPI-to-wage sensitivity differs by cohort (CPI × cohort)

See `Final_Report.pdf` for the full model equation, regression tables, diagnostics, and robustness checks.
