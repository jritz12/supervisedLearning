# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

The purpose of this analysis is to determine the creditworthiness of borrowers based on several variables. The financial information provides us with an individuals loan size, the interest rate, the borrowers income, the debt to income ratio, number of accounts, derogratoy marks, total debt and loan status. We need to predict from this whether they recieved a loan or not based off the variables. The variable we are trying to predict is loan_status 75,036 people were categorized as low risk borrowers while 2500 were classified as high risk. The stages of machine learning that I went through is to first train the dataset on the original data, I then fit the regression model using the training data. Next I proceeded to created a new logistic regression with a resampled training data to see if it was more accurate.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy was  0.9520479254722232, Precision weighted average was 0.99 however the macro avg was 0.92, and Recall scores the weighted average was 0.99 and macro average was 0.92.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy was 0.9936781215845847, Precision weighted average was 0.99 and macro average was 0.92, and Recall scores both macro and weighted averages were 0.99.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
The second model performed better with an accuracy score of over 99% compared to the first models score of slightly over 95%. Performance does matter on the problem we are trying to solve. In this case it is more import to accurately detect high risk loans since a business could lose money.
