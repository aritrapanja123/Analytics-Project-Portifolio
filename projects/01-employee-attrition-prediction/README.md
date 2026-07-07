# Predicting Employee Attrition

## Project Overview

Employee attrition creates recruitment costs, productivity loss, disruption, and loss of organisational knowledge. This project develops a machine learning framework to predict voluntary employee attrition and translate model outputs into practical retention decisions.

## Business Problem

The key challenge is not simply predicting who may leave. HR teams have limited intervention capacity, so the analytical solution must balance predictive performance, false positives, false negatives, intervention workload, explainability, and fairness.

## Objectives

- Predict employee attrition using classification models.
- Compare multiple machine learning approaches.
- Handle class imbalance appropriately.
- identify the main drivers of attrition.
- Evaluate decision thresholds rather than relying only on the default 0.50 threshold.
- Translate predictions into actionable retention insights.
- Review model fairness across relevant employee groups.

## Analytical Approach

The project benchmarks six classification models:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- XGBoost
- Gaussian Naive Bayes

The workflow includes data cleaning, missing-value treatment, categorical encoding, selective feature scaling, stratified train-test splitting, in-fold SMOTE, repeated cross-validation, held-out test evaluation, threshold sensitivity analysis, cost-sensitive reasoning, SHAP explainability, and fairness analysis.

## Evaluation Metrics

The models were assessed using metrics appropriate for imbalanced classification:

- ROC-AUC
- PR-AUC
- Precision
- Recall
- F1-score
- Confusion matrix
- Flag rate and intervention volume

## Key Findings

The analysis showed that employee attrition risk is associated with a combination of work patterns, compensation, career stage, tenure, satisfaction, involvement, travel, and personal circumstances. Important drivers included overtime, job satisfaction, monthly income, age, years at the company, distance from home, environment satisfaction, job involvement, and marital status.

A major conclusion of the project is that model selection should not be based on accuracy alone. The operating threshold should reflect organisational capacity and the relative consequences of missed leavers and unnecessary interventions.

## Business Value

The project demonstrates how predictive analytics can support targeted retention strategies while keeping decisions explainable and operationally realistic.

Potential uses include:

- prioritising retention conversations;
- identifying high-risk employee segments;
- designing targeted interventions;
- supporting workforce planning;
- evaluating the operational cost of different decision thresholds.

## Tools and Techniques

Python, pandas, scikit-learn, imbalanced-learn, XGBoost, SHAP, classification modelling, cross-validation, SMOTE, explainable AI, threshold optimisation, and fairness analysis.

## Skills Demonstrated

Business problem framing, predictive analytics, model comparison, imbalanced classification, model evaluation, explainability, fairness analysis, decision threshold governance, and business recommendation development.

## Future Improvements

Future work could include external validation on data from additional organisations, survival analysis, time-dependent attrition modelling, causal analysis of retention interventions, and integration with a Power BI or Streamlit decision-support dashboard.
