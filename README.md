# Diamond Price Prediction

## Overview
This project focuses on predicting diamond prices using regression models. The dataset consists of various attributes that affect the price of a diamond, such as carat, cut, color, clarity, and more. The goal is to develop an accurate regression model that can estimate diamond prices based on these features.

## Dataset
The dataset includes the following features:
- **Carat**: Weight of the diamond
- **Cut**: Quality of the cut (e.g., Fair, Good, Very Good, Premium, Ideal)
- **Color**: Diamond color grade (e.g., J, I, H, G, F, E, D)
- **Clarity**: Measurement of how clear the diamond is (e.g., I1, SI2, SI1, VS2, VS1, VVS2, VVS1, IF)
- **Depth**: Total depth percentage
- **Table**: Width of the top of the diamond relative to the widest point
- **Price**: Price of the diamond (target variable)
- **X, Y, Z**: Dimensions of the diamond

## Methodology
1. **Data Preprocessing**
   - Handling missing values (if any)
   - Encoding categorical variables
   - Feature scaling and transformation
2. **Exploratory Data Analysis (EDA)**
   - Understanding correlations between features
   - Visualizing distributions and relationships
3. **Model Selection & Training**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - Support Vector Regression (SVR)
   - Gradient Boosting Models
4. **Evaluation**
   - Metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), R-squared (R²)
   - Model comparison and selection

## Requirements
To run the project, install the required dependencies using:
```sh
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook to execute the analysis and model training:
```sh
jupyter notebook Regression_Diamonds.ipynb
```

## Results
The final model with the best performance will be used to predict diamond prices, and its performance metrics will be reported.

## Future Work
- Improve model accuracy with hyperparameter tuning
- Explore deep learning models for regression

## License
This project is open-source and available under the [MIT License](LICENSE).

