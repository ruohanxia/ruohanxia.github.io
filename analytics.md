---
layout: default 
title: "Data Analytics"
permalink: /analytics
---

## About My Data & Analytic Approach
I’m a quantitative researcher who approaches analytics as a tool for solving real-world problems. I work across R, SQL, MATLAB, and Python to clean, structure, and analyze complex datasets, selecting methods based on the question at hand rather than the tool itself. My experience spans advanced statistical modeling—including linear mixed-effects models, structural equation models, and time-series analysis—as well as building reproducible analytic pipelines and translating results into clear, actionable insights. 

The projects below reflect my approach to analytics: thoughtful problem framing, careful method selection, and transparent, reproducible analysis.

## Flagship Projects
### 1. Modeling Caregiver Emotionality And Infant Neural Responses 
*Problem* 

How do caregiver characteristics shape infants' neural responses to emotional cues - and how can we model these effects reliably in <u>noisy, longitudinal</u> data? 

*Why this matters*

Real-world analytics often involve noisy data and incomplete observations. Such important variability calls for careful consideration in data handling and model selection to yield unbiased, accurate results. This project demonstrates how to build, evaluate, and defend analytical pipelines under these constrains - balancing data quality, sample size, statsitical rigor, and interpretability to produce insights that stakeholders can trust. 

*Context*

I analyzed multi-session EEG and interactive behavioral data from infants and caregivers to understand how environmental factors relate to early neural markers of emotion processing. The dataset included repeated measures, variable data quality, different pattern of missingness, and multiple sources of individual-level variability. 

*Analytics Focus*
- Built reproducible preprocessing pipelines for EEG-derived features
- Cleaned and merged longitudinal behavioral and neural datasets
- Modeled nested data structures using multilevel models
- Conducted robustness checks across preprocessing thresholds and model specifications

*Key Insights* 
- Caregiver emotionality was systematically associated with infants' baseline neural activity as well as neural responses to emotional stimuli
- Accounting for within-subject variability substaintially improved model stability and interpretability
- Analytic decisions (e.g., preprocessing thresholds) meaningfully impacted downstream inferences, highlighting importance of transparent, reproducible pipelines

*Tools*
- R (dplyr, tidyverse, lme4, emmeans, ggplot2)
- MATLAB (EEGLAB, ERPLAB, EP Toolkit)
- Python (Pandas, NumPy) 

[View full analytic code on GitHub](INSERT LINK HERE LATER)

### 2. Pediatric Developmental Outcomes

### 3. Treatment Response & Safety Signals in Pediatric Populations

### 4. Digtal Health Engagement & Retention 
