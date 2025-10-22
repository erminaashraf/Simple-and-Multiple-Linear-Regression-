# Simple-and-Multiple-Linear-Regression-
Does studying more improve exam results? Do these results differ across groups? We run a simple linear regression of Exam Score on Hours Studied for each group.

# Student Performance Analysis

This project analyzes the **Student Performance Factors** dataset to explore how academic effort and support systems influence student outcomes.  
Using Python, I ran a **simple linear regression** to evaluate the relationship between study time and final exam scores, while checking the validity of OLS model assumptions.

## Dataset
The dataset includes information on students’ **exam scores** and various **academic, behavioral, and socio-economic factors**.

- **Dependent variable:**  
  - `Exam_Score` – Final exam score (0–100)

- **Key independent variables:**  
  - `Hours_Studied`, `Attendance`, `Sleep_Hours`, `Previous_Scores`, `Tutoring_Sessions`

- **Background (categorical) variables:**  
  - `Parental_Education_Level`, `Family_Income`, `Access_to_Resources`, `Parental_Involvement`,  
    `Teacher_Quality`, `Motivation_Level`, `School_Type`, `Peer_Influence`, `Internet_Access`,  
    `Extracurricular_Activities`

## Research Questions
1. Does studying more improve exam results?  
2. Does the effect of studying differ between **High Support** and **Low Support** students?  
3. Do the regression assumptions hold?

## Methodology
- **Data cleaning** and filtering  
- **Simple linear regression** of `Exam_Score` on `Hours_Studied`  
- Grouped regressions for High vs. Low Support students  
- **Diagnostic tests** for:
  - Linearity  
  - Independence of errors  
  - Homoskedasticity  
  - Normality of residuals  

## Learning Objectives
Through this project, I practiced:
- Data cleaning, filtering, and sampling
- Running and interpreting simple linear regressions
- Validating model assumptions using diagnostic plots and statistical tests
- Presenting insights in a structured, replicable notebook format

---

**Tools used:** Python, pandas, statsmodels, matplotlib, seaborn  
**Focus areas:** Education analytics, regression modeling, statistical diagnostics
