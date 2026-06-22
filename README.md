# From raw data to real answers.

**Prasad Patil · Data Analyst · MS Applied Data Science · Syracuse University · GPA 3.9 · May 2026**  
Authorized to work in the US — OPT EAD June 2026–2027 · STEM extension eligible to June 2029

---

Most data problems aren't visible on the surface. The failure rate looks normal until you separate clean records from noise. The fraud exposure is buried in transaction type distributions. The delivery problem is concentrated in two regions nobody checked.

I find those patterns. I prove them statistically. I explain what they mean to someone who needs to make a decision.

**SQL** to extract and investigate · **Python and R** to clean, model, and validate · **Power BI and Tableau** to communicate the answer · **dbt and Snowflake** to make it repeatable.

---

## By The Numbers

| What I Found | Proof |
|---|---|
| $3.08M fraud exposure across 590K transactions | χ²=368.90 p≈0 |
| $34K LTV gap across 36 customer segments | χ²=293.15 p≈0 |
| $21M revenue at risk in supply chain | χ²=41,856 p≈0 |
| $259K capacity recovered in manufacturing | ANOVA + Tukey pairwise |
| 88% of failures traced to 2 defect categories | Pareto + chi-square |
| Cash loans default at 8.35% vs revolving 5.48% | A/B test, 95% power |
| Demand forecasting at 0.6% MAPE | Prophet model, 180K orders |
| $15.42M revenue tracked with anomaly detection | Real-time dbt + Delta Lake |
| 5.7M taxi records — fare and fleet patterns surfaced | Snowflake Gold layer SQL |
| Churn prediction AUC 0.90 | XGBoost + SHAP |

---

## Tech Stack

**Analytics & BI:**  
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

**Data Modeling & Transformation:**  
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=flat&logo=databricks&logoColor=white)

**Statistical & ML:**  
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat&logo=python&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-FF6B6B?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## Experience

**Research Analyst · iConsult - Syracuse University · Syracuse NY · Jun 2026 – Present**  
Root cause analysis on political advertising datasets · LLM output validation and benchmarking · GxP-aligned data governance · Python and Polars pipelines · cross-platform statistical frameworks

**Data Analytics and Pipeline Engineer · JMA Wireless · Syracuse NY · Aug – Dec 2025**  
ANOVA and Tukey pairwise comparisons across antenna families · Pareto analysis traced 88% of failures to 2 defect categories · $259K annualized capacity recovered · Lean Six Sigma DMAIC framework · stakeholder reporting to VP and Director level

**System Engineer · Tata Consultancy Services · Mumbai · Jul 2022 – Jul 2024**  
SQL analysis across 450M+ financial transactions · 85+ data quality issues diagnosed and resolved · 40% reporting reliability improvement · 50% faster delivery through Python automation · 200+ SQL procedures optimized

---

## Projects

### 🏦 [Retail Banking Customer Analytics Platform](https://github.com/prasadpatil0103/Retail-Banking-Customer-Analytics-Platform)
`SQL` `Python` `R` `AWS Glue` `Redshift` `dbt` `XGBoost` `SHAP` `Power BI` `A/B Testing`

**The question:** Who defaults and why — and what is each customer segment actually worth?

**The answer:** Cash loans default at 8.35% vs revolving at 5.48% (χ²=293.15, p≈0, 95% power). A $34K LTV gap exists between the highest and lowest-value segments across 36 demographic groups. External credit score is the dominant default predictor (SHAP importance: 0.65).

307K loan applications · Churn AUC 0.90 · Credit Risk AUC 0.69 · 100% dbt test pass rate · Power BI dashboard live-connected to Redshift

---

### 💳 [Financial Fraud Detection Analytics](https://github.com/prasadpatil0103/Financial-Fraud-Detection-Analytics-)
`SQL` `Python` `PostgreSQL` `XGBoost` `SHAP` `Feature Engineering` `Statistical Analysis`

**The question:** Where is the fraud concentrated and what transaction patterns predict it?

**The answer:** $3.08M exposed across $79.74M portfolio. Discover card carries 7.7% fraud rate vs 3.2% industry average (χ²=368.90, p≈0). Six engineered features — z-scores and velocity metrics — drive the classification model.

590K transactions · XGBoost AUC 0.81 · SHAP explainability · three high-risk segments identified

---

### 🚚 [Supply Chain Intelligence Platform](https://github.com/prasadpatil0103/Supply-Chain-Intelligence-Platform)
`SQL` `Python` `Prophet` `SARIMA` `Power BI` `dbt` `Snowflake` `Statistical Analysis`

**The question:** Where are deliveries failing and can demand be forecast reliably enough to act on?

**The answer:** 57.3% of late deliveries root-caused to specific regional and seasonal patterns (χ²=41,856, p≈0). $21M revenue at risk identified across 23 regions. Prophet forecasting achieves 0.6% MAPE on 180K orders — reliable enough for operational planning.

SARIMA R²=0.86 · Power BI reporting layer · advanced SQL with LAG, RANK, NTILE

---

### 🏭 [Manufacturing Operations Analytics — Lean Six Sigma DMAIC](https://github.com/prasadpatil0103/Retail-Banking-Customer-Analytics-Platform)
`Python` `R` `ANOVA` `Chi-Square` `Pareto Analysis` `Lean Six Sigma`

**The question:** Why is the first-pass failure rate 47.75% and where are the failures actually coming from?

**The answer:** 88% of failures trace to 2 defect categories — not obvious until clean records were separated from noise and ANOVA with Tukey pairwise comparisons validated significant variance across antenna families. Chamber Capability Matrix built to optimize dispatch routing.

$259K annualized capacity recovered · 75–112 hours monthly testing returned · findings presented to VP and Director level stakeholders

---

