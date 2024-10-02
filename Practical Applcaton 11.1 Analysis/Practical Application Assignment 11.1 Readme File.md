# CRISP-DM Analysis on Used Cars Dataset

# Business Understanding
The goal of this analysis is to understand what factors influence the price of used cars. This will help used car dealerships optimize their inventory and pricing strategies. By identifying key attributes that affect pricing, dealerships can make informed decisions on which cars to stock, how to price them, and what features to highlight in sales efforts. Understanding consumer preferences and the factors that drive car prices is crucial in a highly competitive market. This approach follows the CRISP-DM (Cross Industry Standard Process for Data Mining) methodology, which provides a robust framework for analyzing and solving business problems using data mining techniques (Shearer, 2000).

# Data Understanding and Preparation
The dataset contains various attributes of used cars, including price, year, manufacturer, model, condition, cylinders, fuel type, odometer, title status, transmission, drive type, size, type, paint color, and location information like state and region. Significant data cleaning was performed to address missing values and inconsistencies. Missing values in critical columns like 'year' and 'odometer' were filled with median values, while categorical variables were filled with 'Unknown'. Columns with excessive missing data, such as 'VIN' and 'size', were removed to streamline the analysis. The cleaned dataset was then prepared for exploratory data analysis and modeling, adhering to the data preparation steps outlined in the CRISP-DM process (Shearer, 2000).


# Modeling Attempts and Results
Multiple modeling attempts were made, including Linear Regression and Random Forest. The Linear Regression model showed poor performance, failing to capture complex patterns due to its limitations in handling non-linear relationships and interactions among features. A more sophisticated Random Forest model demonstrated potential for capturing complex interactions between variables but required further optimization for practical deployment. Random Forest, a popular ensemble method, is effective in handling large datasets with complex interactions (Breiman, 2001). The model's performance highlighted that car year, odometer, and manufacturer were significant predictors of price.



# Conclusions and Recommendations
Based on the analysis, it is recommended that dealerships focus on the following factors to optimize their pricing strategies:
•	- Car Age and Mileage: Prioritize inventory with lower mileage and newer models, as these factors significantly impact car prices. Cars with fewer miles and newer manufacturing years command higher prices, aligning with consumer expectations of reliability and performance (Breiman, 2001).
•	- Key Features: Highlight cars with favorable conditions, popular manufacturers, and appealing features that are shown to increase value. Dealerships should ensure these attributes are prominently displayed in listings to attract buyers.
•	- Further Modeling: Continued refinement of predictive models, including feature engineering and the use of advanced algorithms such as Gradient Boosting Machines or Neural Networks, will help improve price predictions and enhance inventory decision-making (Friedman, 2001). Incorporating additional data, such as market demand trends or specific feature availability, could further refine price optimization models.
Overall, this analysis provides a comprehensive view of the used car market and offers actionable insights that dealerships can apply to their pricing strategies. By understanding and leveraging key factors that affect vehicle value, dealerships can better align their inventory with market expectations and enhance profitability.

The jupyter notebook file and related files can be found using Git Hub link below

https://github.com/rajreddys/kraftwerk

