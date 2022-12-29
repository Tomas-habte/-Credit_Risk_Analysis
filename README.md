# Credit Risk Analysis
## Overview
The purpose of this analysis is to determine the best machine learning model that can be used to predict credit card risk. This will help a peer-to-peer lending services company to reduce their business risk.  

## Results
|  Machine Learning Models Results | 
| ------------- | 
|• **Naive Random Oversampling**: Balanced accuracy score of 0.6573.|
| ![Naive Random Oversampling](https://user-images.githubusercontent.com/111667387/209897500-ea635d3e-a406-4995-8880-54fcc35e56f5.jpg)| 
|• **SMOTE Oversampling**: Balanced accuracy score of 0.6622.|
|![SMOTE Oversampling](https://user-images.githubusercontent.com/111667387/209897528-60a04e48-29e3-4d3d-9f7b-58703a66d34a.jpg)| 
|• **Undersampling**: Balanced accuracy score of 0.5443.|
|![Undersampling](https://user-images.githubusercontent.com/111667387/209897551-41f97bf2-c8d3-4fad-83da-98ab32285681.jpg)| 
|• **Combination Sampling**: Balanced accuracy score of 0.6876.|
|![Combination Sampling](https://user-images.githubusercontent.com/111667387/209897559-36249741-d555-4c53-966c-d827b2f04162.jpg)| 
|• **Balanced Random Forest Classifier**: Balanced accuracy score of 0.7885.|
|![Balanced Random Forest Classifier ](https://user-images.githubusercontent.com/111667387/209897565-8df74087-2462-4ed9-8eed-c0ec21ed73a6.jpg)| 
|• **Easy Ensemble AdaBoost Classifier**: Balanced accuracy score of 0.9317.|
|![Easy Ensemble AdaBoost Classifier ](https://user-images.githubusercontent.com/111667387/209897571-4585faf9-6547-4c4d-a262-565414937569.jpg)| 
## Summary
The results above shows that there is a significant difference in the ability of a machine learning model to predict risk depending on the model used. For example, Native Random Oversampling had a much lower sensitivity score (0.40) than Easy Ensemble AdaBoost Classifier (0.94). Since credit risk is an inherently unbalanced classification problem, we can use the balanced accuracy score as a key performance metric for the models. Easy Ensemble AdaBoost Classifier had the highest balanced accuracy score of 0.9317. It also had the highest F1 score (0.97) which is another important performance metric. Therefore, we recommend that this model is used. 
