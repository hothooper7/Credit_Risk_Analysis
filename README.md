# Credit_Risk_Analysis

Using the credit card credit dataset from LendingClub, as well as various algorithms, the following will show which models best predict credit risk and whether or not they should be used for making loan decisions.  

## Results of recall scores of six machine learning models

### Naive Random Oversampling

![Naive Balanced Accuracy](https://user-images.githubusercontent.com/100809925/176233884-a7914967-5bd2-4bb2-9c7b-234f6924c1cf.jpeg)

![Naive Precision and Recall Scores](https://user-images.githubusercontent.com/100809925/176233947-299aeb77-9933-4ce6-b140-8670ba4cea62.jpeg)

As demonstrated by the Naive Random Oversampling images above: 
1.  The balanced accuracy score is .65 or 65% accurate.
2.  The precision for high risk loans is .01 or 1% accurate vs. low risk precision of 1.0 or ~100% accurate.
3.  The sensitivity for high risk loans is .63 vs. low risk loan sensitivity of .67.


### SMOTE Oversampling

![Smote Balanced Accuracy](https://user-images.githubusercontent.com/100809925/176235697-05fee692-2e83-4a1e-9b30-261d354a1500.jpeg)

![Smote Precision and Recall](https://user-images.githubusercontent.com/100809925/176235872-5cdb3ec3-8ffd-4f86-b6f7-dc2378db5426.jpeg)

As demonstrated by the SMOTE Oversampling images above: 
1.  The balanced accuracy score is .65 or 65% accurate.
2.  The precision for high risk loans is .01 or 1% accurate vs. low risk precision of 1.0 or ~100% accurate.
3.  The sensitivity for high risk loans is .64 vs. low risk loan sensitivity of .66.


### Undersampling

![Undersampling Balanced accuracy score](https://user-images.githubusercontent.com/100809925/176238209-1323b95f-fbba-4c47-8196-6baab6d06a58.jpeg)

![Undersampling precision and recall](https://user-images.githubusercontent.com/100809925/176238288-061b90a6-3d0e-4bf7-856c-d0e1b2a7cdef.jpeg)

As demonstrated by the Undersampling images above: 
1.  The balanced accuracy score is .51 or 51% accurate.
2.  The precision for high risk loans is .01 or 1% accurate vs. low risk precision of 1.0 or ~100% accurate.
3.  The sensitivity for high risk loans is .59 vs. low risk loan sensitivity of .43.


### Combination (Over and Under) Sampling


![Combination Sampling Balanced Accuracy Score](https://user-images.githubusercontent.com/100809925/176243909-f0dc328e-f02a-41b7-8239-05721acb0913.jpeg)

![Combination Sampling Precision and recall](https://user-images.githubusercontent.com/100809925/176243958-91aca7e3-8642-42f8-963e-c83517ae6fcc.jpeg)

As demonstrated by the Combination Sampling images above: 
1.  The balanced accuracy score is .62 or 62% accurate.
2.  The precision for high risk loans is .01 or 1% accurate vs. low risk precision of 1.0 or ~100% accurate.
3.  The sensitivity for high risk loans is .69 vs. low risk loan sensitivity of .55.


### Balanced Random Forest Classifier


![Balanced Random Forest Classifier Accuracy](https://user-images.githubusercontent.com/100809925/176245256-10d0cc53-9454-4a03-819d-fbb6fc4fba52.jpeg)

![Balanced Random Forest Classifier P C](https://user-images.githubusercontent.com/100809925/176245291-186e819e-c8db-4e48-80a5-9b07465ee8bf.jpeg)

As demonstrated by the Balanced Random Forest Classifier images above: 
1.  The balanced accuracy score is .79 or 79% accurate.
2.  The precision for high risk loans is .04 or 4% accurate vs. low risk precision of 1.0 or ~100% accurate.
3.  The sensitivity for high risk loans is .67 vs. low risk loan sensitivity of .91.


### Easy Ensemble AdaBoost Classifier


![EEAC BAS](https://user-images.githubusercontent.com/100809925/176246723-6087de2f-b790-4d23-bc4d-00125912f2e5.jpeg)

![EEAC P R](https://user-images.githubusercontent.com/100809925/176246775-97fc35e1-00af-4e11-8b34-3d8e7013b4c9.jpeg)


As demonstrated by the Easy Ensemble AdaBoost Classifier images above: 
1.  The balanced accuracy score is .93 or 93% accurate.
2.  The precision for high risk loans is .07 or 7% accurate vs. low risk precision of 1.0 or ~100% accurate.
3.  The sensitivity for high risk loans is .91 vs. low risk loan sensitivity of .94.


 ## Summary
 
Based on all of the models and algorithms, the Easy Ensemble AdaBoost Classifier is the most accurate at predicting credit risk.  Unfortunately, none of the models are particularly good at predicting high risk customers, which is perhaps the most important group.  Lending to high risk loan seekers is not a particularly good strategy, so I would recommend using the Easy Ensemble model in conjunction with other tests, such as interviewing potential loan candidates to gather more facts.  

