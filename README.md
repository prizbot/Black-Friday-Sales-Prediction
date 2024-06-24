# Black Friday Sales Prediction

## Overview
This project aims to predict customer purchase behavior during the Black Friday sales event. Using a comprehensive dataset provided by a retail company, the project explores various customer demographics, product details, and purchase amounts. The dataset includes attributes such as user ID, product ID, gender, age, occupation, city category, years spent in the current city, marital status, and product categories. The target variable is the purchase amount.

## Data Exploration and Analysis
The dataset was thoroughly analyzed to understand the distribution and characteristics of each attribute. Key findings include:

- **Gender Distribution:** More males participate in Black Friday sales, with males also spending more on average than females.
- **Age Groups:** The age group 26-35 is the most active in purchases, although average spending is consistent across age groups.
- **City Categories:** City category B has the highest number of purchases, but buyers from city category C spend the most on average.
- **Marital Status:** Unmarried individuals tend to make more purchases, although the average purchase amount is similar for both married and unmarried individuals.
- **Occupations:** The dataset includes 20 different occupations, with similar average spending across these occupations.
- **Product Categories:** Certain product categories, such as 1, 5, and 8, see higher sales volumes.

## Data Preprocessing
The data was preprocessed to handle missing values, encode categorical variables, and drop irrelevant columns. Missing values in product categories 2 and 3 were filled with zeroes, and categorical variables were converted to numerical values using label encoding and dummy variables.

## Modeling
Three regression models were implemented to predict the purchase amount:

- **Linear Regression:** This model provided a baseline for comparison.
- **Decision Tree Regressor:** This model aimed to capture non-linear relationships in the data.
- **Random Forest Regressor:** This ensemble method improved prediction accuracy by reducing overfitting.

## Model Performance
Each model's performance was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score. The Random Forest Regressor provided the best performance, highlighting its ability to handle the complexity of the dataset.

## Conclusion
This project demonstrates the process of predicting customer purchase behavior using machine learning techniques. By understanding the factors influencing purchase amounts, retailers can tailor their marketing strategies and offers to different customer segments, ultimately enhancing sales during major events like Black Friday.

## Contact

Feel free to reach out if you have any questions or suggestions:

- **LinkedIn**: [Priyadharshini NRS](https://www.linkedin.com/in/priyadharshininrs)
- **Email**: priyadharshininrs@gmail.com
