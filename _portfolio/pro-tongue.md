---
title: "PRO-TONGUE"
excerpt: "Postoperative outcome prediction tool after glossectomy in tongue cancer patients<br/><img src='/images/pro_tongue.png' style='width:70%;'>"
collection: portfolio
order: 1
---
The interface can be found [here](https://pro-tongue.streamlit.app){:target="_blank" rel="noopener"}.

As part of my work for this [manuscript](/publications/tongue), developed alongside collaborators from Johns Hopkins University, Brigham and Women's Hospital Harvard Medical School, University Hospital of Zürich, and Heidelberg University, I built an interactive tool to predict 30-day postoperative complications (*Any complication, Serious complications, Unplanned reoperation, Surgical site infection, Pneumonia*, and *Bleeding requiring transfusion*) following glossectomy for tongue cancer. It leverages calibrated tree-based model architectures—including LightGBM and XGBoost—developed (2008-2023) and temporally validated (2024) on patients from the ACS‑NSQIP dataset.


Key Features
-------
- **Clinically Relevant Stratification:** Predictions are converted into actionable risk tiers (Very Low, Low, Medium, High) using logarithmic thresholds, helping clinicians quickly assess patient acuity.

- **Contextualized Performance:** The tool displays observed event rates and probability thresholds for each risk bin, plus the patient’s predicted risk percentile in the test cohort (overall, positive cases, and negative cases).

- **Explainable Predictions:** To counter the "black box" problem, individual feature contributions are visualized using regularized SHAP values. This allows users to see how specific clinical factors influence an inputted patient's risk estimate relative to baseline.

- **Handling Missing Data:** The system handles missing numerical values via imputation, explicitly flagging any imputed fields to maintain transparency in the clinical decision process.