# CreditFraudAnalysis
## imbalanced dataset processing method
For classification problem. if there exists imbalance dataset, some kind of data with high percentage will overfitting, but others will underfitting. <br>
```highlight```
    `For example',
    `圆点`
     * in the credit fraud transaction, most of them are normal, but some of them has fraud behavior.<br>
     * in the problem of custom lossing, most of custmors will continue to use this service, but only a few of them won't.<br>

For this imbalanced scenario,  a ‘problem’ will arise: if 90% of the training data belongs to the same class, our classificater would classified only this specific class, it would make no use. e.g. the ratio larger than 4:1<br>

METHOD:<br>
(1) sampling: oversampling, undersampling<br>
`超链接`
[reference](https://www.marcoaltini.com/blog/dealing-with-imbalanced-data-undersampling-oversampling-and-proper-cross-validation"click it out")
(2) based on Cost-Sensitive Learning, e.g. Adacost<br>
(3) make imbalanced dataset One Class Learning, or Novelty Detection, e.g. One-class SVM<br>

## PCA  Transformation
## Classification by Naive Bayes,LR, DT...
## Cross validation
