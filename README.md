# Hi, I'm Michele 👋

I am a recent MSc graduate in Mathematical Engineering, passionate about applying mathematics to **statistical learning, numerical modelling, and simulation**.

Throughout my academic journey, I developed the mathematical, statistical, and computational skills needed to approach complex problems across these areas.

## Featured Projects

### [Retail Churn Prediction — Online Retail II](https://github.com/michelebirardi21/retail-churn-prediction)

**End-to-end Data Science project**

A reproducible churn prediction pipeline built on transactional e-commerce data (*Online Retail II*, UCI), focusing on temporal validation, probability calibration, and economic decision-making rather than metric chasing.

Key components of the workflow:

- **SQL data engineering (DuckDB):** deduplication, net-spend target definition (accounting for cancelled orders), and 32 behavioral/RFM features computed strictly before each snapshot date on active customers;
- **Modelling and validation:** chronological train/validation/test split, expanding-window tuning for LightGBM, comparison against a recency baseline and regularized Logistic Regression, Platt vs. isotonic calibration, and paired bootstrap confidence intervals;
- **Interpretability and business impact:** SHAP analysis, expected-value targeting policy, and a 3×3 sensitivity analysis across retention rates and contact costs.

The pipeline is fully automated in Python and verified with `pytest` checks for data integrity and leakage prevention.

---

### [Ground-Motion Site Effects in Italy](https://github.com/michelebirardi21/ground-motion-analysis-italy)

**MSc thesis project**

A geostatistical analysis of residual ground-motion site effects across Italy, based on seismic events that occurred in Central Italy.

The project compares three modelling approaches:

* a parametric stationary geostatistical model;
* a locally adaptive non-stationary model based on Random Domain Decomposition;
* a non-parametric geostatistical model.

The analyses consider both **Peak Ground Acceleration (PGA)** and **Peak Ground Velocity (PGV)**, with the aim of modelling and mapping the spatial variability of site effects.

---

### [Cheers to Deals — Retail Beer Volumes and Promotions](https://github.com/beasisti/Applied_Project)

**Applied Statistics project**

A collaborative study of beer sales dynamics, developed as part of the Applied Statistics course.

The analysis examines sales volumes for the 20 best-selling beers between February 2019 and February 2024, investigating how brands, individual products, and different types of promotion influence retail sales.

---

### [Bayesian Identification of Circadian Genes](https://github.com/gidiesse/circadian_genes_bayesian)

**Bayesian Statistics project**

A collaborative project developed as part of the Bayesian Statistics course.
The study focused on the identification of circadian genes through the analysis of gene-expression time series.

The project had two main objectives:

* identifying circadian genes by examining the periodic behaviour of their transcripts;
* developing a Bayesian approach for detecting periodic signals while accounting for dependence across genes.

The methodology combines Bayesian statistical modelling with computational inference techniques for the analysis of high-dimensional biological data.


<!--
**michelebirardi21/michelebirardi21** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
