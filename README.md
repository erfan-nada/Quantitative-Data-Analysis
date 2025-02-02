# Quantitative Data Analysis

This project focuses on the analysis of a diabetes dataset to derive insights about various health indicators and their relationship to diabetes outcomes. The analysis includes statistical summaries, visualizations, interpretation of results, and a machine learning model.

---

## Authors

- **Erfan Nada**
- **Mohammed Ammar**

---

## Dataset Description

The dataset consists of features that are categorized into **discrete** and **continuous** variables:

### Discrete Variables

- **Pregnancies**
- **Outcome**

### Continuous Variables

- **Glucose**
- **Blood Pressure**
- **Skin Thickness**
- **Insulin**
- **BMI (Body Mass Index)**
- **Diabetes Pedigree Function**
- **Age**

---

## Data Cleaning

- Checked for null values and confirmed there were none.
- Filled missing values using the mean to ensure data consistency.

---

## Analysis and Visualizations

### 1. **Correlation Heatmap**

- **Description:** Represents relationships between dataset features using correlation coefficients.
- **Key Insights:**
  - Positive correlation between:
    - Glucose and Outcome: **0.47**
    - BMI and Outcome: **0.29**
    - Age and Outcome: **0.238**

### 2. **Scatter Plot: Blood Pressure vs. BMI**

- **Description:** Highlights variability in BMI across blood pressure levels.
- **Key Insight:** Data shows clusters rather than a linear trend.

### 3. **Histograms with KDE**

- **Pregnancies:** Right-skewed distribution with most individuals having 0–5 pregnancies.
- **Skin Thickness:** Concentrated around lower values, with a few high outliers.
- **Age:** Most individuals are between 20–40 years.

### 4. **Pie Chart: Diabetes Outcomes**

- **Description:** Distribution of diabetes (Outcome = 1) vs non-diabetes (Outcome = 0).
- **Key Insight:** Highlights prevalence of diabetes in the dataset.

### 5. **Boxplots**

- **Skin Thickness:** Highlights variability and outliers.
- **Diabetes Pedigree Function:** Indicates genetic predisposition.
- **Blood Pressure:** Shows individuals with hypertension as outliers.

---

## Statistical Summary

### Central Tendency

- **Mean Values:**

  - Glucose: **120.89**
  - BMI: **31.99**
  - Age: **33.24**

- **Median Values:**

  - Glucose: **117**
  - BMI: **32**
  - Age: **29**

- **Mode Values:**

  - Glucose: **99**
  - BMI: **30**
  - Age: **22**

### Variability

- **Standard Deviation:**

  - Insulin: **115.24**
  - BMI: **7.88**
  - Age: **11.76**

- **Variance:**

  - Glucose: **1022.25**
  - Insulin: **13281.18**

---

## Machine Learning Model

### **Logistic Regression**

- **Description:** Implemented logistic regression to predict diabetes outcomes.
- **Performance Metrics:**
  - Model Accuracy: **77%**
  - Data Split: 80:20 (Train,Test)
  - Precision, Recall, and F1-score analysis.
- **Key Insight:** Logistic regression provides an interpretable way to assess diabetes risk based on health indicators.

---

## Conclusions

The findings emphasize the significance of:

1. Monitoring key health indicators such as **glucose levels**, **BMI**, and **age** for assessing diabetes risk.
2. Identifying outliers and extreme cases for targeted interventions.
3. Informing public health initiatives aimed at reducing diabetes prevalence and improving health outcomes.
4. Utilizing **machine learning models** like logistic regression to improve predictive capabilities for diabetes diagnosis.

---

## Tools Used

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Statistical Analysis and Data Visualization
- Machine Learning (Logistic Regression)

---

### Acknowledgments

- October University for Modern Sciences & Arts

