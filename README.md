# House Price Prediction

## Overview
This project implements a **Linear Regression Model** to predict house prices based on their square footage, number of bedrooms, and number of bathrooms. The goal is to use historical housing data to develop a predictive model that provides accurate price estimates for new data.

## Features
- Predicts house prices using:
  - Square footage
  - Number of bedrooms
  - Number of bathrooms
- Provides a simple and interpretable linear regression model.
- Can be used as a foundation for more advanced models and features.

## Dataset
The dataset used in this project contains information about houses, including:
- **Square Footage:** Total living area in square feet.
- **Number of Bedrooms:** The number of bedrooms in the house.
- **Number of Bathrooms:** The number of bathrooms in the house.
- **Price:** The selling price of the house (target variable).

## Requirements
To run this project, you need the following tools and libraries installed:

- Python 3.7+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (optional for visualizations)

You can install the required libraries using:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage
### 1. Clone the Repository
```bash
git clone https://github.com/mukul2309/PRODIGY_ML_01.git
```

### 2. Predict New Data
You can update the `submission.csv` file with new house details and use the model to predict prices.

## Model Details
The project uses **Simple Linear Regression** and **Multiple Linear Regression** depending on the input features:
- The model finds the best-fit line that minimizes the error between predicted and actual house prices.

### Metrics Used:
- **Mean Squared Error (MSE)**
- **R-squared (R²)**


## Future Improvements
- Add additional features like location, year built, and lot size.
- Implement feature scaling and normalization for better performance.
- Explore advanced models like Decision Trees, Random Forests, or Gradient Boosting.
- Deploy the model as a web application using Flask or Streamlit.
