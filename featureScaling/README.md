# Feature Scaling in Machine Learning

## Overview

This project demonstrates two important feature scaling techniques used in machine learning:

1. Standardization (Z-Score Scaling)
2. Min-Max Normalization

The goal is to transform numerical features into a common scale, improving the performance of machine learning algorithms.

---

## Datasets Used

### Mall Customer Dataset
Used for Standardization.

Features:
- Age
- Annual Income (k$)
- Spending Score (1-100)

### Wine Quality Dataset
Used for Min-Max Normalization.

Features:
- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

---

## Techniques Applied

### Standardization

Formula:

Z = (X - μ) / σ

Results:
- Mean ≈ 0
- Standard Deviation ≈ 1

### Min-Max Normalization

Formula:

X_normalized = (X - X_min) / (X_max - X_min)

Results:
- Minimum Value = 0
- Maximum Value = 1

---

## Visualizations

- Histograms
- KDE Plots
- Boxplots
- Statistical Comparisons

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Learning Outcomes

- Understanding Feature Scaling
- Applying StandardScaler
- Applying MinMaxScaler
- Comparing scaled and unscaled data
- Data preprocessing for Machine Learning

---

## Author

Raksha C C
