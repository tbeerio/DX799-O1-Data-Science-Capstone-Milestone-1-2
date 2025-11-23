**Modeling U.S. Macroeconomic Activity Using the FRED-MD Dataset**

**Overview**

This repository contains the code, data, and documentation for Milestone One of my Data Science Capstone (DX799 O1). The project applies a series of machine learning and econometric methods to forecast monthly industrial production growth (Δlog(INDPRO) × 100) using the FRED-MD dataset.

The analysis progresses over six weeks of modeling experiments, each introducing new techniques for improving predictive performance, interpretability, and robustness in macroeconomic forecasting.

├── Beer_Tim_Week_1.ipynb        # Week 1 – EDA and Polynomial Regression baseline  
├── Beer_Tim_Week_2.ipynb        # Week 2 – Regularized Regression (Lasso, Ridge, Elastic Net)  
├── Beer_Tim_Week_3.ipynb        # Week 3 – Stepwise OLS, PCR, and PLSR  
├── Beer_Tim_Week_4.ipynb        # Week 4 – Logistic Classification (Expansion vs. Contraction)  
├── Beer_Tim_Week_5.ipynb        # Week 5 – Support Vector Regression (Linear vs. RBF)  
├── Beer_Tim_Week_6.ipynb        # Week 6 – Decision Tree and Random Forest Models  
│
├── Beer_Tim_Week_8.ipynb        # Week 8 – K-Nearest Neighbors (baseline + tuning)
├── Beer_Tim_Week_9.ipynb        # Week 9 – Gradient Boosting (baseline + full tuning)
├── Beer_Tim_Week_10.ipynb       # Week 10 – Clustering Part I (DBSCAN + K-means structure tests)
├── Beer_Tim_Week_11.ipynb       # Week 11 – Clustering Part II (DBSCAN refinement + HAC + dendrograms)


├── fredmd_clean.csv             # Cleaned macroeconomic dataset (1959–2025 sample)  
├── X_transformed_week2.csv      # Transformed features (ADF-based transformations)  
├── y_target_week2.csv           # Target variable: Δlog(INDPRO) × 100  

├── week3_model_comparison.csv   # Model comparison metrics from Week 3  
├── week3_best_predictions.csv   # Best test predictions from Week 3 (PLSR)  
├── week4_logit_results.csv      # Logistic regression results summary  
├── week4_logit_test_probs.csv   # Predicted probabilities from logistic models  
├── week6_dt_baseline_results.csv# Decision tree regression results  
├── week6_rf_results.csv         # Random forest regression results  

├── feature_correlations_full.csv# Correlation matrix used in Week 1 EDA  
├── 2025-09-MD.csv               # Raw input macro panel (FRED-MD base)  
│
└── README.md                    # Project documentation (this file)

**Dataset**

The dataset originates from the Federal Reserve Bank of St. Louis – FRED-MD Database, a publicly available monthly panel of U.S. macroeconomic indicators developed by McCracken and Ng (2015).

Link: https://www.stlouisfed.org/research/economists/mccracken/fred-databases

