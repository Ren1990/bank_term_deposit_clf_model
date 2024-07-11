# **Bank Term Deposition Marketing Campaigns Outcome Classification Prediction Model**
This is a Jupyter project demonstrate on classification model training. You may visit the presentation slide below.

Presentation Slide Link: https://docs.google.com/presentation/d/1hGG3yMfugKGOfFKQ-XcSUYOL7bIE1J2XIRnxq0ROVEQ/edit#slide=id.g274072545a7_0_1

## **Introduction**
### Dataset Overview
The data model study below is based on Kaggle open dataset: https://www.kaggle.com/datasets/thedevastator/bank-term-deposit-predictions

This dataset, titled Direct Marketing Campaigns for Bank Term Deposits, is a collection of data related to the direct marketing campaigns conducted by a Portuguese banking institution. These campaigns primarily involved phone calls with customers, and the objective was to determine whether or not a customer would subscribe to a term deposit offered by the bank. Most of the outcomes of the dataset is 'unsuccessful' (i.e. **unbalanced data**), therefore the study will prioritize on balanced accuracy (i.e. simple average accuracy of successful and unsuccessful outcome, instead of weight average accuracy of the two outcomes) and recall.

### Objective
The goal is to predict the outcome of the marketing campaign by training model with provided data, and study what are the key factors affecting the result.

### Model Training Flow
1. Data Cleaning & Exploration
2. Data Transformation
3. Model Selection
4. Base Model Training
5. Feature Engineering and Model Finetune
6. Conclusion
