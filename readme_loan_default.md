**Mortgage Default Probability Prediction**

This project aims to predict the probability of default (PD) for borrowers using FICO scores. FICO scores, which range from 300 to 850, are a standardized credit score used in 90% of mortgage application decisions in the United States. The task is to construct a technique for predicting PD by mapping FICO scores into categorical buckets, optimizing the boundaries to best summarize the data.

Key Objectives:
Quantization of FICO Scores:

Develop a rating map that categorizes FICO scores into buckets.
Optimize bucket boundaries to minimize mean squared error or maximize log-likelihood.
Machine Learning Model for PD Prediction:

Build a machine learning model using the categorized FICO scores to predict the probability of mortgage default.
Ensure the model is adaptable for future data sets by using a general approach to bucket generation.
Approach:
Mean Squared Error (MSE): Minimize the squared error for approximated bucket values.
Log-Likelihood: Maximize the likelihood function considering bucket roughness and default density.
Dynamic Programming: Use a dynamic programming approach to split the problem into manageable subproblems, optimizing the categorization process.
This structured methodology helped in effectively analyzing the data and building robust models for the mortgage default prediction.
