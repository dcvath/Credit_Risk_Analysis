# Credit Risk Analysis

## Overview of Analysis

### Purpose
The purpose of this analysis was to create different models and determine which model should be used to predict credit risk. The credit card credit dataset was provided by LendingClub, a peer-to-peer lending services company. 

### Description of Analysis
I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. Then, I used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.


## Results
Below, please find the results of the analysis:

### RandomOverSampler
- Balanced accuracy score is 64%

<img width="611" alt="randomoversampler_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576120-8ebdee53-2bf2-44ef-90f7-6e686fdf54ca.png">

- High_risk has a very low positivity at 1% and the recall is 66%.

<img width="814" alt="randomoversampler_classreport" src="https://user-images.githubusercontent.com/85654649/138576406-edea8443-e239-44cc-8055-9137f7d74fad.png">


### SMOTE 
- Balanced accuracy score is 65%
<img width="504" alt="SMOTE_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576437-8c39b4ee-dfd5-412f-be47-6e325120ac66.png">

- High_risk has a very low positivity at 1% and the recall is 61%.

<img width="818" alt="SMOTE_classreport" src="https://user-images.githubusercontent.com/85654649/138576452-8ae456ac-24e1-4586-ab8c-8b2d952eaec8.png">


### ClusterCentroids

- Balanced accuracy score is 65%.

<img width="487" alt="Cluster_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576561-230c4485-2adb-4ca7-b5c2-44023cfd3a1b.png">

- High_risk has a very low positivity at 1% and the recall is 69%.

<img width="834" alt="Cluster_classreport" src="https://user-images.githubusercontent.com/85654649/138576584-41e2a788-da07-43cd-b69e-763826215451.png">


### SMOTEENN

- Balanced accuracy score is 54%.

<img width="503" alt="SMOTEENN_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576667-a11555b2-3d3d-4cbc-90e6-f52cff709f44.png">

- High_risk has a very low positivity at 1% and the recall is 72%.

<img width="819" alt="SMOTEENN_classreport" src="https://user-images.githubusercontent.com/85654649/138576695-15a7f08c-997a-44a9-9e67-9b5d16a8a9f6.png">


### BalancedRandomForestClassifier

- Balanced accuracy score is 77%.

<img width="605" alt="Forest_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576741-1cb8e1d8-a9da-47a6-8cc6-040359cb05dd.png">

- High_risk has a very low positivity at 3% and the recall is 66%.

<img width="808" alt="Forest_classreport" src="https://user-images.githubusercontent.com/85654649/138576756-82fb4d5c-04df-4762-be55-680293c4c090.png">


### EasyEnsembleClassifier

- Balanced accuracy score is 92%.

<img width="502" alt="AdaBoost_accuracyscore" src="https://user-images.githubusercontent.com/85654649/138576840-e09fdc92-d51f-4f31-8e4c-b61190033d12.png">

- High_risk has a very low positivity at 9% and the recall is 89%.


## Summary
Based on the analysis, .

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
