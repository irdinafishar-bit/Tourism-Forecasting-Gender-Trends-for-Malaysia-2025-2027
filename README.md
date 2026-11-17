# Tourism-Forecasting-Gender-Trends-for-Malaysia-2025-2027-
Full-stack analytics platform forecasting 2025–2027 Malaysian tourist arrivals using XGBoost (R² = 0.77) and Random Forest, paired with a LightGBM gender-trend classifier (F1 = 0.986) in Python and deployed via a multi-tab R Shiny dashboard.

# Tourism Forecasting & Gender Trends For Malaysia (2025-2027)

![Python](https://img.shields.io/badge/Python-ML%20Modeling-blue)
![R](https://img.shields.io/badge/R-Shiny%20Dashboard-276DC3)

## Overview
Full-stack, multi-language analytics platform built to analyze historical inbound tourism patterns in Malaysia, forecast multi-year tourist arrivals (2025–2027), and classify demographic travel trends. The architecture decouples heavy machine learning training in Python from a reactive, multi-tab interactive web dashboard in R Shiny.

## Key Components
* **Multi-Year Tourist Arrival Forecasting (2025–2027):**
  * Engineered temporal and country-level features across historical arrival records.
  * Benchmarked regression models in Python, with **XGBoost ($R^2 = 0.77$)** and **Random Forest** capturing seasonal recovery and growth trajectories through 2027.
* **Demographic Gender-Trend Classification:**
  * Built a supervised classification pipeline using **LightGBM** to identify dominant traveler gender segments across source markets and entry points, achieving an **$F1$-score of 0.986**.
* **Interactive R Shiny Dashboard:**
  * Integrates pre-computed Python model outputs into a multi-tab interface featuring dynamic country filters, 2025–2027 forecast visualizations, and demographic breakdowns.

## Tech Stack
* **Machine Learning (Python):** `pandas`, `numpy`, `scikit-learn`, `xgboost`, `lightgbm`
* **Visualization & Web App (R):** `shiny`, `ggplot2`, `plotly`, `dplyr`
