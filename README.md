# Aritra Panja | Business Analytics & Business Analysis Portfolio

![Business Analysis](https://img.shields.io/badge/Business%20Analysis-Requirements%20%26%20Process%20Improvement-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualisation-yellow)
![Python](https://img.shields.io/badge/Python-Analytics%20%26%20Machine%20Learning-blue)
![SQL](https://img.shields.io/badge/SQL-Data%20Analysis-lightgrey)
![SAP](https://img.shields.io/badge/SAP-S%2F4HANA%20%7C%20Analytics%20Cloud-0FAAFF)
![Decision Science](https://img.shields.io/badge/Decision%20Science-Simulation%20%26%20Optimisation-green)

## About This Portfolio

Welcome to my portfolio of applied **Business Analysis, Business Analytics, Business Intelligence, and Decision Science projects**.

This repository demonstrates how I approach business and operational problems by combining:

* business problem definition;
* data analysis and visualisation;
* KPI development and performance analysis;
* machine learning and predictive analytics;
* process modelling and simulation;
* optimisation and scenario analysis;
* risk and uncertainty analysis;
* business-focused recommendations.

My focus is not only on building analytical models, but on translating analysis into **clear, practical, and actionable business decisions**.

---

## Quick Navigation

| Project                                                                                         | Business Problem                                                                                                       | Key Methods                                                       |
| ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| [Employee Attrition Prediction](./projects/01-employee-attrition-prediction/)                   | How can organisations identify employees at higher risk of voluntary attrition and prioritise retention interventions? | Python, Machine Learning, SMOTE, SHAP, Threshold Analysis         |
| [Business Intelligence & Decision Making](./projects/02-business-intelligence-decision-making/) | How can organisational data be transformed into meaningful performance insights?                                       | Power BI, KPI Analysis, Performance Reporting, Data Visualisation |
| [Customer Sentiment Analysis](./projects/03-customer-sentiment-analysis/)                       | How can large volumes of customer feedback be automatically classified and analysed?                                   | NLP, TF-IDF, Logistic Regression, Naive Bayes, CNN, BERT          |
| [Food Redistribution Simulation](./projects/04-food-redistribution-simulation/)                 | How can food redistribution operations be improved to reduce waste and operational bottlenecks?                        | Discrete Event Simulation, Process Modelling, Capacity Analysis   |
| [Optimisation & Decision Modelling](./projects/05-optimisation-decision-modelling/)             | How can transportation costs be minimised while satisfying capacity and allocation constraints?                        | Linear Programming, Excel Solver, Scenario Analysis               |
| [Risk Management](./projects/06-risk-management/)                                               | How can project uncertainty be incorporated into planning and decision-making?                                         | Risk Analysis, Dependency Analysis, Scenario Reasoning            |
| [Behavioural Operations](./projects/07-behavioural-operations/)                                 | How do behavioural factors influence operational and economic decisions?                                               | Expected Utility Theory, Behavioural Analysis, Decision Theory    |

---

# Featured Case Studies

## 1. Employee Attrition Prediction

### Business Question

How can an organisation identify employees at higher risk of voluntary attrition while keeping retention interventions operationally realistic?

### Visual Preview

![Threshold Trade-off Analysis](./projects/01-employee-attrition-prediction/assets/threshold-tradeoff-analysis.png)

This visual shows the trade-off between precision, recall, and intervention volume, helping convert the attrition model into a practical HR decision-support tool.

### What I Did

* Developed an end-to-end machine learning classification workflow.
* Compared six predictive models.
* Applied leakage-safe preprocessing and in-fold SMOTE.
* Evaluated models using ROC-AUC, PR-AUC, precision, recall, and F1-score.
* Performed threshold sensitivity analysis based on intervention capacity.
* Used SHAP to explain the main drivers of attrition.
* Conducted fairness analysis across employee groups.
* Translated predictive outputs into retention-focused business recommendations.

### Methods & Tools

`Python` `Pandas` `Scikit-learn` `XGBoost` `SMOTE` `SHAP` `Machine Learning`

[View Project](./projects/01-employee-attrition-prediction/)

---

## 2. Business Intelligence & Decision Making

### Business Question

How can sales and operational data be transformed into meaningful performance insights for management decision-making?

### Visual Preview

![Sales and Profit Trend](./projects/02-business-intelligence-decision-making/assets/sales-profit-trend.png)

This visual summarises sales and profit movement over time, supporting management-level performance analysis and commercial decision-making.

### What I Did

* Analysed sales and profitability performance.
* Evaluated product and category performance.
* Examined regional and geographical trends.
* Analysed customer segments.
* Investigated discount relationships.
* Evaluated shipping mode performance.
* Analysed product return trends.
* Considered organisational challenges involving data quality, integration, and analytics adoption.

### Methods & Tools

`Power BI` `KPI Analysis` `Data Visualisation` `Performance Analysis` `Business Intelligence`

[View Project](./projects/02-business-intelligence-decision-making/)

---

## 3. Food Redistribution Simulation

### Business Question

How can a university food redistribution process be redesigned to reduce waste and improve operational flow?

### Visual Preview

![Food Redistribution Process Flow](./projects/04-food-redistribution-simulation/assets/food-redistribution-des-flow.png)

This visual represents the food redistribution process flow used to analyse bottlenecks, queues, capacity constraints, and improvement opportunities.

### What I Did

* Modelled the end-to-end redistribution process.
* Represented collection, sorting, storage, and distribution activities.
* Analysed process bottlenecks and queues.
* Evaluated capacity constraints.
* Tested alternative operational scenarios.
* Developed evidence-based process improvement recommendations.

### Methods & Tools

`Discrete Event Simulation` `Process Modelling` `Bottleneck Analysis` `Capacity Planning` `Scenario Analysis`

[View Project](./projects/04-food-redistribution-simulation/)

---

# Skills & Technology

## Business Analysis

| Area             | Skills                                                                                                      |
| ---------------- | ----------------------------------------------------------------------------------------------------------- |
| Requirements     | Requirements Elicitation, Business Requirements, Functional Requirements, User Stories, Acceptance Criteria |
| Process Analysis | As-Is Analysis, To-Be Design, Gap Analysis, Process Mapping, BPMN                                           |
| Delivery         | UAT, Test Scenarios, Traceability, Agile, Scrum, Kanban                                                     |
| Stakeholders     | Workshops, Interviews, Stakeholder Management, Cross-functional Collaboration                               |
| Improvement      | Root Cause Analysis, Process Improvement, Business Case Development, Decision Support                       |

## Data & Business Intelligence

| Area           | Skills                                                                  |
| -------------- | ----------------------------------------------------------------------- |
| Data Analysis  | SQL, Python, Excel                                                      |
| BI & Reporting | Power BI, SAP Analytics Cloud, KPI Reporting                            |
| Visualisation  | Dashboard Development, Executive Reporting, Data Storytelling           |
| Analysis       | Trend Analysis, Variance Analysis, Segmentation, Performance Monitoring |

## Analytics & Decision Science

| Area                | Skills                                                                        |
| ------------------- | ----------------------------------------------------------------------------- |
| Machine Learning    | Logistic Regression, Decision Trees, Random Forest, XGBoost, Naive Bayes, SVM |
| NLP                 | TF-IDF, Sentiment Analysis, CNN, BERT                                         |
| Explainability      | SHAP, Feature Importance, Threshold Analysis                                  |
| Operations Research | Simulation, Linear Programming, Optimisation                                  |
| Decision Analysis   | Scenario Analysis, Risk Analysis, Behavioural Decision-Making                 |

## Enterprise Platforms

`SAP S/4HANA` `SAP Analytics Cloud` `ServiceNow` `Power BI` `Azure` `Excel`

---

# Repository Structure

```text
Aritra-Panja-Business-Analytics-Portfolio/
│
├── README.md
│
└── projects/
    │
    ├── 01-employee-attrition-prediction/
    │   ├── README.md
    │   ├── employee-attrition-prediction-report.pdf
    │   └── assets/
    │       ├── threshold-tradeoff-analysis.png
    │       ├── attrition-feature-importance.png
    │       └── model-confusion-matrix.png
    │
    ├── 02-business-intelligence-decision-making/
    │   ├── README.md
    │   ├── business-intelligence-decision-making-report.pdf
    │   └── assets/
    │       ├── sales-profit-trend.png
    │       ├── category-profitability-analysis.png
    │       └── returns-kpi-analysis.png
    │
    ├── 03-customer-sentiment-analysis/
    │   ├── README.md
    │   ├── customer-sentiment-analysis-report.pdf
    │   └── assets/
    │
    ├── 04-food-redistribution-simulation/
    │   ├── README.md
    │   ├── food-redistribution-simulation-report.pdf
    │   └── assets/
    │       └── food-redistribution-des-flow.png
    │
    ├── 05-optimisation-decision-modelling/
    │   ├── README.md
    │   ├── optimisation-decision-modelling-report.pdf
    │   └── assets/
    │
    ├── 06-risk-management/
    │   ├── README.md
    │   ├── risk-management-report.pdf
    │   └── assets/
    │
    └── 07-behavioural-operations/
        ├── README.md
        ├── behavioural-operations-report.pdf
        └── assets/
```

---

# Which Projects Should You View?

### Business Analyst Roles

Recommended starting points:

1. [Business Intelligence & Decision Making](./projects/02-business-intelligence-decision-making/)
2. [Food Redistribution Simulation](./projects/04-food-redistribution-simulation/)
3. [Optimisation & Decision Modelling](./projects/05-optimisation-decision-modelling/)
4. [Risk Management](./projects/06-risk-management/)

### Data Business Analyst & BI Analyst Roles

Recommended starting points:

1. [Business Intelligence & Decision Making](./projects/02-business-intelligence-decision-making/)
2. [Employee Attrition Prediction](./projects/01-employee-attrition-prediction/)
3. [Customer Sentiment Analysis](./projects/03-customer-sentiment-analysis/)

### Process Improvement & Operational Analytics Roles

Recommended starting points:

1. [Food Redistribution Simulation](./projects/04-food-redistribution-simulation/)
2. [Optimisation & Decision Modelling](./projects/05-optimisation-decision-modelling/)
3. [Risk Management](./projects/06-risk-management/)

---

# About Me

I am a **Business Analytics professional** with experience across business analysis, SAP-enabled process improvement, requirements gathering, process analysis, KPI development, reporting, and data analytics.

I hold an **MSc in Business Analytics & Management Science with Distinction** from the **University of Southampton**.

My experience combines:

* business analysis and requirements gathering;
* SAP-enabled business process improvement;
* stakeholder workshops and cross-functional collaboration;
* data analysis using SQL, Python, Power BI, and Excel;
* KPI development and performance reporting;
* process mapping and gap analysis;
* UAT and test scenario development;
* analytical modelling and decision support.

I am interested in opportunities across **Business Analysis, Data Business Analysis, Business Intelligence, Process Improvement, Product Analysis, and SAP-enabled Business Transformation**.

---

# Contact

**Aritra Panja**

Business Analyst | Business Analytics | Data & BI | SAP Process Improvement

**LinkedIn:** [linkedin.com/in/aritra-panja271098](https://www.linkedin.com/in/aritra-panja271098)

**Email:** [aritrapanja@gmail.com](mailto:aritrapanja@gmail.com)

---

## Portfolio Purpose

> Understanding business problems, structuring analytical solutions, evaluating alternatives, and translating data into actionable business decisions.

Thank you for visiting my portfolio.
