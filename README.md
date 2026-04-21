# Exploratory Data Analysis (EDA) Project

## Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset to understand its structure, detect patterns, identify relationships, and prepare the data for future prediction models.

---

## Objective

* Analyze the dataset using statistical and visualization techniques
* Handle missing and duplicate values
* Identify correlations between features
* Detect outliers and data distributions
* Create meaningful features for future prediction

---

## Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Viewed initial rows and structure

### 2. Data Understanding

* Checked dataset shape, columns, and data types
* Generated statistical summary using `.describe()`

### 3. Data Cleaning

* Handled missing values using appropriate methods
* Removed duplicate records

### 4. Univariate Analysis

* Analyzed individual features
* Used histograms and bar plots

### 5. Bivariate Analysis

* Explored relationships between variables
* Used scatter plots and correlation heatmaps

### 6. Correlation Analysis

* Used heatmap to visualize feature relationships
* Identified strong positive and negative correlations

### 7. Outlier Detection

* Detected outliers using boxplots
* Analyzed their impact on the dataset

### 8. Feature Engineering

* Created new features such as:

  * Time-based features
  * Ratio features
  * Categorical bins
  * Lag features

---

## Key Visualization

### Correlation Heatmap

Used to understand relationships between numerical variables.

```python
plt.figure(figsize=(12, 8))
sns.heatmap(df.corr(numeric_only=True), annot=True, cmap='coolwarm', fmt=".2f", linewidths=0.5)
plt.title("Correlation Heatmap")
plt.show()
```

---

## Key Insights

* Strong correlations observed between some numerical features
* Certain features showed skewed distributions
* Outliers detected in multiple columns
* Feature engineering improved data understanding

---

## Future Scope

* Build machine learning models for prediction
* Perform feature selection for better accuracy
* Apply advanced techniques like scaling and encoding
* Deploy model using a web application

---

## Conclusion

EDA helps in understanding the dataset and plays a crucial role in building accurate and efficient machine learning models.

---

## Author

**Tejaswin S Srikar**
