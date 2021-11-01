# Credit_Risk_Analysis

## Overview of the analysis: 
The purpose of this analysis is to use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm, and then compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit card risk. Finally, evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: 

### Naive Random Oversampling
* Balanced Accuracy Score
* ![Naive - Balanced](https://user-images.githubusercontent.com/85706721/139611571-8dce3f3a-50c0-4cb2-8a4a-dcb8705b195e.png)

* Precision and Recall Scores
* ![Naive - Recall](https://user-images.githubusercontent.com/85706721/139611585-b64670ed-47bb-4ace-9550-1cadeacb7129.png)


### SMOTE Oversampling
* Balanced Accuracy Score
* ![SMOTE - Balanced](https://user-images.githubusercontent.com/85706721/139611596-e0cb2491-3285-4f38-a51d-00e6e0ef4345.png)

* Precision and Recall Scores
* ![SMOTE - Recall](https://user-images.githubusercontent.com/85706721/139611603-f46b5725-e577-488b-b227-d919fe31dae5.png)


### Undersampling with Cluster Centroids
* Balanced Accuracy Score
* ![Undersampling - Balanced](https://user-images.githubusercontent.com/85706721/139611606-fd684ba7-b7b0-495d-afb3-087af4e5712f.png)

* Precision and Recall Scores
* ![Undersampling - Recall](https://user-images.githubusercontent.com/85706721/139611612-9253a1d9-eabe-489a-a5a1-9da0f73c5a1f.png)


### Combination (Over and Under) Sampling with SMOTEENN
* Balanced Accuracy Score
* ![Combination - Balanced](https://user-images.githubusercontent.com/85706721/139611619-54983e93-0152-4ee2-a102-9ae0be878bd5.png)

* Precision and Recall Scores
* ![Combination - Recall](https://user-images.githubusercontent.com/85706721/139611625-f0802990-c794-4c55-84d5-e73c97f3331d.png)


### Balanced Random Forest Classifier
* Balanced Accuracy Score
* ![Balanced - Balanced](https://user-images.githubusercontent.com/85706721/139611633-730300b9-7392-46c5-9aaa-be9d9ef9b174.png)

* Precision and Recall Scores
* ![Balanced - REcall](https://user-images.githubusercontent.com/85706721/139611644-a946725e-3df4-4c08-81f2-16778816219d.png)


### Easy Ensemble AdaBoost Classifier
* Balanced Accuracy Score
* ![Easy - Balanced](https://user-images.githubusercontent.com/85706721/139611657-c990bf72-2f2d-48f4-bc48-506fdcd64023.png)

* Precision and Recall Scores
* ![Easy - Recall](https://user-images.githubusercontent.com/85706721/139611670-66e58162-5948-4f86-84f8-65a9192a8767.png)


## Summary: 
The Naive, Smote, and Undersampling models have the same fairly low balanced accuracy score of 65%.

The Combination has the lowest balanced accuracy score at 54%.

The Balanced Random Forest Classifier model has a better balanced accuracy score than the previous models at 79%.

The Easy Ensemble Adaboost Classifier model has the highest balanced accuracy score at 93%.  

I would recommend the Easy Ensemble Adaboost Classifier model because it has the highest balanced accuracy score.
