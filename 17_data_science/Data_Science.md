# 17. Data Science & Statistics

## Degree Programs

| Level | Programs |
|---|---|
| Undergraduate | Statistics (BS/BA), Data Science (BS), Applied Mathematics & Statistics, Actuarial Science |
| Masters | MS in Statistics, MS in Data Science, MS in Biostatistics, MS in Analytics, MS in Applied Statistics, MA in Statistics |
| PhD | Statistics, Biostatistics, Data Science (emerging), Applied Mathematics & Statistics |

**Note:** Data Science is a rapidly evolving field at the intersection of statistics, computer science, and domain expertise. Standalone Data Science degree programs have proliferated since ~2015, while Statistics departments remain the intellectual foundation. This document covers both.

---

## 17.1 Core Curriculum (Undergraduate)

### Foundation
Calculus I-III, Linear Algebra, Multivariable Calculus, Probability Theory, Programming (Python, R).

### Core Courses

| Course | Content |
|---|---|
| **Probability Theory** | Probability axioms, random variables (discrete/continuous), joint distributions, expectation, moment-generating functions, law of large numbers, central limit theorem, convergence concepts |
| **Mathematical Statistics** | Point estimation (MLE, method of moments, Bayesian), interval estimation, hypothesis testing (Neyman-Pearson, likelihood ratio), sufficiency, completeness, UMVUE, asymptotic theory |
| **Linear Regression** | Simple and multiple regression, least squares, inference on coefficients, model diagnostics, multicollinearity, variable selection, ANOVA, generalized linear models (intro) |
| **Statistical Computing** | R/Python for data analysis, simulation (Monte Carlo, bootstrap), numerical optimization (Newton, EM algorithm), reproducible research, data wrangling |
| **Data Structures & Programming** | Python/R programming, data manipulation (pandas, dplyr), SQL, algorithms basics, software engineering for data science |
| **Machine Learning** | Supervised learning (regression, classification, trees, SVMs, neural networks), unsupervised learning (clustering, PCA, dimensionality reduction), model selection (cross-validation, bias-variance) |
| **Data Visualization** | Grammar of graphics (ggplot2), interactive visualization (D3.js, Plotly, Tableau), principles of effective visual communication, exploratory data analysis |
| **Experimental Design** | Randomization, blocking, factorial designs, fractional factorials, response surface methodology, A/B testing, power analysis |
| **Time Series** | Stationarity, ARIMA models, spectral analysis, state space models, forecasting, GARCH (finance) |

**Key Textbooks:**
- Casella & Berger – *Statistical Inference*
- Hastie, Tibshirani & Friedman – *The Elements of Statistical Learning*
- James, Witten, Hastie & Tibshirani – *An Introduction to Statistical Learning* (ISLR)
- Wackerly, Mendenhall & Scheaffer – *Mathematical Statistics with Applications*
- Gelman, Carlin, Stern, Dunson, Vehtari & Rubin – *Bayesian Data Analysis*
- Wickham & Grolemund – *R for Data Science*
- Rice – *Mathematical Statistics and Data Analysis*
- Montgomery – *Design and Analysis of Experiments*
- Box, Jenkins, Reinsel & Ljung – *Time Series Analysis: Forecasting and Control*

---

## 17.2 Graduate Specialization Areas

#### A. Statistical Theory
- Decision theory, nonparametric statistics, asymptotic theory, semiparametric models, empirical processes, high-dimensional statistics, minimax theory, admissibility

#### B. Bayesian Statistics
- Bayesian hierarchical models, MCMC methods (Metropolis-Hastings, Gibbs, Hamiltonian Monte Carlo), variational inference, Bayesian nonparametrics (Dirichlet processes, Gaussian processes), Bayesian decision theory, Stan/JAGS/PyMC

#### C. Biostatistics
- Clinical trials design (Phase I-III, adaptive designs), survival analysis (Kaplan-Meier, Cox model), longitudinal data analysis (mixed models, GEE), causal inference in observational studies (propensity scores, IV), genomics/genetics statistics (GWAS, multiple testing), EHR data analysis

#### D. Machine Learning & Statistical Learning
- Deep learning theory, kernel methods, random forests, boosting (XGBoost, LightGBM), neural network theory (overparameterization, double descent), online learning, bandit algorithms, transfer learning, few-shot learning

#### E. Causal Inference
- Potential outcomes framework (Rubin), structural causal models (Pearl, DAGs), instrumental variables, regression discontinuity, difference-in-differences, synthetic control, mediation analysis, causal discovery algorithms

