# Practical Statistics for Data Scientists — Code Reproduction and Notes

This repository was created as a structured code reproduction and conceptual explanation project based on **Practical Statistics for Data Scientists, Second Edition: 50+ Essential Concepts Using R and Python** by **Peter Bruce, Andrew Bruce, and Peter Gedeck**.

> The book cover is not embedded. A legal/official image can be added manually if required.

---

## Project Description

The repository contains executed Jupyter notebooks for the seven main chapters of the book. The notebooks are written in English and focus on practical statistical concepts for data science using Python.

Each notebook includes:

- learning objectives,
- theoretical explanation,
- original/adapted code reproduction,
- output interpretation,
- extended study notes,
- chapter summary,
- key takeaways.

All examples use synthetic or built-in datasets so the notebooks can be run without external downloads.

---

## Book Information

- **Title:** Practical Statistics for Data Scientists
- **Edition:** Second Edition
- **Authors:** Peter Bruce, Andrew Bruce, Peter Gedeck
- **Publisher:** O'Reilly Media
- **Main Topics:** exploratory data analysis, sampling, statistical testing, regression, classification, machine learning, and unsupervised learning.

---

## Repository Structure

```text
.
├── README.md
├── requirements.txt
└── notebooks/
    ├── Chapter_01_Exploratory_Data_Analysis.ipynb
    ├── Chapter_02_Data_and_Sampling_Distributions.ipynb
    ├── Chapter_03_Statistical_Experiments_and_Significance_Testing.ipynb
    ├── Chapter_04_Regression_and_Prediction.ipynb
    ├── Chapter_05_Classification.ipynb
    ├── Chapter_06_Statistical_Machine_Learning.ipynb
    └── Chapter_07_Unsupervised_Learning.ipynb
```

---

## Chapter Overview

### Chapter 1 — Exploratory Data Analysis
Covers data types, structured data, location and variability estimates, robust statistics, distributions, categorical data, correlation, and multivariate visualization.

### Chapter 2 — Data and Sampling Distributions
Covers random sampling, sample bias, sampling distributions, central limit theorem, bootstrap, confidence intervals, and common probability distributions.

### Chapter 3 — Statistical Experiments and Significance Testing
Covers A/B testing, hypothesis tests, permutation tests, p-values, t-tests, multiple testing, ANOVA, chi-square tests, bandits, power, and sample size.

### Chapter 4 — Regression and Prediction
Covers linear regression, least squares, residuals, multiple regression, cross-validation, model selection, factor variables, diagnostics, and nonlinear extensions.

### Chapter 5 — Classification
Covers Naive Bayes, logistic regression, confusion matrices, precision, recall, specificity, ROC curves, AUC, lift, imbalanced data, and cost-based classification.

### Chapter 6 — Statistical Machine Learning
Covers KNN, tree models, bagging, random forest, variable importance, boosting, XGBoost concepts, regularization, hyperparameters, and cross-validation.

### Chapter 7 — Unsupervised Learning
Covers PCA, K-means, hierarchical clustering, model-based clustering, scaling, categorical variables, and clustering interpretation.

---

## Installation

```bash
python -m venv venv
```

Windows:

```bash
.\venv\Scripts\activate
```

macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## How to Run

```bash
jupyter notebook
```

Open the `notebooks/` folder and select the chapter notebook you want to review. The submitted notebooks have already been executed, so outputs and plots are visible directly in the `.ipynb` files.

---

## Dependencies

```text
numpy
pandas
matplotlib
scipy
scikit-learn
jupyter
nbformat
nbclient
```

---

## Academic Integrity

This repository is prepared as an academic learning project. The explanations are written in original wording, and the code examples are adapted into original runnable demonstrations. The purpose is to support understanding and practical learning, not to replace the original book.

---

## Completion Status

- [x] Chapter 1 — Exploratory Data Analysis
- [x] Chapter 2 — Data and Sampling Distributions
- [x] Chapter 3 — Statistical Experiments and Significance Testing
- [x] Chapter 4 — Regression and Prediction
- [x] Chapter 5 — Classification
- [x] Chapter 6 — Statistical Machine Learning
- [x] Chapter 7 — Unsupervised Learning
- [x] All notebooks executed
- [x] README created
- [x] requirements.txt created
