# Telco Customer Churn Prediction

## Project Overview
This project aims to predict customer churn for a telecommunications company using machine learning techniques. We analyze the Telco Customer Churn dataset to identify key factors contributing to churn and develop predictive models to help the company implement targeted retention strategies. This project follows a structure similar to the provided sample projects (Detecting Suicide Ideation-2 and Predictive Maintenance) but focuses on the telecom industry's specific challenges.

## Table of Contents
1. [Installation](#installation)
2. [Project Structure](#project-structure)
3. [Usage](#usage)
4. [Data](#data)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Business Recommendations](#business-recommendations)
8. [Presentation](#presentation)
9. [Non-Technical Report](#non-technical-report)
10. [Future Work](#future-work)
11. [Contributing](#contributing)
12. [License](#license)

## Installation
To run this project, you need Python 3.7+ and the following libraries:

## Installation
To run this project, you need Python 3.7+ and the following libraries:
numpy pandas matplotlib seaborn scikit-learn xgboost joblib



## Project Structure
- `EDA_and_Feature_Engineering.ipynb`: Exploratory Data Analysis and Feature Engineering
- `Logistic_Regression_Model.ipynb`: Logistic Regression model implementation
- `Gradient_Boosting_Model.ipynb`: Gradient Boosting model implementation
- `Random_Forest_Model.ipynb`: Random Forest model implementation
- `Model_Comparison.ipynb`: Comparison of all models and final conclusions
- `data/`: Directory containing the Telco Customer Churn dataset
- `models/`: Directory containing saved model files
- `Telco_Churn_Prediction_Presentation.pptx`: Presentation slides summarizing the project
- `Non_Technical_Report.pdf`: Non-technical summary of findings and recommendations
- `README.md`: This file
- `requirements.txt`: List of required Python packages

## Usage
1. Clone this repository to your local machine.
2. Install the required packages as described in the [Installation](#installation) section.
3. Run the Jupyter notebooks in the following order:
   - `Complete_Pipeline.ipynb`
4. Each notebook contains detailed comments and markdown cells explaining the process and findings.
5. Review the `Telco_Churn_Prediction.pptx` for a summary of key findings.
6. Read the `Report.pdf` for business-oriented insights and recommendations.

## Data
The Telco Customer Churn dataset contains information about a telecom company's customers, including:
- Customer demographics (gender, age range, partners, dependents)
- Account information (tenure, contract type, payment method)
- Services used (phone, internet, tech support, streaming TV and movies)
- Charges (monthly and total)
- Churn status

The dataset is available in the `data/` directory. For more details on the dataset, refer to the `EDA_and_Feature_Engineering.ipynb` notebook.

## Methodology
1. Problem Statement and Initial Data Analysis:
   - Define the problem of customer churn prediction
   - Perform Exploratory Data Analysis (EDA) on the Telco Customer Churn dataset
   - Visualize key features and their relationships to churn
2. Feature Engineering:
   - Handle missing values
   - Encode categorical variables
   - Scale numerical features
3. Model Development and Testing:
   - Logistic Regression
   - Gradient Boosting
   - Random Forest
4. Model Evaluation and Comparison:
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC score
   - Feature importance analysis

## Results
- Logistic Regression: Accuracy 0.8168, ROC AUC 0.8638
- Gradient Boosting: Accuracy 0.8083, ROC AUC 0.8655
- Random Forest: Accuracy 0.8034, ROC AUC 0.8541
- Neural Network: Accuracy 0.8128, ROC AUC 0.8627

The Logistic Regression model showed the highest accuracy, while the Gradient Boosting model had the best ROC AUC score and the Neural Network had the good balance between precision and recall. Detailed performance metrics and visualizations can be found in the `Model_Comparison.ipynb` notebook.

## Business Recommendations
1. Focus on long-term contracts to reduce churn risk
2. Develop targeted retention programs for customers in early tenure periods
3. Review pricing strategies, especially for customers with high total charges
4. Implement the Logistic Regression model for general use due to its high accuracy and interpretability
5. Consider using the Gradient Boosting model for precise probability rankings in specific scenarios

For a comprehensive list of recommendations and their rationale, please refer to the `Report.pdf`.

## Presentation
A detailed presentation (`Telco_Churn_Prediction.pptx`) has been created based on the provided reference PPT. It includes:
- Project overview and objectives
- Key findings from the EDA phase
- Model performance comparisons
- Feature importance analysis
- Business insights and recommendations

## Non-Technical Report
A non-technical report (`Report.rtf`) has been prepared, focusing on:
- Executive summary of the project
- Key findings in business-friendly language
- Actionable insights for reducing customer churn
- Recommendations for implementation and future steps

## Future Work
- Explore advanced feature engineering techniques
- Investigate deep learning models for churn prediction
- Develop a user-friendly dashboard for business users
- Implement a system for periodic model retraining and evaluation
- Conduct A/B testing on recommended retention strategies

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.