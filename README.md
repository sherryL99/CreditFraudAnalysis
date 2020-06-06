# CreditFraudAnalysis
## imbalanced dataset processing method
For classification problem. if there exists imbalance dataset, some kind of data with high percentage will overfitting, but others will underfitting. <br>
    For example,(1) in the credit fraud transaction, most of them are normal, but some of them has fraud behavior.<br>
            (2) in the problem of custom lossing, most of custmors will continue to use this service, but only a few of them won't.<br>

For this imbalanced scenario,  a problem will arise: if 90% of the training data belongs to the same class, our classificater would classified only this specific class, it would make no use. e.g. the ratio larger than 4:1<br>

METHOD:<br>
(1) sampling: oversampling, undersampling<br>
(2) based on Cost-Sensitive Learning, e.g. Adacost<br>
(3) make imbalanced dataset One Class Learning, or Novelty Detection, e.g. One-class SVM<br>

## PCA  Transformation
## Classification by Naive Bayes,LR, DT...
## Cross validation
