# UK Charity Organisation Clustering Analysis

## Project Overview

This project applies unsupervised machine learning techniques to analyse and segment over 300 UK charity organisations based on their operational characteristics, thematic focus, beneficiary groups, and governance-related indicators.

The objective of this project is to identify organisational patterns and hidden structural relationships within the charity sector using clustering analysis, dimensionality reduction, and data visualisation techniques.

---

## Objectives

* Perform exploratory data analysis (EDA) on organisational datasets
* Preprocess and transform structured categorical data
* Apply dimensionality reduction techniques to high-dimensional features
* Identify organisational clusters using K-Means clustering
* Generate actionable insights through visualisation and pattern analysis

---

## Technologies & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* UMAP-learn
* Matplotlib

---

## Methodology

### 1. Data Cleaning & Preprocessing

* Loaded and cleaned organisational data from Excel datasets
* Converted string-formatted categorical sets into Python lists
* Applied MultiLabelBinarizer for multi-category variables
* Applied One-Hot Encoding for geographic categories
* Performed missing value imputation using median values
* Applied log transformation and feature standardisation

### 2. Feature Engineering

Key features included:

* Organisational age
* Latest income
* Operating margin
* Reporting noncompliance
* Thematic categories
* Beneficiary groups
* Organisational role types

### 3. Dimensionality Reduction

To reduce noise and improve clustering quality:

* PCA was used to retain 85% explained variance
* UMAP was applied to project high-dimensional features into a 2D embedding space

### 4. Clustering Analysis

K-Means clustering was performed on UMAP embeddings.

Different K values were compared using the elbow method and cluster visualisation techniques to identify meaningful organisational segments.

---

## Key Outcomes

* Identified distinct organisational patterns and governance-related risk profiles
* Generated stakeholder-oriented insights through clustering visualisation
* Improved understanding of operational similarities between UK charities
* Demonstrated practical applications of machine learning in organisational analysis

---

## Repository Structure

```bash
├── charity_clustering_analysis.ipynb
├── processed_step_1.csv
├── README.md
└── figures/
```

---

## Notes

The original dataset is not included in this repository due to data privacy considerations.

---

## Author

Youyang Qu
MSc Data Science (Business and Management)
The University of Manchester