#### F. High-Dimensional Statistics
- Lasso, elastic net, sparse regression, compressed sensing, random matrix theory, covariance estimation, high-dimensional testing, post-selection inference, debiased lasso

#### G. Spatial & Environmental Statistics
- Geostatistics (kriging), spatial point processes, spatio-temporal models, environmental monitoring, remote sensing data, climate statistics, spatial econometrics

#### H. Natural Language Processing (Statistical)
- Language models, topic models (LDA), sentiment analysis, information extraction, text classification, word embeddings, Transformer architectures, evaluation methodology

#### I. Data Engineering & Systems
- Data pipelines (ETL/ELT), distributed computing (Spark, Dask), data warehousing, feature engineering, MLOps (model deployment, monitoring, retraining), data quality, streaming data

---

## 17.3 Key Methods & Tools

| Category | Examples |
|---|---|
| **Languages** | R, Python, SQL, Julia, SAS, Stata |
| **R Ecosystem** | tidyverse, ggplot2, caret/tidymodels, Shiny, Stan (rstan), lme4 |
| **Python Ecosystem** | pandas, NumPy, SciPy, scikit-learn, statsmodels, PyTorch, matplotlib, seaborn |
| **Big Data / Distributed** | Apache Spark, Dask, Hadoop, Presto/Trino, BigQuery, Snowflake, Databricks |
| **Visualization** | ggplot2, Matplotlib, Plotly, D3.js, Tableau, Streamlit |
| **Bayesian** | Stan, PyMC, JAGS, BUGS, Edward, NumPyro |
| **ML Platforms** | Hugging Face, Weights & Biases, MLflow, SageMaker |
| **Experimentation** | A/B testing platforms, power calculators, causal inference packages (DoWhy, EconML) |

---

## 17.4 Foundational Texts

### Core Textbooks

#### Undergraduate Core

| Subject | Standard text | Notes |
|---|---|---|
| Statistical Inference | Casella & Berger — *Statistical Inference* | Standard rigorous inference text |
| Statistical Learning | James et al. — *An Introduction to Statistical Learning* | Default first applied ML/stat learning text |
| Statistical Learning (advanced) | Hastie, Tibshirani & Friedman — *The Elements of Statistical Learning* | Canonical advanced learning text |
| Regression | Weisberg — *Applied Linear Regression* | Standard regression text |
| Bayesian Statistics | Gelman et al. — *Bayesian Data Analysis* | Standard Bayesian text |
| Experimental Design | Montgomery — *Design and Analysis of Experiments* | Standard design text |
| Time Series | Box, Jenkins, Reinsel & Ljung — *Time Series Analysis* | Standard forecasting text |
| Data Wrangling | Wickham & Grolemund — *R for Data Science* | Standard practical workflow text |

#### Graduate / Reference Texts

| Subject | Standard text | Notes |
|---|---|---|
| Probability | Wasserman — *All of Statistics* / van der Vaart theory texts | Common graduate bridge |
| Asymptotic Statistics | van der Vaart — *Asymptotic Statistics* | Standard advanced theory text |
| Causal Inference | Hernán & Robins — *Causal Inference* | Standard modern causal text |
| Machine Learning | Murphy — *Probabilistic Machine Learning* | Standard broad graduate reference |
| High-Dimensional Statistics | Wainwright — *High-Dimensional Statistics* | Standard modern theory text |
| Convex Optimization | Boyd & Vandenberghe — *Convex Optimization* | Core optimization reference |

### Recommended Papers

#### Classic / Foundational
- Fisher (1922) — mathematical foundations of theoretical statistics.
- Neyman & Pearson (1933) — the most efficient tests of statistical hypotheses.
- Kolmogorov (1933) — probability axiomatization.
- Cox (1972) — regression models and life tables.
- Akaike (1974) — AIC.
- Dempster, Laird & Rubin (1977) — EM algorithm.
- Efron (1979) — bootstrap methods.
- Rosenbaum & Rubin (1983) — propensity score.
- Breiman, Friedman, Olshen & Stone (1984) — CART.
- Benjamini & Hochberg (1995) — false discovery rate control.

#### Methods / Canonical Frameworks
- Tibshirani (1996) — LASSO.
- Breiman (2001) — random forests.
- Friedman (2001) — gradient boosting machine.
- Vapnik and kernel/SVM milestone papers.
- Rubin (1974) — causal model and missing-data foundations.
- Efron et al. (2004) — least angle regression.
- Donoho (2006) — compressed sensing.
- Meinshausen & Bühlmann stability selection papers.
- Pearl (2009-era) — structural causal model summaries.

