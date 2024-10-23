1.	Clear statement demonstrating your understanding of the business problem
 The business objective is to develop a predictive model that identifies the likelihood of a client subscribing to a bank term deposit following a marketing contact. This model aims to increase the efficiency of marketing campaigns by reducing the number of contacts made while maintaining or improving the success rate of term deposit subscriptions.

2.	Concise interpretation of descriptive and inferential statistics, your findings (including actionable insights).
 
we can see that the target variable is highly unbalanced (88% of the data is no). This will impact the training and models we are going to use.
we can see normal distributions in almost all numerical columns. Column pdays should be inspected further since 999 means client was not contacted.
we can see that some distributions are highly unbalanced such as:
 
 
3. Next steps and recommendations.
Observation: depending on the performance metric, different models could be called the "best", 
- Using Test Accuracy: Decision Tree (90%) 
- Using F1 Score: Logistic Regression (45%) 
While some models were able to get over 90% on both training and test sets, the target variable is highly unbalanced and if the models were to just say "no", it'd give them high accuracy on the training/test sets. 
The target variable is highly unbalanced so this issue needs to be addressed AND/OR we need to use more complicated models to get a better F1 score.
Adjust your performance metric
Please see the below data frame results of hyper parameter tuning and basic model training.

 
 
  
