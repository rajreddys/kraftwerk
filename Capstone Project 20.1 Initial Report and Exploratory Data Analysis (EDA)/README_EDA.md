### Project Title

**Author**

#### Executive Summary

This project aims to predict customer churn in the telecommunications industry using the Telco Customer Churn dataset. By analyzing customer attributes and service usage patterns, we identify high-risk customers, enabling proactive retention strategies to reduce churn.

#### Rationale

Customer churn is a critical problem for telecommunication companies, leading to significant revenue loss. Accurately identifying customers likely to churn allows businesses to implement targeted retention measures, improving customer satisfaction and profitability.

#### Research Question

How can we predict customer churn using customer demographic, account, and service usage data? Which features are the most significant in driving churn, and what actionable insights can help reduce it?

#### Data Sources

The Telco Customer Churn dataset from Kaggle serves as the primary data source. It contains information about customer demographics, account details, service usage, and churn status.

#### Methodology

1. **Data Cleaning**: Address missing values and correct data types (e.g., handling empty strings in TotalCharges).
2. **Exploratory Data Analysis**: Analyze and visualize relationships between features and churn.
3. **Feature Engineering**: Create new features, such as TotalServices, Tenure_Year, and interaction terms, to enhance predictive power.
4. **Preprocessing**: Scale numerical features, encode categorical variables, and handle missing values using pipelines.
5. **Correlation Analysis**: Identify significant relationships between numerical variables and churn.
6. **Feature Preparation**: Prepare the processed data for machine learning modeling.
7. **Model Development and Testing**: Build machine learning models and training them.
8. **Model Evaluation and Comparison**: Evaluting machine models and compraing them.

#### Results
Preliminary analysis indicates that churn is associated with shorter tenure, higher monthly charges, and lower total charges. Engineered features such as TotalServices and Tenure_Year provide additional predictive insights. These findings suggest that retention efforts should focus on customers with high monthly charges and those in their early tenure phase.
The results for machine learning models:

- Logistic Regression: Accuracy 0.8168, ROC AUC 0.8638
- Gradient Boosting: Accuracy 0.8083, ROC AUC 0.8655
- Random Forest: Accuracy 0.8034, ROC AUC 0.8541

The Logistic Regression model showed the highest accuracy, while the Gradient Boosting model had the best ROC AUC score. Detailed performance metrics and visualizations can be found in the `Complete_Pipeline.ipynb` notebook.

#### Next Steps
1. Explore potential business recommendations and implement retention campaigns.