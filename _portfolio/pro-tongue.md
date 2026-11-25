---
title: "PRO-TONGUE"
excerpt: "Interpretable risk calculator for six major 30-day complications following tongue cancer surgery.<br/><img src='/images/pro_tongue.png' alt='PRO-Tongue risk calculator interface' style='width:70%; max-width:100%; height:auto;'>"
collection: portfolio
order: 1
---
[Launch PRO-Tongue <i class="fas fa-arrow-up-right-from-square" aria-hidden="true"></i>](https://pro-tongue.streamlit.app){: .btn .btn--inverse target="_blank" rel="noopener"}

<img src="/images/pro_tongue.png" alt="PRO-Tongue risk calculator interface" style="width:85%; max-width:100%; height:auto; display:block; margin:1em auto;">

## Overview 

As part of [our published study](/publications/tongue), I developed an interactive risk calculator for six major 30-day postoperative complications following glossectomy for tongue cancer:

- Any complication
- Serious complications
- Unplanned reoperation
- Surgical site infection
- Pneumonia
- Bleeding requiring transfusion

The calculator uses calibrated gradient-boosted tree models (LightGBM and XGBoost) developed using approximately 7,500 patients (2008–2023) and temporally evaluated on approximately 730 patients (2024) from the ACS-NSQIP data registry. The models were selected based on performance in the test set, with particular emphasis on risk stratification to support clinically interpretable, individualized risk estimation.

## Key Features

- **Interpretable Risk Stratification:** Predicted probabilities are mapped to four risk groups (Very Low, Low, Moderate, and High) using logarithmically spaced probability thresholds derived from the development data.

- **Contextualized Risk Estimates:** Each risk group is presented alongside its observed event rate and probability thresholds, providing context relative to the study population. Individual predicted probabilities are also contextualized through percentile rankings.

- **Individualized Model Explanations:** Interactive visualizations of regularized SHAP (Shapley Additive exPlanations) values illustrate how individual input features contribute to the model's predicted risk relative to its baseline.

- **Transparent Handling of Missing Data:** Missing numerical inputs are automatically imputed, with imputed values explicitly flagged and displayed to help users interpret predictions in light of the available information.

## Limitations

Although the models have been temporally evaluated, model selection was informed by performance on the temporal test cohort. Further independent validation is needed to assess the reliability and generalizability of the selected models across clinical settings. The calculator is intended to support, rather than replace, clinical judgment.

## Links

- [Risk calculator](https://pro-tongue.streamlit.app)
- [Associated publication](/publications/tongue)
- [Project code](https://github.com/AnthonyMatarr/ML-Tongue-Pred)