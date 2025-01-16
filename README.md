# House-Price-Prediction
# House Price Prediction

This project predicts house prices based on various features such as area, number of bedrooms, bathrooms, stories, parking spaces, and more. It demonstrates the full pipeline of a machine learning project, including data preprocessing, exploratory data analysis, feature engineering, and model evaluation.

## Features
- Data cleaning and handling missing values
- Outlier detection and removal
- Exploratory data analysis using visualizations
- Feature engineering and scaling
- Building and evaluating a linear regression model
- Residual analysis and error term visualization
- Model evaluation using R² score

## Dependencies
To run this project, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels

Install them using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```


How to Use
1.Clone this repository:
```bash
git clone https://github.com/yourusername/house-price-prediction.git
```
2.Navigate to the folder:
```bash
cd house-price-prediction
```
3.Run the script:
```bash
python house_price_prediction.py
```

**Workflow**

1.Data Inspection:

  Display dataset shape, column info, and basic statistics.
  
2.Data Cleaning:

  Handle missing values and remove outliers using IQR.  
  
3.EDA:

  Visualize relationships between features and the target variable.
  
4.Feature Engineering:

  Encode categorical variables and scale numerical features.
  
5.Model Building:

  Use Recursive Feature Elimination (RFE) and OLS for feature selection.
  
6.Model Evaluation:

  Evaluate the model using R² score and residual analysis.

  
**Results**  
  The model achieves a good fit with insights into significant features affecting house prices.
Visualizations provide a clear understanding of data relationships.
