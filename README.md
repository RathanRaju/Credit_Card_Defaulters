# Credit Card Defaulters

- Dataset Link - https://www.kaggle.com/code/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets/data


### Outline

- Introduction
- Understanding our data
- Preprocessing
- Classifiers
- Random UnderSampling and Oversampling
- Testing
- Conclusion



## Introduction

In this kernel we will use various predictive models to see how accurate they are in detecting whether a transaction is a normal payment or a fraud. As described in the dataset, the features are scaled and the names of the features are not shown due to privacy reasons. 


## Understanding our data

Imbalanced Data - ![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/Imbalanced_Data.png "Imbalanced Data")

- No Frauds 99.83 % of the dataset
- Frauds 0.17 % of the dataset


## Preprocessing

Distributions 

![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/Distribution%20of%20Transcation%20Amount%20and%20Time.png "Distributions")

- By seeing the distributions we can have an idea how skewed are these features, we can also see further distributions of the other features.


Equally Distributing and Correlating by taking the subset from the original data

![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/Equally%20Distributed%20Classes.png "Equally Distributing")


Distribution of the Classes in the subsample dataset
- No Frauds 50 % of the dataset
- Frauds 50 % of the dataset


Imbalanced Correlation Matrix 

![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/Imbalanced%20Correlation%20Matrix.png "Imbalanced Correlation Matrix")


## Classifiers

ROC Curve of Top 4 Classifiers 

![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/ROC%20Curve.png "ROC Curve of Top 4 Classifiers ")


## Random UnderSampling and Oversampling

UnderSampling Precision-Recall curve

![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/UnderSampling.png "UnderSampling Precision-Recall curve ")


OverSampling Precision-Recall curve

![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/OverSampling.png "OverSampling Precision-Recall curve ")



## Testing

Confusion Matrix of all the Classification Models

![alt text](https://github.com/RathanRaju/Credit_Card_Defaulters/blob/main/Classification_Models.png "Classification Models ")


## Conclusion

- The best-performing models were logistic regression and support vector classifier (SVM). 

- Furthermore, the Random UnderSampling and OverSampling (SMOTE) method yielded accuracy scores of 94.21 and 98.70. 

- Implementing SMOTE on our unbalanced dataset assisted us in dealing with label imbalance (more no fraud than fraud transactions). 

- Assume that consumers who were making regular transactions had their cards stopped because our model categorised the transaction as fraudulent. this would be a big disadvantage for the banking institution. The quantity of client complaints and dissatisfaction will grow.

