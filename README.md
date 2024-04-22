
## Introduction

This project delves into video game sales prediction using machine learning. By analyzing a comprehensive dataset encompassing various features such as platform, genre, release year, and regional sales figures, the goal is to build models that can accurately forecast global video game sales. The dataset employed originates from Kaggle and offers a wealth of information about video games and their performance across different regions.

## Project Goals

1. Develop powerful machine learning models capable of predicting video game sales with high accuracy.
2. Explore and compare the performance of diverse regression algorithms to identify the most effective approach for this task.
3. Gain valuable insights into the key factors that significantly influence video game sales, ultimately contributing to informed decision-making processes within the gaming industry.

## Methodology

### 1. Data Preprocessing

- The dataset was loaded and subjected to initial exploration to understand its structure and contents.
- Data cleaning operations were conducted to address missing values and ensure proper data type conversion.
- Categorical features were transformed into numerical representations using label encoding to facilitate model training.

### 2. Modeling

- The dataset was split into training and testing sets, separating features (independent variables) from the target variable (global sales).
- A variety of regression algorithms were employed:
  - K-Nearest Neighbors (KNN)
  - Multiple Linear Regression (MLR)
  - Decision Tree Regression (DTR)
  - Random Forest Regression (RFR)
  - Gradient Boosting Regression (GBR)
- Hyperparameter tuning and cross-validation techniques were utilized to optimize model performance.
- Model evaluation metrics such as Mean Squared Error (MSE) and R-squared were employed to assess the effectiveness of each model.

### 3. Results

- Each regression model's performance was evaluated using the chosen metrics.
- Model predictions were visualized alongside actual sales figures to gain insights into model behavior.
- The Gradient Boosting Regression model was identified as the top performer based on R-squared scores, demonstrating its superior predictive ability.

## Conclusion

This project successfully developed and evaluated machine learning models for predicting video game sales. The Gradient Boosting Regression algorithm emerged as the most effective model for accurate sales predictions. Insights gleaned from this project can be immensely valuable for stakeholders in the gaming industry, enabling well-informed decisions and strategic resource allocation.


