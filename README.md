# Credit_Risk_Analysis

Evaluate several machine learning models to assess credit card risk.

## Overview of the loan prediction risk analysis

Use six machine learning models to evaluate which has the highest accuracy and precision in evaluating credit card risk.

## Results

- *Naive Random Oversampling Model*

![1](https://github.com/padilladaniela/Credit_Risk_Analysis/blob/main/Naive_Accuracy.png)

- *SMOTE Oversampling Model*

![2](https://github.com/padilladaniela/Credit_Risk_Analysis/blob/main/SMOTE_Balanced.png)

- *Undersampling Model*
- 
![2](https://github.com/padilladaniela/Credit_Risk_Analysis/blob/main/Undersampling_Balanced.png)

- *SMOTEENN Model*

![2](https://github.com/padilladaniela/Credit_Risk_Analysis/blob/main/SMOTEEEN.png)

- *Balanced Random Forest Model*

![2](https://github.com/padilladaniela/Credit_Risk_Analysis/blob/main/Random_Rainforest.png)

- *Easy Ensemble Model*

![2](https://github.com/padilladaniela/Credit_Risk_Analysis/blob/main/Easy_Essemble.png)



## Summary
The Easy Ensemble model has the highest accuracy score (0.93) and the F-1 score for low risk (0.97) is also the highest.
The recommended model for credit card analysis would be the Easy Ensemble model.
The Balanced Random Rainforest model has the second highest accuracy score at 0.79 and the F-1 score is 0.95.
The Naïve Random Oversampling model has an accuracy of 0.66 and a F-1 score of 0.80 for low risk.
The SMOTE model has an accuracy score of 0.63 and the F-1 score is 0.78 for low risk.
The SMOTEENN model has an accuracy score of 0.62 and the F-1 score is 70 for low risk.
UnderSampling has the lowest accuracy score at 0.51 and F-1 score of 0.60.
Because of how low both scores are the Undersampling model is not recommended for credit card risk analysis.
