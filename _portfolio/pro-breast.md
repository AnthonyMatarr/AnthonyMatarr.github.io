---
title: "PRO-BREAST"
excerpt: "Post-resection and Reconstruction outcome prediction for disease-directed Breast surgery<br/><img src='/images/pro_breast.png'>"
collection: portfolio
---
The interface can be found [here](https://pro-breast.streamlit.app){:target="_blank" rel="noopener"}.

As part of my work for this [manuscript](/publication/mastectomy) developed alongside collaborators from Johns Hopkins Medical School, I built an interactive risk calculator that allows clinicians to estimate risk of 30-day postoperative complications (Surgical/Medical complications, Mortality, Unplanned Reoperation, & Venous Thromboembolism) after breast surgery. The tool uses calibrated gradient-boosted tree models (XGBoost/LightGBM) trained/validated on 737,730 patients from the ACS-NSQIP dataset (2008–2024).

Key Features
------

- **Actionable Risk Stratification:** Instead of solely relying on raw probabilities, predictions are mapped to clinically meaningful risk groups (Very Low, Low, Medium, High) using logarithmically spaced thresholds derived from the development data.

- **Transparent Baselines:** Each risk group is presented alongside its observed event rate and probability thresholds, providing context relative to the overall population. Raw probability outputs are also shown with percentile rankings.

- **Interpretable "Black Box" Models:** To demystify the predictions, the tool visualizes individual feature contributions using regularized SHAP (Shapley Additive exPlanations) values. This interactive plot shows exactly which factors pushed a patient's risk up or down relative to the baseline.

- **Robustness to Missing Data:** Numerical inputs can be marked as unknown/NA and are automatically imputed, with all imputed values explicitly flagged for transparency.
