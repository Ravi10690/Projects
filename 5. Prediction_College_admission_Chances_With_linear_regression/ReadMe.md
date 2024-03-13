## Jamboree Graduate Admission Analysis and Prediction

## Problem Statement
Jamboree, a leading educational service provider, aims to assist students in predicting their chances of admission to IVY league colleges. The project involves understanding the factors influencing graduate admissions and developing a predictive model for admission probability from an Indian perspective.

## Dataset Overview
- **Columns:**
  - Serial No. (Unique row ID)
  - GRE Scores (out of 340)
  - TOEFL Scores (out of 120)
  - University Rating (out of 5)
  - Statement of Purpose and Letter of Recommendation Strength (out of 5)
  - Undergraduate GPA (out of 10)
  - Research Experience (either 0 or 1)
  - Chance of Admit (ranging from 0 to 1)

## Key Questions Explored
1. What factors significantly influence graduate admissions?
2. How do these factors interrelate among themselves?
3. Can a predictive model accurately estimate admission probability?

## Analysis Steps

### 1. Define Problem Statement and Perform Exploratory Data Analysis
- Clearly define the problem statement based on Jamboree's objective.
- Perform exploratory data analysis (EDA) to understand the dataset's structure and characteristics.

### 2. Data Preprocessing.
- Check for duplicate values.
- Address missing values.
- Treat outliers.
- Conduct feature engineering for model improvement.
- Prepare data for modeling.

### 3. Model Building.
- Build a Linear Regression model to predict admission probability.
- Display model coefficients with column names.
- Experiment with Ridge and Lasso regression for model refinement.

### 4. Testing Assumptions of Linear Regression Model 
- Check for multicollinearity using VIF scores.
- Verify the mean of residuals is nearly zero.
- Assess linearity of variables (no pattern in residual plot).
- Test for homoscedasticity.
- Validate normality of residuals (bell-shaped curve in residuals distribution, QQ plot alignment).

### 5. Model Performance Evaluation 
- Evaluate metrics such as MAE, RMSE, R2, and Adjusted R2.
- Check both train and test performances.
- Provide comments on performance measures and suggest model improvements if needed.

### 6. Actionable Insights & Recommendations 
- Interpret significance of predictor variables.
- Suggest additional data sources for potential model improvement.
- Discuss model implementation in real-world scenarios and potential business benefits.

## Conclusion
The project successfully addresses Jamboree's objective by analyzing graduate admission data, building a predictive model, and providing actionable insights. The Linear Regression model, along with Ridge and Lasso regressions, undergoes thorough testing and evaluation. Recommendations are made for potential improvements and real-world implementation.

