# Credit Risk Analysis

## Overview
The purpose of this analysis is to utilize multiple different machine learning models to determine which best helps us determine credit card risk.

## Results
 and the precision and recall scores of all six machine learning models.
  Use screenshots of your outputs to support your results

- Naive Random Oversampling Results
The balanced accuracy score for Naive Random Oversampling is 64%.  
<img width="492" alt="Naive Random Oversampling Results" src="https://user-images.githubusercontent.com/90050622/150651064-e9562fd0-5a51-48c1-bda8-a646eb69da37.png">

- SMOTE Oversampling Results
The balanced accuracy score for SMOTE Oversampling is 66%.
<img width="495" alt="SMOTE Oversampling Results" src="https://user-images.githubusercontent.com/90050622/150651072-b413e3fa-d5e4-48e0-b48d-2c86682ee78a.png">

- Undersampling Results
The balanced accuracy score for Undersampling is 54%.
<img width="491" alt="Undersampling Results" src="https://user-images.githubusercontent.com/90050622/150651078-d80b64c3-f7a6-4748-8980-5d78719878b4.png">

- Combination (Over and Undersampling) Results
The balanced accuracy score for Combination is 54%.
<img width="499" alt="Combination (Over and Undersampling) Results" src="https://user-images.githubusercontent.com/90050622/150651083-1dea385b-0e3b-4ab9-9432-946888ccfd0e.png">

- Balanced Random Forest Classifier Results
The balanced accuracy score for Balanced Random Forest Classifier is 75%.
<img width="495" alt="Balanced Random Classifier Results" src="https://user-images.githubusercontent.com/90050622/150651092-bdf9d6d6-b3a2-430f-9c13-a481dc0953b3.png">

- Easy Ensemble AdaBoost Classifier Results
The balanced accuracy score for Easy Ensemble AdaBoost Classifier is 93%.
<img width="502" alt="Easy Ensemble AdaBoost Classifier Results" src="https://user-images.githubusercontent.com/90050622/150651097-014fb860-7826-4546-bc72-26da3121daf2.png">

## Summary
The Easy Ensemble AdaBoost Classifier Model had by far the highest balanced accuracy score at 93%.  The next highest score was with the Random Forest Classifier which was at 75%.  Typically, we also want to make sure there is a good balance of recall and precision.  I would recommend the use of the Easy Ensemble AdaBoost Classifier.  Not only did it have the highest balanced accuracy score, but it also has a very good balance of precision and recall scores. 
