# Credit_Risk_Analysis

## Analysis Overview
We were asked to train and test six different imbalanced machine learning models assessing credit card risk. Four of the models were created using different resampling algorithms, the other two were bias-reduction models. The purpose of this was to find which model could assess cred card risk.

The sklearn models used in this project were:
  1. Random Oversampling
  2. SMOTE Oversampling
  3. Cluster Centroids Undersampling
  4. SMOTEENN Combination Sampling
  5. Balanced Random Forest
  6. Easy Ensemble Adaptive Boost

## Results

### Random Oversampling

![Random Oversampling]()

 - The overall accuracy score for random oversampling was 64.75%. 
 - The precision on high risk credit was 1%, recall was 62%, and the F1 score was 2%.
 - The recall on low risk credit was 67% and the F1 score was 80%.

### SMOTE Oversampling

![Smote Oversampling]()

 - The overall accuracy score for SMOTE oversampling was 61.70%. 
 - The precision on high risk credit was 1%, recall was 57%, and the F1 score was 2%.
 - The recall on low risk credit was 66% and the F1 score was 79%.

### Cluster Centroids Undersampling

![Cluster Centroids]()

 - The overall accuracy score for Cluster Centroids undersampling was 51.60%. 
 - The precision on high risk credit was 1%, recall was 60%, and the F1 score was 1%.
 - The recall on low risk credit was 43% and the F1 score was 60%.

### SMOTEENN Combination Sampling

![SMOTEENN Combination Sampling]()

 - The overall accuracy score for SMOTEENN Combination Sampling was 63.47%. 
 - The precision on high risk credit was 1%, recall was 70%, and the F1 score was 2%.
 - The recall on low risk credit was 57% and the F1 score was 63%.

### Balanced Random Forest

![Balanced Random Forest]()

 - The overall accuracy score for Balanced Random Forest was 78.85%. 
 - The precision on high risk credit was 3%, recall was 70%, and the F1 score was 6%.
 - The recall on low risk credit was 87% and the F1 score was 93%.

### Easy Ensemble Adaptive Boost

![Easy Ensemble Adaptive Boost]()

 - The overall accuracy score for Easy Ensemble Adaptive Boost was 93.17%. 
 - The precision on high risk credit was 9%, recall was 92%, and the F1 score was 6%.
 - The recall on low risk credit was 87% and the F1 score was 93%.




