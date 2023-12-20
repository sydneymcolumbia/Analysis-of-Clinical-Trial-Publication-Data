# Analysis-of-Clinical-Trial-Publication-Data
Analysis of Clinical Trial Publication Data from the ISLR2 R Package

Overview

This project focused on the analysis of the Publication dataset from the ISLR2 R package, which contains data on 244 clinical trials funded by the National Heart, Lung, and Blood Institute. The dataset details the time to publication for the results of these clinical trials.

Objectives & Methods

The project was structured to cover various aspects of survival analysis:

Data Loading: The Publication dataset was loaded into R for examination and analysis.
Observation and Censorship Analysis: The number of clinical trials where the time to publication was observed and the number where it was censored were calculated.

Kaplan-Meier Estimator Plotting: A Kaplan-Meier estimator for the time to publication of all clinical trials was produced and plotted, including 99% pointwise confidence bands.

Subgroup Analysis with Kaplan-Meier Estimator: Kaplan-Meier estimators for time to publication were plotted for two subgroups based on the 'posres' variable (clinical trials with positive findings vs. those without). The log-rank test was employed to examine if the time to publication was associated with the outcome of the clinical trials.

Cox Proportional Hazards Model Fitting: A Cox proportional hazards model was fitted using predictors such as 'posres', 'multi', 'clinend', and 'budget'. The model summary was produced.

Model Evaluation: The global likelihood ratio, Wald, and score tests were used to determine if the Cox model was better than a model with no predictors.

Predictor Effect Interpretation: The estimated effect of each predictor on the hazard function for the time to publication was interpreted.

Survival Function Estimation and Plotting: Using the estimates from the Cox model, the baseline survival function S0 and the survival functions for clinical trials with specific predictor values were plotted. These functions helped compare the likelihood of publication timing for two hypothetical clinical trials with different sets of predictor values.
Deliverables

The project concluded with a comprehensive report summarizing the findings from each stage of the analysis. The report provided insights into the factors affecting the time to publication of clinical trials and how different variables influenced these timelines. By employing survival analysis techniques, the project offered a nuanced understanding of publication dynamics in clinical research, highlighting the practical application of statistical methods in real-world scenarios.
