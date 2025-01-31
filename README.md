# California Housing Price Prediction with Multiple Linear Regression

## Overview  
This project builds a Multiple Linear Regression model to predict housing prices in California using the `fetch_california_housing` dataset. The workflow includes data exploration, preprocessing, model training, evaluation, and visualization.

## Dataset  
- **Source**: `fetch_california_housing` from scikit-learn.  
- **Features**: 8 numerical attributes (e.g., median income, house age).  
- **Target**: Median house value (in hundreds of thousands of dollars).  

## Tools & Libraries  
- Python, Jupyter Notebook  
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn  

## Steps  
1. **Data Preparation**: Load and explore the dataset.  
2. **EDA**: Correlation analysis and pairplots.  
3. **Preprocessing**: Train-test split and standardization.  
4. **Model Training**: Linear Regression and Polynomial Regression.  
5. **Evaluation**: MAE, MSE, RMSE, R², and residual analysis.  

## Results  
- **Linear Regression**:  
  - R² Score: ~0.60  
  - MAE: ~0.53  
- **Polynomial Regression**:  
  - Slight improvement in R² (~0.65).  

## How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/yourusername/california-housing-regression.git  
