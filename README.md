# Credit Risk Analysis

## Overview of the analysys:
Using my knowledge of the imbalanced-learn and scikit-learn libraries, I evaluated three machine learning models by using resampling to determine which is better at predicting credit risk. I used the "loan_stats csv" file to help predict whether someone is low or high risk status.

# Results:

- Naive Random Oversampling: The balanced accuracy is 67% and the average precision is 99% with the recall on 61%.

![This is an image](https://github.com/KandiJayana/Credit_Risk_Analysis/blob/c088f393454a4425bb33d932104b5d3b0cd7a0e7/PNG/Naive%20Random%20Oversampling.png)

- SMOTE oversampling: The balanced accuracy is 62% average precision is 99% with the recall on 69%.

![This is an image](https://github.com/KandiJayana/Credit_Risk_Analysis/blob/c088f393454a4425bb33d932104b5d3b0cd7a0e7/PNG/SMOTE%20oversampling.png)

- Undersampling: The balanced accuracy is 66% and the average precision is 99% with the recall on 40%.

![This is an image](https://github.com/KandiJayana/Credit_Risk_Analysis/blob/c088f393454a4425bb33d932104b5d3b0cd7a0e7/PNG/Undersampling.png)

- Combination "over and undersampling": The balanced accuracy is 66% and the average precision is 99% with the recall on 59%.

![This is an image](https://github.com/KandiJayana/Credit_Risk_Analysis/blob/c088f393454a4425bb33d932104b5d3b0cd7a0e7/PNG/Combination.png)

- Balanced Random Forest Classifier: The balanced accuracy is 76% and the average precision is 99% with the recall on 87%.

![This is an image](https://github.com/KandiJayana/Credit_Risk_Analysis/blob/c088f393454a4425bb33d932104b5d3b0cd7a0e7/PNG/Balanced%20Random%20Forest.png)

- Easy Ensemble AdaBoost Classifier: The balanced accuracy is 93% and the average precision is 99% with the recall on 94%.
![This is an image](https://github.com/KandiJayana/Credit_Risk_Analysis/blob/c088f393454a4425bb33d932104b5d3b0cd7a0e7/PNG/Easy%20Ensemble%20AdaBoost.png)



# Summary: 
After running the analysis with all models and even with the precision being low or none for all of them, we can see that Easy Ensemble Classifier was the most effective because it provided the highest score.
I still recommend the Easy Ensemble Classifier because when your performance is above 90%, it is considered a great value for the overall analysis.
