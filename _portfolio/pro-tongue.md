---
title: "PRO-TONGUE"
excerpt: "Postoperative outcome prediction tool after glossectomy in tongue cancer patients<br/><img src='/images/pro_tongue.png'>"
collection: portfolio
---
The interface can be found [here](https://pro-tongue.streamlit.app){:target="_blank" rel="noopener"}.

As part of my work for this [manuscript](/publication/tongue), developed alongside collaborators from John Hopkins University, Brigham and Women's Hospital Harvard Medical School, University Hospital of Zürich, and Heidelberg University, I built an interactive tool to predict 30-day postoperative complications (comprehensive any/serious complications, unplanned reoperation, surgical site infection, pneumonia, and bleeding transfusion) following glossectomy for tongue cancer. It leverages tree-based calibrated model architectures—including LightGBM and XGBoost—trained and temporally validated on patients from the ACS‑NSQIP dataset from 2008–2024.


Key Features
-------
- **Clinically Relevant Stratification:** Predictions are converted into actionable risk tiers (Very Low, Low, Medium, High) using logarithmic thresholds, helping clinicians quickly assess patient acuity.

- **Contextualized Performance:** The tool displays observed event rates and probability thresholds for each risk bin, plus the patient’s predicted risk percentile in the test cohort (overall, positive cases, and negative cases).

- **Explainable Predictions:** To counter the "black box" problem, individual feature contributions are visualized using regularized SHAP values. This allows users to see exactly how specific clinical factors influence the risk estimate relative to baseline.

- **Handling Missing Data:** The system robustly handles missing numerical values via imputation, explicitly flagging any imputed fields to maintain transparency in the clinical decision process.