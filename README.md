# Housing Price Prediction (Kaggle Competition)

This repository contains my final project submission for the **STAT 361 – Fall 2024** course competition hosted on **Kaggle**. The goal is to build predictive regression models to estimate median home values (`medv`) using the Boston Housing dataset and compete on the Kaggle leaderboard. :contentReference[oaicite:1]{index=1}

---

## Project Overview

**Objective:**  
Predict median home values (`medv`) from housing and socioeconomic variables using regression techniques and submit predictions to the **STAT 361 Project – Fall 2024** Kaggle competition. :contentReference[oaicite:2]{index=2}

**Competition Link:**  
https://www.kaggle.com/competitions/stat-361-project-fall-2024/leaderboard :contentReference[oaicite:3]{index=3}

**Metric:**  
Competition defines a specific scoring metric (usually RMSE or similar on a holdout test set). Submissions are ranked on a **leaderboard** that combines public and private test subsets. :contentReference[oaicite:4]{index=4}

---

## Models Developed

Three main model classes were explored:

### 1. Linear Regression
- Baseline model using all predictors
- Stepwise feature selection using AIC/BIC
- Diagnostic plots to assess assumptions

### 2. Quadratic Regression
- Added squared terms for non-linear effects
- Model refinement via stepwise selection
- Evaluated based on AIC/BIC and validation metrics

### 3. Cubic Regression
- Included up to third-order polynomial terms
- Variable elimination to prevent overfitting
- Final models compared using AIC, BIC, and diagnostic plots

---

## Model Performance

Final comparative scores (e.g., RMSE/score from validation or competition results):

| Model Type      | Score (Lower is Better) |
|------------------|-------------------------|
| Linear           | 3.88508                 |
| Quadratic        | 3.21756                 |
| Cubic            | 3.27288                 |

The **quadratic model** achieved the best validation performance. Final competition predictions were generated using the **cubic model**. (Adjust based on your findings.)


