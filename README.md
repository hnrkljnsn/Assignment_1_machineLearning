# Assignment 1 - Ames housing dataset price prediction

## The process:
### Data Exploration and Missing Values
Explored the dataset and checked for missing values. Sorted the missing values based on how much data was missing.
After sorting we saw that the following columns were missing the most values:
* Pool Qc: 2917 missing values
* Misc Feature: 2824 missing values
* Alley: 2732 missing values
* Fence: 2358 missing values
* Fireplace Qc: 1422 missing values

The columns above was dropped beacuse of their large amount of missing values.

### Correlation analysis
Correlation analysis was performed to identify features that had the strongest relationships with the target variable, SalePrice. The following features were highly correlated and selected for the prediction model:
* Overall Qual: Correlation ≈ 0.80.
* Gr Liv Area: Correlation ≈ 0.71.
* Garage Cars: Correlation ≈ 0.65.
* Garage Area: Correlation ≈ 0.64.
* Total Bsmt SF: Correlation ≈ 0.63.
* 1st Flr SF: Correlation ≈ 0.62.
* Year Built: Correlation ≈ 0.56.

### Visualize the Correlation analysis data
The data from the correlation analysis was visualized using scatterplot.
![image](https://github.com/user-attachments/assets/ec7fb9e6-4fd6-499b-855a-4c454c32e442)

### Model selection and comparison
Three models were applied to predict house prices:

* Linear Regression: A simple model that assumes a linear relationship between the features and the target variable.
* Polynomial Regression: Extends linear regression by allowing for nonlinear relationships between features and the target.
* Random Forest Regressor: An ensemble model that combines multiple decision trees to improve performance by reducing variance and overfitting.


## Conclusion
The most important features for predicting house prices were identified through correlation analysis, focusing on variables related to house size, quality, and age.

The high correlation of features like Overall Qual, Gr Liv Area, and Garage Cars with SalePrice helped improve the model's accuracy by focusing on the most relevant features.

Polynomial regression and random forest regression provided better accuracy than linear regression because they can handle more complex relationships between features and house prices. 

![image](https://github.com/user-attachments/assets/ba45cded-5eec-48e0-b1ab-86fec6893b01)



