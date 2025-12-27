# 👨‍💻 Anthony Inzinna | Technical Research & Code Archive

**M.S. Data Science (Candidate) | Python & R Developer**

This profile serves as the source code repository for my applied research in behavioral analytics and algorithmic forecasting. Unlike my business portfolio, this archive focuses on the **raw implementation logic**, reproducibility, and statistical methodologies used in my modeling work.

---

## 📂 Repository Index & Technical Stacks

### 1. [GA4 Forensic Traffic Analysis](https://github.com/anthonyinzinna/ga4-forensic-traffic-analysis) (New)
* **Stack:** SQL (BigQuery), Looker Studio, Regex
* **Implementation:** Engineered a heuristic identity resolution pipeline to filter bot/developer traffic from raw GA4 event streams.
* **Logic:** Utilized `UNNEST` and Window Functions to reconstruct session-scoped engagement metrics, distinguishing "0-second" headless browsers from high-value recruitment leads (LinkedIn/GitHub).
* **Key Function:** Identity Logic that flags visitors based on geo-behavioral fingerprints.

### 2. [People Analytics: Behavioral Drivers](https://github.com/anthonyinzinna/People-Analytics-Behavioral-Drivers)
* **Stack:** Python, Scikit-Learn, XGBoost, SHAP
* **Implementation:** Developed a classification pipeline using `scale_pos_weight` to handle class imbalance in HR data.
* **Logic:** Replaced standard black-box predictions with SHAP (SHapley Additive exPlanations) waterfall plots to quantify individual turnover risk factors.
* **Key Function:** Optimized precision-recall thresholds to improve minority class detection (attrition) from 34% to 61%.

### 3. [Supply Chain Demand Forecasting](https://github.com/anthonyinzinna/Retail-Inventory-Forecasting-Prophet)
* **Stack:** Python, Facebook Prophet, Pandas
* **Implementation:** Time-series decomposition model separating growth trends from weekly/yearly seasonality.
* **Logic:** Calculated dynamic "Safety Stock" levels using 95% confidence interval upper bounds rather than static averages.
* **Outcome:** Generated risk-adjusted procurement algorithms to minimize stockout probabilities during high-variance periods.

### 4. [Geospatial Visualization Pipeline](https://github.com/anthonyinzinna/Data_Viz_Urban_Growth)
* **Stack:** R, Magick, Tmap
* **Implementation:** Custom "Manual Device" rendering pipeline to bypass standard library limitations on ARM64 architectures.
* **Logic:** Script generates individual PNG frames for urban density evolution (1950–2030) and stitches them using the Magick image processing engine.
* **Feature:** Hardware-agnostic rendering loop for high-resolution time-lapse generation.

### 5. [Mobile Game A/B Testing](https://github.com/anthonyinzinna/Mobile-Game-Retention-AB-Test)
* **Stack:** Python, SciPy, Statistical Hypothesis Testing
* **Implementation:** Rigorous evaluation of gameplay gate mechanics (Level 30 vs Level 40).
* **Logic:** Applied statistical significance testing (p-value analysis) to measure impacts on 1-Day vs 7-Day retention rates.
* **Result:** Quantified the negative impact of delayed friction points on long-term user habituation.

---

## 🛠️ Languages & Tools
`Python` `R` `SQL` `BigQuery` `Tableau` `Looker Studio` `Git`

---

## 🔗 External References
* **Full Case Studies & Business Impact:** [View Portfolio](https://sites.google.com/view/anthony-inzinna-data/)
* **Professional Network:** [LinkedIn Profile](https://www.linkedin.com/in/anthonyinzinna/)
* **Verified Credentials:** [Merit Page](https://meritpages.com/anthonyinzinna)
