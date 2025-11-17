# Explainable AI (XAI) Using SHAP — Medical Classification Model

This project focuses on applying Explainable Artificial Intelligence (XAI) techniques to understand how a medical classification model makes its predictions.
Using SHAP (SHapley Additive exPlanations), the goal is to open the machine-learning “black box” and visualize the contribution of each clinical feature.

## Overview

Machine learning models often make predictions without revealing the reasoning behind them. This project focuses on using SHAP to explain:

* Why the model predicts "diseased" or "healthy"
* Which clinical features influence the prediction
* How much each feature contributes to the final output

The project is inspired by the paper: "Opportunities and Challenges in Explainable Artificial Intelligence (XAI)" by Arun Das & Paul Rad.

## SHAP Analysis

SHAP assigns each feature a contribution value based on game theory.

### Key Insights

* AST, GGT, BIL, and ALP were the most influential features.
* Some features decreased the probability of disease (negative contribution).
* SHAP provided consistent and fair explanations across samples.

## Visualizations Included

The repository includes the following SHAP plots:

* Global Feature Importance
* SHAP Summary (Beeswarm) Plot
* Waterfall Plot for Individual Cases
* Local Force Plots

These plots clearly show how the model builds a prediction from base value to final probability.

## What This Project Demonstrates

* How to use SHAP for interpreting tabular medical data
* How to analyze both local and global feature contributions
* How explainability improves trust in healthcare AI
* How to validate ML decisions visually and numerically

## Reference

**Paper Inspiration:** Opportunities and Challenges in Explainable Artificial Intelligence (XAI)  
**Authors:** Arun Das & Paul Rad  
**Link:** [https://arxiv.org/abs/2006.11371]

## Contributing

Contributions and suggestions are welcome. Feel free to submit issues or pull requests.

## Author

**Trishala**  
Computer Science Student • AI/ML Enthusiast  
Focused on transparent, interpretable, and responsible AI.
