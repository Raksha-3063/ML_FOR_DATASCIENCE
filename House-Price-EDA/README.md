# House Price EDA

## Overview

This project performs Exploratory Data Analysis (EDA) on a House Price dataset to identify the key factors influencing property prices.

The analysis includes:

* Data Cleaning
* Outlier Detection
* Bivariate Analysis
* Multivariate Analysis
* Correlation Analysis
* Data Visualization using Seaborn and Matplotlib

---

## Dataset Features

The dataset contains information such as:

* Square Foot Area (SQUARE_FT)
* Number of Bedrooms (BHK_NO.)
* Property Location
* Property Price (TARGET(PRICE_IN_LACS))
* Other housing attributes

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Analysis Performed

### Bivariate Analysis

* Area vs Price
* BHK vs Price
* Distribution of property prices

### Multivariate Analysis

* Area vs Price by BHK
* Relationship among multiple housing features

### Correlation Analysis

* Correlation Heatmap
* Identification of important features affecting house prices

---

## Key Insights

* Property prices generally increase with area.
* Higher BHK properties tend to have higher prices.
* Extreme outliers were identified and handled.
* Area and BHK together show a strong relationship with property prices.

---

## Project Structure

```text
House-Price-EDA/
│
├── Analysis.ipynb
├── train.csv
├── test.csv
├── sample_submission.csv
└── README.md
```

---

## Author

Raksha C C

B.Tech Computer Science Engineering

Aspiring Data Scientist
