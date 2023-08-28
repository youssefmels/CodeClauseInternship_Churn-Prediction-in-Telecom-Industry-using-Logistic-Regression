# CodeClauseInternship_Churn-Prediction-in-Telecom-Industry-using-Logistic-Regression
This project is a part of my data science internship at CodeClause. It is a model that predicts whether a client in the telecom industry would churn. Churning is when a customer ends their subscription with your company during a certain time frame.
The dataset was straightforward. There were no nulls or duplicates in the dataset; however, there were 11 empty strings in the "Total Charges" column which I replaced with the column's mean.
I performed preprocessing and data visualization to see how each categorical feature could relate to churning, and to also view each categorical column's values. More visualization, box plots, was performed to look for outliers, but none were found.
I changed the categorical columns to numerical using label encoder and then I used vif test to measure multicollinearity. Four columns were found to have high collinearity. I attempted to use PCA to deal with the issue, but accuracy decreased by a lot.
Then I found out the correlation and I used chi-square test for feature selection. I used SMOTE to deal with variable imbalance and trained and tested using imbalanced data and balanced data to see the difference.
I employed grid search with the imbalanced dataset for the best results.
After training, the difference could be seen in each data's classification report, accuracy, and confusion matrix.
I would like to thank CodeClause for giving me this opportunity to enhance and showcase my abilities in this field.

