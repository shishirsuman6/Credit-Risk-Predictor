# credit_risk_predictor


Mortgages, student and auto loans, and debt consolidation are just a few examples of credit and loans that people seek online. Peer-to-peer lending services such as Loans Canada and Mogo let investors loan people money without using a bank. However, because investors always want to mitigate risk, in this scenario a client has asked that I help them predict credit risk with machine learning techniques.

In this report I have built and evaluated several machine learning models to predict credit risk using data one would typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so I have employed different techniques for training and evaluating models with imbalanced classes. I have used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:



### 1) [Resampling](Reports/credit_risk_resampling.ipynb)

```

Conclusions


Which model had the best balanced accuracy score?

The following models have the same balanced accuracy score: RandomOverSampler, SMOTE, and SMOTEENN ClusterCentroids has a slightly lesser balanced accuracy score


Which model had the best recall score?

The following models have the same recall score: RandomOverSampler, SMOTE, and SMOTEENN ClusterCentroids has a slightly lesser recall score for low_risk loan status.



Which model had the best geometric mean score?

All models have the same Geometric Mean score.

```


### 2) [Ensemble Learning](Reports/credit_risk_ensemble.ipynb)

```
Conclusions


Which model had the best balanced accuracy score?

EasyEnsembleClassifier


Which model had the best recall score?

EasyEnsembleClassifier


Which model had the best geometric mean score?

EasyEnsembleClassifier


What are the top three features?

for BalancedRandomForestClassifier

 1.  'total_rec_prncp'
 2.  'last_pymnt_amnt'
 3. 'total_pymnt_inv'

```


