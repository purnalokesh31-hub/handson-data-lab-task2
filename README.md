# Hands-On Data Lab Implementation

This repository contains the code, exploratory data analysis (EDA), and visual outputs for **Task 2: Hands-On Data Lab Implementation**, completed as part of the **Machine Learning Engineer Internship**.

## Project Overview
The goal of this task is to set up a cloud-based data science workspace, load a benchmark dataset, perform data cleaning and exploratory analysis, generate key summary statistics, and export statistical visualizations.

## Environment & Libraries Used
- **Platform:** Google Colab (Python 3)
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `seaborn`, `matplotlib`
- **Dataset Ingestion:** `scikit-learn`

## Dataset Description
The analysis utilizes the classic **Iris Dataset** imported via `sklearn.datasets`.
- **Sample Count:** 150 instances
- **Classes:** `setosa`, `versicolor`, `virginica`
- **Features:** 
  - `sepal_length` (cm)
  - `sepal_width` (cm)
  - `petal_length` (cm)
  - `petal_width` (cm)

## Exploratory Data Analysis & Key Findings
1. **Feature Distributions:** Analysis of `petal_length` shows clear separation between species. *Setosa* features significantly shorter petal lengths (< 2.0 cm) compared to *Versicolor* and *Virginica*.
2. **Linear Correlations:** A strong positive relationship exists between `petal_length` and `petal_width` across all three species groups ($r = 0.96$).
3. **Data Integrity:** Verification confirmed zero missing or null entries across all 150 rows.

## Repository Structure
```text
├── task2.ipynb             # Jupyter Notebook containing execution code
├── petal_distribution.png  # Histogram plot of petal lengths by species
├── petal_scatter.png       # Scatter plot of petal length vs. petal width
├── correlation_heatmap.png # Correlation matrix heatmap of numerical features
└── README.md               # Project documentation