### 🛒 [SmartShop — Real-Time E-Commerce Analytics](https://github.com/prasadpatil0103/SmartShop-Analytics)
`Python` `PySpark` `Kafka` `Delta Lake` `dbt` `SQL` `Power BI`

**The question:** What does real-time order data reveal about revenue concentration, delivery performance, and operational anomalies?

**The answer:** $15.42M revenue tracked across 96K+ orders. 97.02% delivery rate with anomalous failure clusters identified in specific product categories. dbt transformation layer produced clean, analysis-ready datasets for business reporting and decision support.

96K+ orders · exactly-once data integrity · real-time anomaly detection · Power BI reporting layer

---

### 🚕 [NYC Taxi Medallion ELT Pipeline — Analytical Insights](https://github.com/prasadpatil0103/NYC-TLC-Data-Pipeline)
`SQL` `Snowflake` `dbt` `Python` `FastAPI` `Airflow`

**The question:** What patterns exist across 5.7M taxi trips — and what do they reveal about fleet performance, fare distribution, and geographic concentration?

**The answer:** Gold layer analytical queries surfaced fare distribution anomalies, trip concentration by borough and hour, and medallion-level performance variance — enabling data-driven insights on fleet allocation and pricing patterns.

5.7M records · Bronze/Silver/Gold medallion architecture · 6 dbt models · daily Airflow DAGs with integrity monitoring · REST API data extraction via FastAPI

---

### 🏥 [Healthcare Hub — Analytics Engineering Platform](https://github.com/prasadpatil0103/ist722dbt/tree/main/Healthcare_DWH)
`dbt` `Snowflake` `SQL` `Power BI` `DAX`

**The question:** How do you build a healthcare reporting layer that clinicians and administrators can actually trust?

**The answer:** Kimball star schema with modular dbt transformations and Power BI DAX dashboards — 50% audit reduction and 3× more maintainable than the previous reporting approach.

984 patients · $8.23M revenue tracked · governance-compliant data definitions

---

### ⚡ [Energy Consumption Analysis](https://github.com/prasadpatil0103/Energy-Consumption-Analysis)
`R` `Random Forest` `KSVM` `AWS S3` `Parquet` `Statistical Modeling`

**The question:** What is the measurable impact of a 5°C temperature increase on household energy consumption?

**The answer:** Random Forest and KSVM models quantified the consumption impact across 800 houses in multi-county South Carolina — translating climate data into actionable energy planning insights.

3 climate datasets · R²=0.62 · Parquet ingestion via R arrow

---

### ✈️ [Airline Delay Prediction](https://github.com/prasadpatil0103/Airline-Delay-Prediction)
`Python` `Random Forest` `Feature Engineering` `NOAA` `DOT`

**The question:** Can weather and seasonal patterns predict airline delays reliably enough to support operational decisions?

**The answer:** DOT flight records merged with 29M NOAA weather observations — after IQR outlier removal and seasonal feature engineering — produced a Random Forest model explaining 62% of delay variance.

650K+ flights · 310K clean records after quality filtering · R²=0.62

---

### 🏈 [Forecasting Fantasy Football with ML](https://github.com/prasadpatil0103/Forecasting-Fantasy-Football-with-Machine-Learning)
`Python` `PySpark` `Gradient Boosting` `Sleeper API` `Parquet`

**The question:** Can historical player performance data produce reliable 2026 PPR projections by position?

**The answer:** Position-specific Gradient Boosting models trained on 79K player-week observations from 2018–2025 — R²=0.489, with projections segmented by position for fantasy decision support.

79K observations · season-partitioned Parquet · Sleeper API ingestion

---

### 🔒 [Crime Detection in Syracuse](https://github.com/prasadpatil0103/Crime-Prediction-Analysis)
`Python` `XGBoost` `Random Forest` `SMOTE` `SARIMA` `Spatio-Temporal Analysis`

**The question:** Where and when does crime concentrate in Syracuse — and can it be predicted reliably?

**The answer:** Spatio-temporal feature engineering with SMOTE class balancing produced 95% classification accuracy. SARIMA time series achieved R²=0.86. Geographic hotspot mapping identified concentration patterns — with ethical AI safeguards documented throughout.

XGBoost + Random Forest · SARIMA R²=0.86 · geographic hotspot mapping

---

### 🔍 [RAG Job Copilot — AI-Powered Job Intelligence](https://github.com/prasadpatil0103/Rag-Job-Copilot)
`Python` `AWS Lambda` `S3` `API Gateway` `TF-IDF` `Streamlit`

**The question:** Can a serverless AI system match job descriptions to candidate skills accurately enough to be useful?

**The answer:** TF-IDF cosine similarity across 30 real job descriptions — role and seniority auto-detected, skill gap analysis surfaced, deployed serverless on AWS.

Serverless AWS deployment · real-time skill matching · Streamlit dashboard

---

## Education

🎓 **M.S. Applied Data Science** — Syracuse University · GPA 3.9 · May 2026  
🎓 **B.E. Information Technology** — University of Mumbai · GPA 3.8

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ppatil--in-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/ppatil-in/)
[![Portfolio](https://img.shields.io/badge/Portfolio-prasadpatil0103.github.io-6366f1?style=flat&logo=google-chrome)](https://prasadpatil0103.github.io)
[![Email](https://img.shields.io/badge/Email-prasad.patil.ds%40gmail.com-D14836?style=flat&logo=gmail)](mailto:prasad.patil.ds@gmail.com)

---

<details>
<summary>📊 GitHub Stats</summary>
<br>
<img src="https://github-readme-stats.vercel.app/api?username=prasadpatil0103&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=86400" height="160"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=prasadpatil0103&layout=compact&theme=tokyonight&hide_border=true&cache_seconds=86400" height="160"/>
</details>