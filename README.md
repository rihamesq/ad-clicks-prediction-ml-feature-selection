# MSc Dissertation Code: CTR Predictions for SMEs  
**Comparing Machine Learning and Feature Selection Methods for Digital Advertising**  

This repository contains the code for my MSc dissertation, titled:  
*“Ad Click Predictions: Comparing Machine Learning and Feature Selection Methods for Digital Advertising.”*

## Overview  
The goal of this research is to investigate methods for predicting Click-Through Rates (CTR) in small and medium enterprises (SMEs) using various machine learning models and feature selection techniques. By analysing and comparing these methods, this project aims to uncover optimal strategies to improve the efficiency and accuracy of digital advertising campaigns for SMEs.  

## Dataset  
This project utilises the **Aliyun Taobao Click-Through Rate (CTR) Prediction Dataset**, which is widely used in CTR prediction research. The dataset includes anonymised user interaction data, such as clicks and actions taken, along with features like user demographics, and ad features.  
- Dataset link: [Aliyun Taobao CTR Dataset]((https://tianchi.aliyun.com/dataset/56))  

## Key Features of the Project  
- Preprocessing and balancing techniques to handle large-scale and imbalanced data.  
- Comparison of traditional machine learning models (Decision Tree, Catboost, simple custom Keras MLP) and deep learning models (Wide & Deep, DeepFM and xDeepFM).  
- Implementation of feature selection techniques such as Recursive Feature Elimination (RFE) and permutation-based importance, to assess the relevance of feature selcetion in improving CTR predictions.  
- Comparison of model performances combined with feature selection methods.  

## File Structure  
- **Notebooks:**  
  Contains Jupyter Notebook files for data preprocessing, feature engineering, model training, and evaluation.  
- **Scripts:**  
  Includes Python scripts for running the models and generating feature importance results.  
- **Outputs:**  
  Stores evaluation results and visualisations of feature importances.  
 
