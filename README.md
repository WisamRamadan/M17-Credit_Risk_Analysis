# Credi Risk Analysis

## Purpose:
The aim of this analysis is to apply skills in data preparation, statistical reasoning, and machine learning to solve credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I will use imbalanced-learn and scikit-learn libraries to employ the following techniques to train and evaluate models with unbalanced classes:
* Oversampling the data using the RandomOverSampler and SMOTE algorithms
* Undersampling the data using the ClusterCentroids algorithm
* Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm
* Use BalancedRandomForestClassifier and EasyEnsembleClassifier that reduce bias to predict credit risk.


## Results:
### Models' Performance Evaluation:

1. Oversampling the data using the RandomOverSampler

Balanced accuracy score: 0.67
![ros](ros.png)

2. Oversampling the data using the SMOTE 
Balanced accuracy score: 0.66
![smote](smote.png)

3. Undersampling the data using the ClusterCentroids algorithm

Balanced accuracy score: 0.66
![cc](cc.png)

4. combinatorial approach of over- and undersampling using the SMOTEENN algorithm

Balanced accuracy score: 0.66
![smoteen](smoteenn.png)

5. BalancedRandomForestClassifier

Balanced accuracy score: 0.79
![brfc](brfc.png)

6. EasyEnsembleClassifier

Balanced accuracy score: 0.93
![eec](ecc.png)

The 

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