#### Modern Field-Defining Results
- Jordan et al. variational/Bayesian machine-learning synthesis papers.
- Friedman, Hastie & Tibshirani (2010) — regularization paths via coordinate descent.
- Chen & Guestrin (2016) — XGBoost.
- Lei, G'Sell, Rinaldo, Tibshirani & Wasserman (2018) — conformal prediction distribution-free methods.
- Chernozhukov et al. (2018) — double/debiased machine learning.
- Van der Laan & Rose targeted learning papers.
- Single-cell / high-dimensional biostatistics method papers.
- Deep-learning theory papers on double descent and interpolation.
- Causal forest and heterogeneous treatment effect papers.

#### Reviews / Orientation
- Breiman (2001) — statistical modeling: the two cultures.
- Tukey (1977) — exploratory data analysis perspective.
- Donoho (2017) — 50 years of data science.
- Blei, Kucukelbir & McAuliffe (2017) — variational inference review.
- Gelman & Vehtari papers on workflow and model checking.
- Claeskens / Hjort and model-selection review papers.

## 17.5 Open Problems & Research Frontiers

- **Causal inference revolution** — Moving from association to causation; scalable causal discovery; causal ML; heterogeneous treatment effects; causal inference with LLMs
- **Foundation models & statistics** — Understanding generalization in overparameterized models; statistical theory for deep learning; conformal prediction for uncertainty
- **Fairness, accountability, transparency** — Statistical definitions of fairness, bias detection/mitigation, algorithmic auditing, interpretable ML
- **Selective inference** — Valid inference after model/variable selection; post-selection inference; conditional inference
- **Privacy-preserving data analysis** — Differential privacy, federated analytics, synthetic data generation, privacy-utility tradeoffs
- **Streaming & real-time analytics** — Online learning, change-point detection, real-time anomaly detection, adaptive experimentation
- **Integration of domain knowledge** — Physics-informed ML, structured models, Bayesian priors from scientific knowledge, scientific machine learning
- **Reproducibility crisis** — Statistical aspects: p-hacking, HARKing, replication; pre-registration, multi-analyst studies, methodological reform

---

## 17.6 Career Paths & Salary Benchmarks

| Role | Range (US) |
|---|---|
| Data analyst (BS) | $60K–$85K |
| Data scientist (MS) | $100K–$160K |
| Senior data scientist | $140K–$220K |
| ML engineer | $120K–$250K+ |
| Statistician (government/pharma) | $70K–$120K |
| Biostatistician | $75K–$130K |
| Actuary (ASA/FSA) | $80K–$200K+ |
| Quantitative researcher (finance) | $150K–$400K+ |
| Research scientist (tech, PhD) | $150K–$300K+ |
| Faculty (R1 Statistics) | $100K–$170K |

**Major Employers:** Google, Meta, Amazon, Microsoft, Netflix, Spotify, Airbnb, Uber, LinkedIn, pharma (Pfizer, Roche, Genentech), insurance, financial firms (Goldman, Citadel, D.E. Shaw), government (Census Bureau, BLS, FDA, NIH), consulting (McKinsey QuantumBlack).

---

## 17.7 Connections to Other Fields

| Field | Connection |
|---|---|
| **Mathematics** | Probability, measure theory, optimization, linear algebra |
| **Computer Science** | Machine learning, algorithms, databases, distributed computing |
| **Economics / Econometrics** | Causal inference, panel data, instrumental variables, time series |
| **Biology / Genomics** | Biostatistics, GWAS, single-cell analysis, phylogenetics |
| **Medicine / Public Health** | Clinical trials, epidemiology, health informatics, survival analysis |
| **Physics** | Statistical mechanics, Bayesian physics, uncertainty quantification |
| **Social Sciences** | Survey methodology, psychometrics, social network analysis |
| **Business** | A/B testing, forecasting, operations, marketing analytics, pricing |

---

## Appendix: Key Conferences & Journals

| Venue | Type |
|---|---|
| NeurIPS, ICML, ICLR | Machine learning conferences |
| KDD, AAAI, AISTATS | Data mining & AI + statistics |
| JSM (Joint Statistical Meetings) | Largest statistics gathering |
| *Annals of Statistics* | Top statistics journal |
| *JASA (Journal of the American Statistical Association)* | Premier applied statistics |
| *Biometrika* | Theoretical/methodological statistics |
| *Statistical Science* | Review articles |
| *JMLR (Journal of Machine Learning Research)* | ML theory/methods |
| *Biostatistics*, *Biometrics* | Biostatistics journals |
