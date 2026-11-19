---
title: "External Validation of Machine Learning Models Predicting Osteoradionecrosis After Mandibular Fibula Free Flap Reconstruction and Radiotherapy for Oral Cancer"
collection: publications
category: inreview
permalink: /manuscripts/osteoradionecrosis-external-validation
excerpt: 'External validation of machine learning models for predicting osteoradionecrosis following mandibular reconstruction and radiotherapy.'
#date: 2026-11-15 # TODO: fill-in for formatting
#venue: 'Manuscript in review'
#citation: 'Nimbalkar A, Matar DY, <strong><u>Matar AY</u></strong>, Lee JJ, Szymkiewicz V, Yogaratnam A, Pillai M, Alsamman B, Gao S, Yu J, Panayi AC, Kao HK, Elhelali A. External Validation of Machine Learning Models Predicting Osteoradionecrosis After Mandibular Fibula Free Flap Reconstruction and Radiotherapy for Oral Cancer. Manuscript under review.'
---

**Under review--**this manuscript has not yet been published.

## Overview

This study evaluates how well models developed in one cohort perform in predicting osteoradionecrosis (ORN) in another, geographically external, cohort. Building on a [a previous study](/manuscripts/ORN) investigating the utility of ML models above logistic regression, seven models (LR, LightGBM, XGB, KNN, SVC, NN, and Stack) were tuned and trained in a 275-patient Taiwanese cohort (Chang Gung Memorial Hospital) and evaluated in a 30-patient U.S. cohort (Johns Hopkins). Additionally, predictions were extended to three risk strata (Low, Moderate, High) to make output more clinically interpretable. LR achieved the highest external AUROC (0.804), while SVC showed increasing observed event rates across risk tiers, although interpretation was limited by the small external sample size.

## Links
- Project code:
    - [Updated model development in Taiwanese cohort](https://github.com/AnthonyMatarr/ML-ORN-Pred-update)
    - [Evaluation in U.S. cohort](https://github.com/AnthonyMatarr/ML-ORN-Validation)