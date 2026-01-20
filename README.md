# Insurance Analysis and Prediction (Python Project Starter)

This project analyzes a medical insurance dataset using basic Python techniques such as lists, dictionaries, loops, functions, and classes. It explores relationships between demographic variables and insurance charges and implements a rule-based prediction model.

---

## Dataset Variables

- age: Age of insured individual
- sex: Gender
- bmi: Body Mass Index
- children: Number of dependents
- smoker: Smoking status (yes/no)
- region: Residential region
- charges: Insurance cost

---

## Project Features

### Data Analysis
- Record count
- Average BMI and charges
- Smoker vs non-smoker counts
- Regional average charge comparison
- Most expensive region detection

### Correlation Analysis
Pearson correlation is calculated between:
- Age and charges
- BMI and charges
- Children and charges
- Smoking status and charges

### Prediction Model
A rule-based prediction model is implemented using:
- Smoker status as baseline
- Age and BMI as adjustment factors
- Object-oriented design using a class

### Model Evaluation
Prediction performance is evaluated using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² score

---

## Model Design

The prediction model is not a machine learning implementation. It uses:

- Baseline insurance cost based on smoking status
- Proportional adjustments based on age and BMI deviation from averages

This approach mimics regression behavior using basic Python logic.

---

## Files

- insurance.csv — dataset
- us-medical-insurance-costs.ipynb — analysis and prediction code
- README.md — project documentation

---
