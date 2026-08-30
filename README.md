# Rupak Ganvir

SWE + ML · IIT Kanpur (M.Tech Geoinformatics) · Ex-SWE · B.Tech CSE  
Open to **Software Engineering**, **ML Engineering**, and **Data Science** roles.

---

## Projects

**[DocuMind](https://github.com/RupakGanvir/DocuMind)** — production-grade RAG service  
Two-stage retrieval: dense search (ChromaDB) fused with BM25 via Reciprocal Rank Fusion, then a cross-encoder reranker on top. Eval harness scores retrieval and generation separately — faithfulness, context precision/recall, answer relevancy, ROUGE-L.  
82 tests, Dockerized, CI via GitHub Actions.  
`Python` `FastAPI` `ChromaDB` `Docker` `GitHub Actions`

**[Fraud Detection System](https://github.com/RupakGanvir/fraud-detection-system)** — IEEE-CIS dataset, 590K+ transactions  
Built Logistic Regression from scratch in NumPy, then pushed it further with XGBoost + SMOTE.  
Went from **0.784 → 0.904 AUC-ROC**. Deployed a FastAPI scoring service with Folium fraud heatmaps.  
`Python` `XGBoost` `SMOTE` `Scikit-learn` `FastAPI` `NumPy` `Pandas`

**[RetailPulse](https://github.com/RupakGanvir/retail-analytics-pipeline)** — SQL/BI analytics pipeline  
DuckDB warehouse built on staging + mart layers (CTEs, window functions), a pytest data-quality suite, and a Streamlit dashboard. The headline recommendation is backed by a Welch's t-test on channel LTV, not a raw average.  
`SQL` `DuckDB` `Streamlit` `Plotly`

**[CausalLens](https://github.com/RupakGanvir/CausalLens)** — A/B testing & experiment design toolkit  
Power analysis, CUPED variance reduction, sample-ratio-mismatch diagnostics, BH-corrected segment testing.  
`Python` `Statistics` `Causal Inference`

**[T20 Cricket Simulator](https://github.com/RupakGanvir/monte-carlo-t20-simulation)** — Monte Carlo match engine  
Ball-by-ball probabilistic simulation for T20 outcomes. Team strength modeling, tournament analysis.  
`Python` `Probability` `Statistics`

**[LiDAR Quality Assessment](https://github.com/RupakGanvir/LiDAR-Quality-Assessment)** — Aerial LiDAR over IIT Kanpur campus  
6.45M points, assessed against 8 USGS/ASPRS accuracy and completeness metrics.  
`Python` `LiDAR` `Point Clouds`


---

## Stack

```
Languages   Python · C++ · JavaScript · SQL
ML          NumPy · Pandas · Scikit-learn · XGBoost
Dev         React · Node.js · FastAPI · REST APIs · Docker
Geo         QGIS · Google Earth Engine · GNSS
```

---

## Experience

**Software Engineer** @ ASP OL Media *(Apr 2024 – Oct 2024)*  
Built React/HTML/CSS frontends for a multi-campaign email automation platform serving millions.  
Engineered an SMTP delivery pipeline — cut delivery failures by 20% through server health monitoring.

**Frontend Developer Intern** @ DevKalp Technologies *(Apr 2023 – June 2023)*  
Hospital management dashboard (React + Tailwind) for 500+ patients — shipped to production.  
Built responsive UI for 2 e-commerce clients in a 4-member agile team.

---

## A Few Other Things

- CodeChef ⭐⭐⭐ · 425+ LeetCode problems (C++, medium/hard focus)
- Two published papers — blockchain-based pharma fraud detection (IJARIIE & IJRPR, 2023)
- B.Tech Computer Science and Engineering (2019–2023)
