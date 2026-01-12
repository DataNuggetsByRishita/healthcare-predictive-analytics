# healthcare-predictive-analytics
Predictive analytics project modelling nursing home quality ratings using staffing, safety, ownership, and facility data. Applied regression, decision trees, k-NN, clustering, and association rules to support data-driven healthcare quality improvement. Industry focus: Healthcare / Public Services.
# Healthcare Predictive Analytics – Nursing Home Quality

## Industry Focus
Healthcare / Public Services / Health Policy

## Project Overview
This project applies predictive analytics to understand and estimate quality ratings (1–5 stars) for nursing homes using operational, staffing, safety, ownership, and facility data. While overall star ratings are widely used, they often lack transparency around the factors that drive performance. This analysis aims to uncover those drivers and translate them into actionable insights for decision-makers.

The project focuses on interpretability, reproducibility, and real-world applicability rather than purely technical accuracy.

---

## Business Problem
Healthcare leaders and regulators need to identify which factors most strongly influence nursing home quality in order to:
- Improve patient care outcomes
- Reduce compliance risks and penalties
- Allocate resources more effectively
- Support underperforming facilities proactively

---

## Data & Features
The dataset includes over 9,600 nursing homes and covers four key domains:
- **Staffing:** RN, LPN, CNA, total nurse hours
- **Safety & Compliance:** complaints, fines, incidents
- **Ownership:** for-profit, non-profit, government
- **Facility Characteristics:** size, residents, occupancy rate

Derived metrics such as complaints per 100 beds, fines per bed, and occupancy rate were created to enable fair comparison across facilities.

---

## Analytical Techniques
- Data preparation and feature engineering
- Exploratory data analysis and correlation assessment
- Linear Regression (M5) with feature selection
- Decision Tree regression for rule-based interpretation
- k-Nearest Neighbours (k-NN) for peer benchmarking
- k-Means clustering for facility profiling
- Association rule mining (FP-Growth) to analyse ownership patterns
- 10-fold cross-validation for robust model evaluation

---

## Key Findings
- **RN staffing hours** are the strongest positive driver of higher quality ratings
- **Complaints per bed** and **fines per bed** are the strongest negative predictors
- **Larger facilities** tend to underperform compared to smaller, fuller homes
- **Non-profit and government-run facilities** outperform for-profit providers on average
- High-quality clusters consistently show more RN staffing and fewer complaints

---

## Model Performance (Summary)
- Linear Regression (M5): Best overall performance and interpretability
- Decision Tree: Lower accuracy but clear operational thresholds
- k-NN: Moderate accuracy with strong benchmarking value

All models consistently identified the same key drivers, reinforcing the reliability of findings.

---

## Practical Recommendations
- Prioritise investment in RN staffing hours per resident
- Act on complaints early through rapid-response monitoring
- Apply targeted quality programs for large facilities
- Increase oversight and accountability for for-profit providers
- Use peer benchmarking to share best practices across facilities

---

## Files in This Repository
- `Sharma_rishita_225125235_A2_MIS772.pdf` – Full analytical report and results
- `SHARMA_RISHITA_225125235_A2_MIS772.zip` – Supporting models and project files

---

## Outcomes
This project demonstrates the ability to design, evaluate, and interpret predictive analytics models, and to translate complex analytical results into clear, evidence-based recommendations for healthcare leaders and policymakers.

---

## Author
Rishita Sharma  
Master of Business Analytics  
Deakin University
