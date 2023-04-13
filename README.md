# Credit_Risk_Analysis

## Overview 
The purpose of this analysis is to predict credit risk using various Machine Learning models. Credit risk refers to the probability of a borrower's inability to repay a loan, which leads to losses for the lender. In this analysis, we used six supervised machine learning models to assess and predict credit risk! These algorithms include Random Oversampling, SMOTE, SMOTEENN, ClusterCentroids, Balanced Random Forest Classifier, and Easy Ensemble AdaBoost Classifier. Each will be presented along with their respective imbalanced classification report.

## Results
Below is the summary of the balanced accuracy scores and the precision and recall scores for each machine learning model, along with their respective imbalanced classification reports:

### Random Oversampling
* The model showed a slightly improved balanced accuracy score compared to Logistic Regression. Precision for high-risk loans was still low, but recall scores were higher for both classes.
* Accuracy Score: 0.658

<img width="629" alt="Screen Shot 2023-04-13 at 2 48 04 PM" src="https://user-images.githubusercontent.com/18335464/231855144-a80a926e-0868-465f-b941-a8bcb81979ac.png">

### SMOTE
* This method demonstrated similar results to Random Oversampling in terms of balanced accuracy, precision, and recall scores, making it another viable option.
* Accuracy Score: 0.652

<img width="631" alt="Screen Shot 2023-04-13 at 2 48 13 PM" src="https://user-images.githubusercontent.com/18335464/231855188-a318a8ee-bf73-4fb6-9973-d7e49a48b335.png">

### ClusterCentroids
* The model's balanced accuracy score was lower compared to other models, and the recall score for low-risk loans was also lower. However, it achieved better precision for high-risk loans.
* Accuracy Score: 0.538

<img width="630" alt="Screen Shot 2023-04-13 at 2 48 26 PM" src="https://user-images.githubusercontent.com/18335464/231855222-084a63c9-db40-4a6e-a7f9-1392130d8a14.png">

### SMOTEENN
* Improvement in accuracy score compared to some other models. While the precision for high-risk loans remained low, the recall scores for both classes were notably higher, indicating a better ability to identify true positive cases.
* Accuracy Score: 0.634

<img width="631" alt="Screen Shot 2023-04-13 at 2 48 36 PM" src="https://user-images.githubusercontent.com/18335464/231855256-cece82e3-c7aa-4592-9fcd-f5dab42022c0.png">

### Balanced Random Forest Classifier
* This model had a high balanced accuracy score, indicating improved performance over other methods. It also had reasonable precision and recall scores for both classes, showing a balanced performance.
* Accuracy Score: 0.779

<img width="630" alt="Screen Shot 2023-04-13 at 2 49 05 PM" src="https://user-images.githubusercontent.com/18335464/231855343-91f2ce45-40ce-49a1-a9d8-6ee9d36d1944.png">

### Easy Ensemble AdaBoost Classifier
* The model has the highest accuracy score among all tested models, along with high recall scores for both low-risk and high-risk loans. This indicates a strong overall performance in predicting credit risk. Note: this imbalanced classification report is about the same as the Random Forest Classifier's report. The improvement is in the accuracy score!
* Accuracy Score: 0.931

<img width="629" alt="Screen Shot 2023-04-13 at 3 05 05 PM" src="https://user-images.githubusercontent.com/18335464/231858673-2f7cc701-6688-4f96-9aa9-7f12908a75e0.png">

## Summary
In summary, the analysis results indicate that the Easy Ensemble AdaBoost Classifier performed best in predicting credit risk among the other Machine Learning models. This model has the highest balanced accuracy score and high recall scores for both low risk and high risk loan predictions. Therefore, we recommend using the Easy Ensemble AdaBoost Classifier for predicting credit risk in this scenario.

However, it is crucial to consider other factors, such as the size of the dataset and computational resources, when choosing a model for real-world applications. It is a good idea to test multiple models before making a final decision on the best model to use for credit risk prediction.
