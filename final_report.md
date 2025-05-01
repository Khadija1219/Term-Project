# Insurance Cost Prediction

## Introduction & Dataset Description
This project explores a real-world dataset of insurance policyholders to predict medical charges based on demographic and behavioral features such as age, BMI, smoking status, and region. The dataset contains 1338 rows and includes both numerical and categorical variables.

## Exploratory Data Analysis (EDA)
EDA revealed strong relationships between smoking status, BMI, and insurance charges. Smokers had significantly higher charges. Age and BMI showed moderate correlation with charges. Regional differences were minimal.

## Preprocessing
Categorical variables were encoded, and numeric features were standardized. The data was split into training and testing sets (80/20).

## Business Questions
- Can we predict medical charges based on personal and behavioral traits?
- How does smoking impact insurance costs?

## Modeling
Two models were used:
- **Linear Regression**
- **Random Forest Regressor**

### Performance Comparison
| Model             | RMSE     | R² Score |
|------------------|----------|----------|
| Linear Regression| 5796.28 | 0.784 |
| Random Forest    | 4534.1 | 0.868 |

Random Forest performed better in both RMSE and R² metrics.

## Insights
- Smoking is the most important cost driver.
- Age and BMI also affect charges.
- Random Forest is more suitable for modeling nonlinear relationships.

## Ethical Reflection (Minimal)
The model may reflect biases present in the dataset (e.g., regional or behavioral). It’s essential not to use such models to penalize individuals without transparency.

