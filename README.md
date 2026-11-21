![Mohammad Haghjoo: Business Data Science for marketing and people analytics](banner.png)

**Business Data Science · Marketing & People Analytics**

Turning marketing and HR data into *decisions* people act on.

M.Sc. student in International Information Systems at FAU Erlangen-Nürnberg. I build
reproducible statistical models and machine learning in Python, R and SQL and turn the
results into decision apps in Streamlit and Shiny. Five years of professional work with
databases, SQL reporting and data integration, and an MBA.

**Looking for a working student position (Werkstudent) in business data science, marketing
analytics or people analytics** from December 2026, up to 20 hours per week, in Nürnberg,
Erlangen, Munich or hybrid.

[Portfolio](https://mhmmdhaghjoo.github.io) · [CV (PDF)](Mohammad_Haghjoo_CV.pdf) · [LinkedIn](https://www.linkedin.com/in/mohammad-haghjoo-b241823b0) · [mohammad.haghjoo@fau.de](mailto:mohammad.haghjoo@fau.de)

## Four questions, answered

| | Question | Answer in short | Stack |
|---|---|---|---|
| **01** People analytics | [Who resigns, and can a risk list find them in time?](https://github.com/mhmmdhaghjoo/employee-turnover-analytics) | Resignations cluster in the first two years and in one department. A gradient boosting model tested on unseen years ranks leavers with ROC AUC 0.93; a fairness audit shows a simple tenure rule finds 100 % of the men who resign but 44 % of the women. [Explorer app](https://github.com/mhmmdhaghjoo/employee-turnover-analytics#explorer-app-streamlit) | Python, scikit-learn, Streamlit |
| **02** Marketing experiment | [Should the shop switch to a one-page checkout?](https://github.com/mhmmdhaghjoo/checkout-ab-test-r) | Yes on mobile, test again on desktop: conversion +0.51 points (95 % interval 0.27 to 0.75), about €45,000 a month in the simulation. Daily peeking raises false winners from 5 % to 22 %. [Shiny app](https://github.com/mhmmdhaghjoo/checkout-ab-test-r#interactive-app-shiny) | R, tidyverse, rstanarm, Shiny |
| **03** Customer analytics | [Which customers come back, and which ones carry the revenue?](https://github.com/mhmmdhaghjoo/online-retail-sql-warehouse) | 19 % order again in the month after their first order; the best segment is 24 % of customers and 54 % of revenue. Built on a star schema with 12 data-quality rules and 10 SQL tests. | PostgreSQL, SQL, Python |
| **04** Marketing machine learning | [Which customers will not order again in the next 90 days?](https://github.com/mhmmdhaghjoo/customer-churn-ml-pipeline) | Logistic regression reaches ROC AUC 0.83 on a later period, 0.034 above a recency baseline. [Decision simulator](https://github.com/mhmmdhaghjoo/customer-churn-ml-pipeline#decision-simulator-streamlit) for the contact threshold. | Python, scikit-learn, Streamlit |

The shop data in projects 02 to 04 is simulated so every result can be rerun. Project 01
uses a public practice HR dataset that appears to be simulated, so its findings illustrate
the method, not a real employer.

## How I work

1. **Business question first.** Every analysis starts from a decision someone has to make.
2. **Data quality before models.** Validation checks, reconciliation tests and documented cleaning rules come before any chart or model.
3. **AI output gets audited.** I use AI coding assistants and treat their output as a draft: tests, out-of-sample evaluation and fairness audits decide what stays.
4. **A decision someone can use.** Reports lead with the finding, and apps let people test the trade-offs themselves.

## Skills

- **Languages and querying:** SQL (PostgreSQL), Python (pandas, NumPy, SciPy, scikit-learn), R (tidyverse, ggplot2, rstanarm)
- **Statistics and machine learning:** hypothesis testing, A/B testing and experiment design, regression (including Bayesian), survival analysis, classification, clustering, out-of-time evaluation, probability calibration, fairness audits
- **Data management:** data modelling, star schema, ETL, data-quality checks, query optimisation
- **Decision apps and reporting:** Streamlit, Shiny, R Markdown, Matplotlib, management reports
- **Engineering:** Git, GitHub Actions, pytest, testthat, ruff, lintr, packaging, basic Docker

## Experience and education

- **Information Systems Specialist** — databases, reporting and data integration. Shiraz Petrochemical Co., Tehran, Iran. 08/2020 – 10/2025, full-time
- **Information Technology Specialist** — database administration and reporting. Tankerranan Petroleum Transport Company, Rafsanjan, Iran. 01/2014 – 06/2020, part-time alongside studies
- **M.Sc. International Information Systems**, FAU Erlangen-Nürnberg. Since 10/2025
- **MBA, Strategic Management**, Allameh Tabataba'i University, Tehran. 09/2021 – 02/2024, grade 19.38 of 20 (German equivalent approx. 1.2)
- **B.Sc. Computer Engineering (Software Engineering)**, Islamic Azad University, Central Tehran Branch. 10/2013 – 07/2020

**Languages:** Persian (native) · English (C1, IELTS Academic 7.5) · German (A2, improving) · Turkish (intermediate)
