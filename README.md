# Credit_Risk_Analysis

## Overview of Analysis

The purpose of this analysis is to create various machine learning models to see if I can create a model that accurately predicts credit risk.

## Results

1. Naive Random Oversampling
  - Accuracy score: 0.64
  
  <img width="208" alt="image" src="https://user-images.githubusercontent.com/102273449/187326270-38d38b15-2ad5-4814-a2b0-9784c88426da.png">

  - Precision score: 0.01
  - Recall/sensitivity score: 0.69
  
  <img width="380" alt="image" src="https://user-images.githubusercontent.com/102273449/187325753-0521e73b-7e7d-4757-bf05-5ae8362d45fe.png">

2. SMOTE Oversampling
  - Accuracy score: 0.66
  
  <img width="123" alt="image" src="https://user-images.githubusercontent.com/102273449/187326333-bf290997-888a-4551-935f-14838aa3ff32.png">
  
  - Precision score: 0.01
  - Recall/sensitivity score: 0.63
  
  <img width="247" alt="image" src="https://user-images.githubusercontent.com/102273449/187326368-249356b8-f5d6-4ac4-be83-284ee08fb209.png">
  
3. Cluster Centroids
  - Accuracy score: 0.54
  
  <img width="165" alt="image" src="https://user-images.githubusercontent.com/102273449/187326460-559de46d-0522-4435-8889-f2687fa82f5d.png">
  
  - Precision score: 0.01
  - Recall/sensitivity score: 0.69
  
  <img width="328" alt="image" src="https://user-images.githubusercontent.com/102273449/187326511-4d177a76-ee7d-4639-bc98-36a8a15dd49d.png">
  
4. SMOTEENN
  - Accuracy score: 0.67
  
  <img width="214" alt="image" src="https://user-images.githubusercontent.com/102273449/187326550-d877a4d9-e486-4031-9e17-a012293538af.png">

  - Precision score: 0.01
  - Recall/sensitivity score: 0.76
  
  <img width="329" alt="image" src="https://user-images.githubusercontent.com/102273449/187326594-fab9e7c1-4014-4cef-bf45-c22c22367822.png">

5. Balanced Random Forest
  - Accuracy score: 0.79
  
  <img width="215" alt="image" src="https://user-images.githubusercontent.com/102273449/187326649-8ae333c3-82ae-4e2b-9c4d-953679d6ec7b.png">

  - Precision score: 0.03
  - Recall/sensitivity score: 0.7 
  
  <img width="329" alt="image" src="https://user-images.githubusercontent.com/102273449/187326702-c8971809-c384-424a-8e8d-9aabcc0888b7.png">
  
6. Easy Ensemble AdaBoost
  - Accuracy score: 0.93
  
  <img width="170" alt="image" src="https://user-images.githubusercontent.com/102273449/187326726-745e3712-55b8-4e93-87e0-12472ec7c1cc.png">

  - Precision score: 0.09
  - Recall/sensitivity score: 0.92
  
<img width="335" alt="image" src="https://user-images.githubusercontent.com/102273449/187326877-1892483a-821f-4523-b83d-ea3ad527c5a2.png">

## Summary

AdaBoost had the highest scores with an accuracy of 0.93, precision of 0.09, and sensitivity of 0.92. None of the models have a very good precision score, so I would not recommend them if you would like high precision in detecting credit risk. f you value sensitivity in your model, I would recommend using the AdaBoost as it had the highest sensitivity rating. 
