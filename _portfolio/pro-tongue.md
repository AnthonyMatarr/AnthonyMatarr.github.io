---
title: "PRO-TONGUE"
excerpt: "Postoperative outcome prediction tool after glossectomy<br/><img src='/images/pro_tongue.png'>"
collection: portfolio
---
The interface can be found [here](https://pro-tongue.streamlit.app){:target="_blank" rel="noopener"}.

As part of my work for this [manuscript](/publication/glossectomy), developed alongside collaborators from Johns Hopkins Medical School, I built an interactive tool to predict 30-day postoperative complications (Aspiration/Surgical-related, & Unplanned Reoperation) following glossectomy (tongue cancer surgery). It leverages multiple calibrated model architectures—including Logistic Regression, LightGBM, and Support Vector Classifiers—trained on 8,266 patients from the ACS‑NSQIP dataset (2008–2024).


Key Features
-------
- **Clinically Relevant Stratification:** Predictions are converted into actionable risk tiers (Very Low, Low, Medium, High) using logarithmic thresholds, helping clinicians quickly assess patient acuity.

- **Contextualized Performance:** The tool displays observed event rates and probability thresholds for each risk bin, plus the patient’s predicted risk percentile in the test cohort (overall, positive cases, and negative cases).

- **Explainable Predictions:** To counter the "black box" problem, individual feature contributions are visualized using regularized SHAP values. This allows users to see exactly how specific clinical factors influence the risk estimate relative to baseline.

- **Handling Missing Data:** The system robustly handles missing numerical values via imputation, explicitly flagging any imputed fields to maintain transparency in the clinical decision process.