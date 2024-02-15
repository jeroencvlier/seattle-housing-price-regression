
# Real Estate Price Prediction Project

## Overview
This project aims to build a machine-learning model to predict the selling prices of houses based on various features. Utilizing a comprehensive dataset of approximately 22,000 properties with historic sales data from May 2014 to May 2015, we explore the intricate relationship between house features and their selling prices. The goal is to provide actionable insights to our real estate company, enabling data-driven decision-making for pricing strategies.

## Objective
To develop a predictive model that accurately forecasts house selling prices, allowing the company to understand the factors contributing to higher property values, specifically those over $650K. Additionally, the project seeks to leverage business intelligence tools to visually explore these characteristics for strategic planning.

## Data Description
The dataset comprises details of 22,000 properties, including:

- **Id**: Unique identifier for the property.
- **Date**: The date the house was sold.
- **Price**: Selling price of the house.
- **Waterfront**: Indicates if the house has a waterfront view.
- **Condition**: Overall condition of the house.
- **Grade**: Overall grade given to the housing unit, based on King County grading system.
- Other features include square footage of the house (excluding basement), living room area in 2015, lot size area in 2015, and several more.

## Tools and Technologies
- **Python**: For data processing and modelling.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Pandas** & **NumPy**: For data manipulation and numerical calculations.
- **Matplotlib** & **Seaborn**: For data visualization.
- **Tableau**: For business intelligence insights and visual exploration of data.

## Methodology
1. **Data Cleaning**: Handling outliers and missing values to ensure data quality.
2. **Feature Engineering**: Creating new variables to better capture the essence of the data.
3. **Model Selection**: Evaluating various regression models, including Linear Regression, Decision Trees, Random Forest, and more, to find the best fit for our data.
4. **Model Evaluation**: Using R² score, MAE, MSE, and RMSE as benchmarks for performance comparison.
5. **Business Intelligence Analysis**: Utilizing Tableau for a deeper visual analysis of which factors contribute to higher property values.

## Results
The best-performing model achieved an R² score of 0.8, indicating a strong ability to predict house prices based on the given features. Further analysis in Tableau revealed that waterfront properties and those with higher grades significantly impact the selling price.

## Contributing
We welcome contributions and suggestions. Please fork the repository and submit pull requests for any enhancements.

## License
Distributed under the MIT License. See `LICENSE` for more information.

