# Credit Risk Analysis

## Overview of Analysis

### Purpose
The purpose of this analysis was to create different models and determine which model should be used to predict credit risk. The credit card credit dataset was provided by LendingClub, a peer-to-peer lending services company. 

### Description of Analysis
I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


## Results
Below, please find the results of the analysis:

### RandomOverSampler

<img width="611" alt="randomoversampler_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576120-8ebdee53-2bf2-44ef-90f7-6e686fdf54ca.png">
- Balanced accuracy score is 65%

<img width="814" alt="randomoversampler_classreport" src="https://user-images.githubusercontent.com/85654649/138576406-edea8443-e239-44cc-8055-9137f7d74fad.png">

- High_risk has a very low positivity at 1% and the recall is 66%.

### SMOTE 
<img width="504" alt="SMOTE_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576437-8c39b4ee-dfd5-412f-be47-6e325120ac66.png">

- Balanced accuracy score is 65%

<img width="818" alt="SMOTE_classreport" src="https://user-images.githubusercontent.com/85654649/138576452-8ae456ac-24e1-4586-ab8c-8b2d952eaec8.png">

- High_risk has a very low positivity at 1% and the recall is 61%.
  

### ClusterCentroids

- Balanced Accuracy Score 
- Precision Score
- Recall Score 

### SMOTEENN

- Balanced Accuracy Score 
- Precision Score
- Recall Score 

### BalancedRandomForestClassifier

- Balanced Accuracy Score 
- Precision Score
- Recall Score 

### EasyEnsembleClassifier

- Balanced Accuracy Score 
- Precision Score
- Recall Score 

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models 
## Summary
Based on the analysis, .

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
