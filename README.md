# Walmart-Sales-Prediction
This project involves exploring a historical dataset of supermarket weekly sales from 2010 to 2012 and creating models to predict weekly sales for the given stores. The dataset contains information about sales, holidays, temperature, fuel price, CPI, and unemployment rate for each week

## Dataset Overview
The dataset, "Walmart Dataset (Retail)," includes the following columns:

1. Store: The Store ID number.
2. Date: The week of sales.
3. Weekly_Sales: Sales record in the week for the given store (target variable).
4. Holiday_Flag: Indicates whether the week has a public holiday or not (1: holiday week, 0: non-holiday week).
5. Temperature: Average temperature of the week.
6. Fuel_Price: Average fuel price for the week in the region.
7. CPI: Prevailing Consumer Price Index.
8. Unemployment: Prevailing Unemployment Rate.

## Holiday Events

The dataset includes four holiday events:

1. Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
2. Labor Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
3. Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
4. Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

## Project Structure
The project will follow the following structure:
1. Data Import: Load the dataset "Walmart_Store_sales.csv" and perform initial data inspection.

2. Exploratory Data Analysis (EDA): Conduct exploratory data analysis to gain insights into the dataset, visualize the distributions, and analyze the relationships between variables.

3. Feature Selection: Select relevant features for modeling based on correlation analysis and domain knowledge.

4. Model Development: Build predictive models to forecast weekly sales. We will start with a simple Linear Regression model and may explore more sophisticated algorithms like Random Forest or XGBoost.

5. Model Evaluation: Evaluate the model's performance using metrics such as Mean Squared Error (MSE) and R-squared.

6. Conclusion: Summarize the findings from the analysis and model development.

Recommendation and Benefits: Provide recommendations based on the insights gained from the analysis and discuss the benefits of using predictive models for sales forecasting in the supermarket business.

## Repository Contents
The repository will contain the following files:

1. Walmart_Store_sales.csv: The dataset file containing historical supermarket weekly sales data.
2. Exploratory_data_analysis.ipynb: A Jupyter notebook with the code for exploratory data analysis.
3. model_development.ipynb: A Jupyter notebook with the code for model development and evaluation.
4. README.md: This readme file providing an overview of the project and its contents.



## Conclusion
This project aims to gain insights from historical supermarket sales data and develop models to predict weekly sales. The analysis and predictive models can be valuable for supermarket management to make informed decisions, plan inventory, and optimize their business operations.

Feel free to explore the code, findings, and recommendations in the provided Jupyter notebooks. If you have any questions or feedback, please do not hesitate to reach out.

Happy exploring and modeling!
