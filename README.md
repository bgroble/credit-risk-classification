# credit-risk-classification
 ## Purpose
 The purpose of this analysis is to train the machine learning model to predict the outcome, and then see how well the machine was trained by comparing the test data to the learned model. This was done in the linear regression. In this specific data, we were looking at how well the model was able to correctly predict that a candidate for a loan would be high risk or well-qualified (healthy) if granted a loan. This was based on a number of factors per each loan candidate, including debt to income ration, the loan size being requested, the income of the candidate, and more. 
 The linear regression showed how well the model was at predicting the creditworthiness of borrowers.
 ## Results 
 * The healthy loan was predicted perfectly, with 100% precision
 * The healthy loan was highly sensitive for true positives, with a 99% recall
 * The high risk loan well-predicted, with 85% precision 
 * The high risk loan was very sensitive for true positives, but less so than for healthy loans, with a 91% recall
 * The model was extremely accurate at predicting the creditworhiness of borrowers, being accurate 99% of the time
 
 ## Summary
In summary, the model is much better at predicting healthy loans than high risk loans, but it is very good at both. One potential factor to consider is that the number of occurrences in the data set, shown in the support column, is much lower for high risk loans than it is for healthy loans. This means that incorrectly identifying a high risk loan would impact the precision and recall more than for a healthy loan.
Because the model is highly accurate and precise, I would recommend that the model be used. However, it may be worth continuing quality improvements such as seeking out a larger data set with more high risk loans, so that these may be predicted with more precision and accuracy. While the model was very good at predicting these loans, any improvement would be extremely lucrative for the company since high risk loans are, by definition, more costly to the lender to grant. 
In short, the model does its job very well and is recommended, but it could be more sensitive to high risk loans. 
