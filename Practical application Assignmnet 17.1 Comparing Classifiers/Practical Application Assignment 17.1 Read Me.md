1.	Clear statement demonstrating your understanding of the business problem

 The business objective is to develop a predictive model that identifies the likelihood of a client subscribing to a bank term deposit following a marketing contact. This model aims to increase the efficiency of marketing campaigns by reducing the number of contacts made while maintaining or improving the success rate of term deposit subscriptions.

2.	Concise interpretation of descriptive and inferential statistics, your findings (including actionable insights).
We can see that some distributions are highly unbalanced such as:
•	'default'
•	'loan'
•	'month'
•	'poutcome'

We can also see that columns like ['job', 'age', 'marital', 'education', 'day_of_week', 'housing', 'loan'] do not contribute much to the target variable (very low correlation < 0.05).
The columns with the highest correlation are:
•	nr.employed (0.35)
•	pdays (0.32)
•	euribor3m (0.30)
•	emp.var.rate (0.29)
•	previous (0.23)

3.	Next steps and recommendations.

Now that we have some basic models on the board, we want to try to improve these. Below,   we list a few things to explore in this pursuit.
•	More feature engineering and exploration. For example, should we keep the gender feature? Why or why not?
•	Hyper parameter tuning and grid search. All of our models have additional hyper parameters to tune and explore. For example the number of neighbors in KNN or the maximum depth of a Decision Tree.
•	Adjust your performance metric

