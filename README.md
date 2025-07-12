# House Price Prediction

This project predicts house prices using various regression models on the King County housing dataset.

## Dataset

https://www.kaggle.com/datasets/harlfoxem/housesalesprediction
- File used: `kc_house_data.csv`

## Preprocessing

- Removed irrelevant columns
- Handled missing data
- Converted year features (`yr_built`, `yr_renovated`) to number of years ago from 2025
- Scaled features where needed (for models like SVR, Ridge, Lasso, etc.)

## Models Used

- Linear Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Support Vector Regressor  
- K-Nearest Neighbors  
- Ridge  
- Lasso  
- ElasticNet  

## Evaluation

Metric: Mean Absolute Error (MAE)
All errors and prices are in USD
| Model               | MAE       |
|--------------------|-----------|
| Linear Regression  | 148,428   |
| Decision Tree      | 146,826   |
| Random Forest      | 123,248   |
| Gradient Boosting  | 130,204   |
| SVR                | 196,637   |
| KNN                | 138,267   |
| Ridge              | 148,426   |
| Lasso              | 148,428   |
| ElasticNet         | 147,204   |

