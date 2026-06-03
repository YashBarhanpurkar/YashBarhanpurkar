<div align="center">

## Yash Barhanpurkar

**M.Sc. Global Production Engineering · TU Berlin**

Bridging physical production systems and digital process optimization — building data pipelines, ML classifiers, and analytics tools for industrial manufacturing problems.

`Python` `SQL` `Power BI` `Scikit-learn` `OpenCV` `ETL` `Lean Six Sigma`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yash-barhanpurkar/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/YashBarhanpurkar)

📍 Berlin, Germany &nbsp;·&nbsp; 🇬🇧 English C1 &nbsp;·&nbsp; 🇩🇪 German A2 (actively improving)

</div>

---

## About

Industrial/production engineer working at the intersection of **shopfloor digitalization**, **predictive maintenance**, and **supply chain data engineering**.

Background: 1.4 years as Systems Engineer at Tata Consultancy Services (enterprise operations, incident response, SOP execution) · B.E. Mechanical Engineering, University of Mumbai · Currently M.Sc. at TU Berlin building data-driven tools for real industrial production problems.

Open to **Werkstudent roles** in Production Analytics · Shopfloor Digitalization · Smart Maintenance · Industry 4.0 · Digital Factory

---

## Projects

### [Industrial Supply Chain — Automated ETL Pipeline & BI Dashboard](https://github.com/YashBarhanpurkar/supply-chain-analytics-dashboard)
> Config-driven Python ETL framework that ingests 180,000+ rows of multilingual logistics data, normalizes it into a 7-table Star Schema SQLite database, and powers a Power BI operational dashboard for delivery performance analysis.

**What makes it non-trivial:** Zero hardcoded logic — all schemas, paths, and mapping rules live in `settings.json`. Quarantine-not-crash validation isolates corrupt rows without stopping the run. Composite Geography Key synthesized from multi-source location strings to prevent join failures. Fact tables split by analytical purpose (logistics vs. financial) to avoid many-to-many traps.

`Python` `Pandas` `SQLite` `SQLAlchemy` `ETL` `Power BI` `DAX` `Star Schema` `Data Warehousing`

---

### [Automated Visual Inspection System — Computer Vision QC](https://github.com/YashBarhanpurkar/cookie-inspection)
> Computer vision pipeline simulating an Industrie 4.0 automated optical inspection station. Segments products from conveyor background, classifies variants by texture signature, and enforces ingredient distribution thresholds with automated Accept/Reject logic.

**What makes it non-trivial:** Dual-channel edge detection — Canny runs on both grayscale AND HSV saturation channels simultaneously, fused via bitwise OR. Captures brightness-defined AND colour-defined edges, outperforming single-channel detection on low-contrast products. GLCM texture features (Contrast, Homogeneity, Entropy) for product classification; Otsu thresholding on the saturation channel for ingredient ratio quantification.

`Python` `OpenCV` `scikit-image` `NumPy` `SciPy` `GLCM` `Otsu Thresholding` `HSV Segmentation`

---

### [Industrial Failure Diagnostics & Condition Monitoring](https://github.com/YashBarhanpurkar/Industrial_Failure_Diagnostics_and_Condition_Monitoring)
> Diagnostic analytics pipeline on 10,000 machine sensor cycles (AI4I 2020). Identifies the failure fingerprint — the high-torque/low-speed operating zone where failure probability spikes — and builds a Random Forest classifier to flag machines entering that zone before downtime occurs.

**What makes it non-trivial:** The thermal hypothesis (process temperature as primary failure driver) is disproven by the data — only 0.3K delta between healthy and failed machines. Torque is the dominant driver at +26% in failed units. Class imbalance (97:3) handled explicitly; model optimized on F1-Score rather than accuracy to balance false alarm rate against failure capture rate.

`Python` `Scikit-learn` `Random Forest` `GridSearchCV` `Pandas` `Matplotlib` `Seaborn`

---

### [Manufacturing KPI Dashboard — Power BI Analytics](https://github.com/YashBarhanpurkar/Adventure_Works_BI_Analytics)
> Production-grade Power BI solution on the AdventureWorks manufacturing dataset. Star schema data model, advanced DAX measures, and a multi-page dashboard covering $24.9M revenue across 6 global markets.

**What makes it non-trivial:** Cyclic relationship in the product hierarchy (Category → Subcategory → Product) resolved by restructuring the relationship chain — not ignored. Folder Path Parameter makes the report portable across machines without manual table re-pointing. DAX: rolling 90-day revenue, YTD comparisons, What-If price adjustment parameter, return rate by SKU.

`Power BI` `DAX` `Star Schema` `Power Query (M)` `Data Modelling`

---

## Technical Skills

**Data & Programming**
Python (Pandas, NumPy, Scikit-learn, OpenCV, scikit-image) · SQL (SQLite, MySQL) · ETL pipeline development · Data modelling (Star Schema, relational DB design) · Git

**Machine Learning & Computer Vision**
Random Forest · Decision Trees · GridSearchCV hyperparameter tuning · GLCM texture features · Otsu thresholding · HSV colour segmentation · Class imbalance handling

**BI & Visualisation**
Power BI (DAX, Power Query) · Matplotlib · Seaborn

**Engineering & Quality**
Lean Six Sigma (Yellow Belt · Green Belt in progress via TU Berlin QM coursework) · DMAIC · FMEA · SPC · QFD · PDCA · OEE · Root Cause Analysis

**Manufacturing & CAD**
DfAM · FDM additive manufacturing (Bambu Lab, Ultimaker, Creality) · SolidWorks · CATIA · Siemens NX · Autodesk Fusion 360

---

## Education

**M.Sc. Global Production Engineering** — Technische Universität Berlin *(Oct 2025 – Aug 2027)*
Digitalization & AI in Automation · Quality Management (DMAIC, Six Sigma) · Production Technology · Supply Chain Management · Lean Management

**B.E. Mechanical Engineering** — University of Mumbai *(Aug 2019 – Mar 2023)*

---

<div align="center">
  <sub>Open to Werkstudent roles in Berlin/Brandenburg — Production Analytics · Shopfloor Digitalization · Smart Maintenance · Industry 4.0</sub>
</div>
