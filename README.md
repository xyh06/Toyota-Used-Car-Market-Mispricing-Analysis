# Toyota Used Car Price Analysis (Machine Learning)

## Project Background

This project investigates the pricing mechanism of used Toyota vehicles using machine learning models.
Instead of predicting price only, the goal is to understand **what determines used car value**.

Dataset: 6738 UK used Toyota vehicles (2013–2020)

---

## Objectives

* Identify key factors affecting price
* Build a market benchmark price model
* Evaluate relative value retention across models

---

## Methodology

1. Data Cleaning (IQR outlier handling)
2. Feature Engineering (age, mileage, engine specs)
3. Random Forest Regression (R² ≈ 0.86 on test set)
4. Price Index = Actual Price / Predicted Price

---

## Key Findings

* Price mainly driven by depreciation (age & mileage)
* Engine parameters provide stable premium
* Model preference affects relative valuation

Used car market follows:

**Depreciation First → Preference Second**

---

## How to Run

```bash
pip install -r requirements.txt
python run.py
```

---

## Author

Undergraduate Data Science Student
Focus: Data Analysis / Applied Statistics
