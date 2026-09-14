# Student Performance Detailed Analysis

A data science and machine learning project analyzing a synthetic dataset of 1,000 students to identify key performance drivers, conduct inferential statistical tests, and implement supervised and unsupervised models.

## Built With

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-0C55A5?style=for-the-badge&logo=scipy&logoColor=white)
![Statsmodels](https://img.shields.io/badge/Statsmodels-00599C?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## Dataset Overview

The dataset contains background demographics and performance metric scores across 1,000 student records:

- **Categorical Features:** `gender`, `race/ethnicity`, `parental level of education`, `lunch`, `test preparation course`
- **Target Metrics:** `math score`, `reading score`, `writing score`

---

## Project Workflow

1. **Dataset Analysis & Visualization:** Exploratory data analysis (EDA) to examine score distributions and demographic impacts.
2. **Feature Engineering:** Preprocessing categorical features using one-hot encoding for machine learning pipelines.
3. **Inferential Analysis & Hypothesis Testing:** Statistical testing and ANOVA models to validate performance drivers.
4. **Supervised Machine Learning:** Training Random Forest Classifiers to predict performance brackets using `scikit-learn` pipelines.
5. **Unsupervised Machine Learning:** Segmenting student profiles using K-Means Clustering evaluated by Silhouette Scores.
