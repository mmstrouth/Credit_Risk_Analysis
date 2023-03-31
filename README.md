# Credit Risk Analysis

##  Overview
The analysis below was performed to determine which, if any, model of credit risk prediction would be optimal.

## Results

### Naive Random Oversampling Technique
* balanced accuracy score: 63%
* Precision & Recall Scores shown below

![This is an image](https://github.com/mmstrouth/Credit_Risk_Analysis/blob/59389b521e8a9b49c63764667edd49a76e10d7a9/Resources/RandomOverSampler.png)


### SMOTE Oversampling Technique
* balanced accuracy score: 66%
* Precision & Recall Scores shown below

![This is an image](https://github.com/mmstrouth/Credit_Risk_Analysis/blob/59389b521e8a9b49c63764667edd49a76e10d7a9/Resources/SMOTE.png)


### ClusterCentroids Undersampling Technique
* balanced accuracy score: 53%
* Precision & Recall Scores shown below

![This is an image](https://github.com/mmstrouth/Credit_Risk_Analysis/blob/59389b521e8a9b49c63764667edd49a76e10d7a9/Resources/ClusterCentroids.png)

### SMOTEENN Combination Technique
* balanced accuracy score: 64%
* Precision & Recall Scores shown below

![This is an image](https://github.com/mmstrouth/Credit_Risk_Analysis/blob/59389b521e8a9b49c63764667edd49a76e10d7a9/Resources/SMOTEENN.png)

### Balanced Random Forest Classifier Technique
* balanced accuracy score: 79%
* Precision & Recall Scores shown below

![This is an image](https://github.com/mmstrouth/Credit_Risk_Analysis/blob/59389b521e8a9b49c63764667edd49a76e10d7a9/Resources/BalancedRandomForestClassifier.png)

### Easy Ensemble AdaBoost Classifier Technique
* balanced accuracy score: 93%
* Precision & Recall Scores shown below

![This is an image](https://github.com/mmstrouth/Credit_Risk_Analysis/blob/59389b521e8a9b49c63764667edd49a76e10d7a9/Resources/EasyEnsembleClassifier.png)

## Summary
Each of the techniques described above have pros and cons. Overall, the Easy Ensemble AdaBoost Classifier Technique has the highest accuracy score. However, when considering the precision and sensitivty scores, I would not recommend any of the models described above because of the nature of credit risk assessment. The credit provider may overestimate how many potential customers are too high risk, thus losing potential business that would actually be beneficial.  
