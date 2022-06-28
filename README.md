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
