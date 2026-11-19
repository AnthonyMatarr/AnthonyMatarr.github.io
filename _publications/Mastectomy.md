---
title: "Development of Interpretable Machine Learning Models for Predicting Complications After Breast Cancer Surgery"
collection: publications
category: inprep
permalink: /publications/mastectomy
excerpt: 'Awaiting the latest 2025 ACS-NSQIP release for temporal & external benchmarking'
#date: 2026-02-01 #will have "published in..." if date is included
#venue: 'Under review'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
#paperurl: 'https://academicpages.github.io/files/paper2.pdf'
#citation: ''
---
- Performed preliminary investigation of how feature set, data coverage (years included), and cohort homogeneity (cancer vs all patients) affected the feasibility of predicting 11 complications after breast surgery 

- Selected a ~365,000-patient breast cancer cohort (2014-2024) from an original cohort of >13M patients (2008-2024) in the [ACS-NSQIP](https://www.facs.org/quality-programs/data-and-registries/acs-nsqip/), engineered features from CPT/ICD codes, and developed five model families (*Logistic regression, XGBoost, LightGBM, Neural network*, and *Stacked ensemble*) across 11 candidate outcomes

- Based on preliminary predictive performance and risk group separation, selected models for four outcomes (*Any complication, Serious complications, Surgical site infection*, and *Unplanned reoperation*) for deployment to [PRO‑Breast](/portfolio/pro-breast)

- Models currently being redeveloped, awaiting the latest 2025 ACS-NSQIP release for temporal & external benchmarking on the [ACS-NSQIP risk calculator](https://riskcalculator.facs.org/RiskCalculator/)