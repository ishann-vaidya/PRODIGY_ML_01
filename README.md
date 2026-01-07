# House Price Prediction using Linear Regression

This project implements a Linear Regression model to predict house prices using the Kaggle House Prices dataset.

## Dataset
- Source: (https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- Features used:
  - Above Ground Living Area (GrLivArea)
  - Number of Bedrooms (BedroomAbvGr)
  - Number of Bathrooms (FullBath)
- Target:
  - SalePrice

## Steps Performed
- Data loading and exploration
- Feature selection and missing value handling
- Feature scaling using StandardScaler
- Model training using Linear Regression
- Model evaluation using RMSE and R² score
- Visualization:
  - Actual vs Predicted Sale Prices
  - House Price vs Living Area

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn

## Results
The model demonstrates a reasonable fit and highlights the linear relationship between living area and house prices.

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
