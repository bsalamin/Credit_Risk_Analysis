# Credit_Risk_Analysis

## Objective
The goal of this analysis was to acheieve the following:
* Explain how a machine learning algorithm is used in data analytics.
* Create training and test groups from a credit card credit risk data set.
* Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
* Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
* Compare the advantages and disadvantages of each supervised learning algorithm.
* Determine which supervised learning algorithm is best used for a given data set or scenario.
* Use ensemble and resampling techniques to improve model performance.

## Results
The analysis employed six machine learning models, and the results for each were summarized with a balanced accuracy score along with precision and recall scores.

### Naive Random Oversampling
* Balance accuracy: 0.655
* Precision is high for low-risk loans and low for high-risk loans.
* Recall: 0.7/0.61

![naive_random](https://user-images.githubusercontent.com/100387078/175821785-51601cfa-36b9-4a9c-b90f-35459c71aada.png)


### SMOTE Oversampling
* Balance accuracy: 0.662
* Precision is high for low-risk loans and low for high-risk loans.
* Recall: 0.63/0.69

![smote](https://user-images.githubusercontent.com/100387078/175821796-ddbb84de-8a25-4ad4-9995-bcb13b2fa67b.png)


### Undersampling
* Balance accuracy: 0.662
* Precision is high for low-risk loans and low for high-risk loans.
* Recall: 0.69/0.4

![undersampling](https://user-images.githubusercontent.com/100387078/175821806-b3adcf51-8623-420b-868a-07050511f327.png)


### Combination Under-Over Sampling
* Balance accuracy: 0.5447
* Precision is high for low-risk loans and low for high-risk loans.
* Recall: 0.72/0.57

![combo](https://user-images.githubusercontent.com/100387078/175821818-74a1ee52-7c01-4f9e-ba41-9c922de4fe2e.png)


### Balanced Random Forest Classifier
* Balance accuracy: 0.787
* Precision is high for low-risk loans and low for high-risk loans.
* Recall: 0.67/0.91

![brfc](https://user-images.githubusercontent.com/100387078/175821832-10f129d1-a143-4f2d-9ed0-d83d44204592.png)


### Easy Ensemble AdaBoost Classifier
* Balance accuracy: 0.925
* Precision is high for low-risk loans and low for high-risk loans.
* Recall: 0.91/0.94

![eec](https://user-images.githubusercontent.com/100387078/175821858-d4828572-f397-4c2e-9070-7c34f099a440.png)


## Summary
The Easy Ensemble AdaBoost Classifier model has the highest balanced accuracy score of 0.925, while the rest of the models had accuracy scores under 0.8. The sensitivity rate, aka "recall," for the Easy Ensemble AdaBoost Classifier was also highest amongst the ML models. The precision scores were very much similar for all the models, so there was no real difference in that regard. 

The Easy Ensemble AdaBoost Classifier is the best machine learning model for this dataset.  
