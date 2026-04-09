# Startup Success Predictor

Predicting Startup Success
A supervised machine learning project that predicts whether a startup will be acquired (success) or closed (failure) based on funding history and company profile data from Crunchbase.

Overview
Startup investment is inherently risky — 90% of startups fail due to poor product-market fit, marketing issues, or team problems. This project aims to help investors and founders make more informed decisions by predicting startup success using historical funding data and machine learning.

Problem Statement
To identify the key features that drive startup success and build a classification model that can predict whether a startup will be acquired or shut down, using publicly available Crunchbase investment data.

Dataset
Source: Crunchbase Startup Investments — Kaggle
Size: 54,294 rows × 39 columns
Target Variable: status — acquired, operating, or closed

Results
Best Model: Random Forest (Binary Classification)

Metric Score: Accuracy~69%
The model predicts 0 = closed (failed) and 1 = acquired (succeeded).

Key Features
Based on the analysis, the three most important factors for startup success were:
Industry — the market sector the startup operates in
Continent — geographic region significantly influences acquisition likelihood
Total investment — higher funding tiers strongly correlated with acquisition
