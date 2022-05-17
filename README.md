# OneLastTrain-Kaggle
Given a medical dataset, divide the dataset into multiple clusters, analyze these clusters, explain the cluster formation and predict the cluster if a new data point(user) input is given. 

[Kaggle Source](https://www.kaggle.com/competitions/onelasttrain/overview)

## Description:
- Target variable in train is readmitted_NO.
- YOU CAN USE ONLY CLUSTERING METHODS, NO CLASSIFIERS

## Challenge
- You are encouraged to only use __Clustering__ methods. No _classifiers_ is to be used.


## Approach
- The dataset has _inconsistent_ empty values. To tackle that, a simple panda replace would do the trick.
- To remove NaN values, a simple column wise % inspection of NaN s will give how many ineffective columns we have.
- These columns (with less than 20% data) are dropped.
