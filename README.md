# BIAS-in-COMPAS-SCORES
 # COMPAS Bias Audit & Fairness Mitigation

This project analyzes racial bias in the **COMPAS recidivism risk assessment system** using the Broward County dataset. We evaluate baseline machine learning models and apply fairness mitigation techniques to reduce disparities between **Black** and **Non-Black** defendants.

## Objectives

* Quantify bias using fairness metrics (Statistical Parity, Disparate Impact, TPR/FPR gaps)
* Compare baseline models (Logistic Regression, Random Forest)
* Apply fairness interventions:

  * **Reweighing** (pre-processing)
  * **Threshold Optimization** (post-processing)
* Visualize selection rates, score distributions, and ROC curves by race

## Methods

* Dataset: Broward County COMPAS data
* Protected attribute: Race (Black vs Non-Black)
* Models: Logistic Regression, Random Forest
* Fairness tools: Custom metrics + AIF360-style methods

## Key Findings

* Baseline models predict “high risk” far more often for Black defendants
* Reweighing reduces disparities
* Threshold Optimization nearly equalizes selection rates across groups

## Outputs

* Fairness metrics summary table (CSV)
* Selection rate comparison plots
* Probability distribution and ROC plots by race

## Disclaimer

This project is for **educational and research purposes only**. COMPAS is a real-world system with serious ethical implications, and results should be interpreted in social and legal context.


