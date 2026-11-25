---
title: "External Validation of Machine Learning Models Predicting Osteoradionecrosis After Mandibular Fibula Free Flap Reconstruction and Radiotherapy for Oral Cancer"
collection: publications
category: inreview
permalink: /publications/osteoradionecrosis-external-validation
excerpt: 'External validation of machine learning models for predicting osteoradionecrosis following mandibular reconstruction and radiotherapy.'
#date: 2026-11-15 # TODO: fill-in for formatting
#venue: 'Manuscript in review'
#citation: 'Nimbalkar A, Matar DY, <strong><u>Matar AY</u></strong>, Lee JJ, Szymkiewicz V, Yogaratnam A, Pillai M, Alsamman B, Gao S, Yu J, Panayi AC, Kao HK, Elhelali A. External Validation of Machine Learning Models Predicting Osteoradionecrosis After Mandibular Fibula Free Flap Reconstruction and Radiotherapy for Oral Cancer. Manuscript under review.'
authors_short: 'Nimbalkar A, Matar DY, <strong><u>Matar AY</u></strong>, et al.'
links:
  - label: 'Code: development'
    url: 'https://github.com/AnthonyMatarr/ML-ORN-Pred-update'
  - label: 'Code: external validation'
    url: 'https://github.com/AnthonyMatarr/ML-ORN-Validation'
---

**Manuscript under review**

## Overview

This study investigates the geographic transferability of machine learning models for predicting osteoradionecrosis (ORN) following mandibular reconstruction and radiotherapy.

Building on [our previous study](/publications/ORN), seven predictive models were developed using a Taiwanese cohort of 275 patients from Chang Gung Memorial Hospital and externally evaluated using an independent cohort of 30 patients from Johns Hopkins. The models included logistic regression, LightGBM, XGBoost, k-nearest neighbors, support vector classification, neural networks, and stacked ensembles. Predictions were also used to stratify patients into low-, moderate-, and high-risk groups to support clinical interpretation.

Logistic regression achieved the highest external AUROC (0.804), while risk groups derived from the support vector classifier showed a monotonic increase in observed event rates. Although interpretation is limited by the small external sample size, these findings illustrate how conclusions about model performance may differ depending on the evaluation criterion.

## My Contribution

I redeveloped the predictive models using the original Taiwanese cohort, implemented their evaluation on the independent U.S. cohort, and extended the evaluation framework to assess three-tier risk stratification.
