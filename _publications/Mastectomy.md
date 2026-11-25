---
title: "Development of Interpretable Machine Learning Models for Predicting Complications After Breast Cancer Surgery"
collection: publications
category: inprep
permalink: /publications/mastectomy
excerpt: 'Development and temporal evaluation of interpretable risk prediction models for major complications after breast cancer surgery.'
#date: 2026-02-01 #will have "published in..." if date is included
#venue: 'Under review'
#citation: ''
links:
  - label: 'Code'
    url: 'https://github.com/AnthonyMatarr/ML-Breast-Pred'
  - label: 'PRO-Breast (Risk Calculator)'
    url: '/portfolio/pro-breast'
  - label: 'ACS-NSQIP data registry'
    url: 'https://www.facs.org/quality-programs/data-and-registries/acs-nsqip/'
    detail_only: true
  - label: 'ACS-NSQIP Surgical Risk Calculator'
    url: 'https://riskcalculator.facs.org/RiskCalculator/'
    detail_only: true
---

**Manuscript in preparation**

## Overview

Preliminary analyses examined how feature selection, temporal data coverage, and cohort composition affected predictive performance across 11 candidate outcomes. These analyses informed the selection of a cohort of approximately 365,000 patients undergoing breast cancer surgery between 2014 and 2024 from more than 13 million ACS-NSQIP surgical records.

We evaluated five model families (logistic regression, XGBoost, LightGBM, neural networks, and stacked ensembles), with particular emphasis on clinically meaningful risk stratification. Preliminary results informed the selection of models for four outcomes: any complication, serious complications, surgical site infection, and unplanned reoperation.

Preliminary models are accessible through [PRO-Breast](/portfolio/pro-breast). Further model development, temporal validation using 2025 ACS-NSQIP data, and benchmarking against the ACS-NSQIP Surgical Risk Calculator are planned.

## My Contribution

I lead the technical development of this project, from investigating how cohort composition and feature availability affect predictive performance to constructing the modeling and evaluation pipelines. I also developed the accompanying web-based risk calculator.
