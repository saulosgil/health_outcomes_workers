# ♻️🩺 health_outcomes_workers

Repository with notebooks, figures, and supporting materials for the study comparing **anthropometric profile**, **cardiometabolic risk**, and **quality of life** between **cooperative** and **independent waste pickers**.

## 📖 About the project

This repository organizes the analytical workflow of a cross-sectional study conducted in Brazil with waste pickers (*catadores de materiais recicláveis*), comparing two groups:

- **Cooperative waste pickers**: those working within recycling cooperatives;
- **Independent waste pickers**: those collecting recyclable materials on the streets without cooperative affiliation.

## 🎯 Study objective

To compare cooperative and independent waste pickers regarding:

1. anthropometric measures (weight, BMI, waist circumference, and waist-to-height ratio);
2. prevalence of obesity and increased cardiometabolic risk;
3. quality of life (WHOQOL-BREF domains).

## 🧪 Study design

This is a **cross-sectional study** with semi-structured interviews and anthropometric assessments.

### Main measures assessed

- **Sociodemographic and occupational data**: age, sex, marital status, education, income, job tenure, and weekly working hours;
- **Lifestyle**: smoking status, alcohol consumption, and self-rated health;
- **Anthropometry**: weight, height, BMI, waist circumference, and waist-to-height ratio;
- **Clinical data**: blood pressure, handgrip strength, self-reported comorbidities (hypertension and type 2 diabetes), and medication use;
- **Cardiometabolic risk**: waist-to-height ratio ≥ 0.50;
- **Quality of life**: assessed using the **WHOQOL-BREF** (physical, psychological, social relationships, and environment domains; scores from 0 to 100).

## 📊 Statistical analysis

- Continuous variables were compared using **Welch's t-test**;
- Proportions were compared using **Boschloo's exact test**, with odds ratios and 95% CI;
- **Linear regression** models (crude and adjusted for sex and age) with heteroskedasticity-robust standard errors (HC3) were used to estimate the association between type of work and anthropometric outcomes;
- WHOQOL-BREF scores were computed following the WHOQOL Group syntax (reversal of items 3, 4, and 26; exclusion of respondents with more than 20% of missing items).

## 🤖 Technologies used

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat&logoColor=white)

## 📁 Repository structure

| File / folder | Description |
| --- | --- |
| `data/` | Analytical datasets. |
| `data_prep.ipynb` | Data cleaning and preparation (variable recoding, comorbidities, medication classes, cardiometabolic risk). |
| `whoqol.ipynb` | Computation of WHOQOL-BREF domain scores. |
| `analise_descritiva.ipynb` | Descriptive analysis and participant characteristics table. |
| `compare_groups.ipynb` | Group comparisons (Welch's t-test and Boschloo's exact test) and figures. |
| `linear_reg.ipynb` | Crude and adjusted linear regression models. |
| `figura_1/` | Figure 1: anthropometric profile and cardiometabolic risk by group. |
| `figura_2/` | Figure 2: WHOQOL-BREF domain scores by group (radar plot). |

## 🔁 Reproducibility

The analyses were performed in **Python** using Jupyter notebooks. To reproduce them, run the notebooks in the following order:

1. `data_prep.ipynb`
2. `whoqol.ipynb`
3. `analise_descritiva.ipynb`
4. `compare_groups.ipynb`
5. `linear_reg.ipynb`

## 🗂️ Purpose of this repository

This repository was created to:

- organize the analysis notebooks;
- document the study's analytical workflow;
- facilitate reproducibility of the analyses;
- centralize figures and materials linked to the manuscript.

## 📑 Reference

📝 Manuscript in preparation. The reference will be added after publication.

---

## 👨‍💻 Author

**Saulo Gil**
GitHub: [@saulosgil](https://github.com/saulosgil)
