# Borehole-Failure-Prediction-Analysis-using-Artificial-Neural-Network-ANN-Model
A comprehensive machine learning project for predicting borehole failures and analyzing maintenance patterns using Artificial Neural Networks (ANNs). This repository contains two complementary notebooks that work together to provide both exploratory data analysis and predictive modeling capabilities.

🔍 Overview
Boreholes are critical water infrastructure, and unexpected failures can cause significant downtime and repair costs. This project leverages real field survey data from 103 boreholes to:

- Analyze maintenance patterns, fault types, energy sources, and cost relationships
- Predict the probability of borehole failure using a deep Artificial Neural Network
- Provide actionable insights through 9 diagnostic visualizations
- The ANN model achieves a ROC-AUC of 0.99 on the test set, demonstrating excellent discriminative ability for identifying at-risk boreholes.

🎯 Key Features
- End-to-end pipeline from raw survey data to deployment-ready predictions
- Strong regularization (L2, Dropout, BatchNormalization) to prevent overfitting on small dataset
- Class imbalance handling via balanced class weights
- Comprehensive evaluation with multiple metrics and diagnostic plots
- Feature engineering tailored to domain knowledge (maintenance ratio, pump stress, fault history)
- Reproducible with fixed random seed (SEED = 42)

📈 Results
Test Set Performance
- Metric	Score
- ROC-AUC	0.9898 ✅
- Accuracy	95.24%
- Precision	0.9333
Recall	1.0000
F1-Score	0.9655
