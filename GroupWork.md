# Group work document
## Introduction
For this assignment, we worked as a team to predict house sale prices using the Ames
housing dataset. We collaborated throughout the process, dividing tasks efficiently while
supporting each other to ensure effective completion of data pre-processing, visualization,
and feature engineering.

## Key Steps
1. ### Data Pre-processing
The first step was to pre-process the data. We handled missing dropping data which
was unnecessary. During this stage, we made decisions about which features to keep
or transform
For example, we analyzed features such as 'OverallQual' and 'GrLivArea,' both of
which were strong indicators of house prices These decisions were made jointly after
assessing the impact of each step on the model's performance.

2. ### Feature Engineering and Visualization
Feature engineering played a crucial role in our project. We conducted correlation
analysis and plotted heatmaps to understand the relationships between various
features and the target variable, 'Sale Price.' This helped us identify key features that
had a strong correlation with the house prices, such as 'OverallQual,' 'GrLivArea' and
'GarageCars.'
To visualize these relationships, we generated scatter plots. This helped us
communicate insights effectively.

3. ### Model Implementation and Comparison
We implemented three models: Linear Regression, Polynomial Regression, and
Random Forest Regressor. Each model was evaluated using Mean Squared Error
(MSE) and R-squared to measure their accuracy. We concentrated on understanding
how each model interacted with the selected features and what their respective
strengths and weaknesses were.
Linear Regression served as a baseline model, and it performed decently with an Rsquared value of 0.817. Polynomial Regression, though more complex, provided a
better fit with an R-squared of 0.879, showing the advantage of capturing non-linear
relationships in the data. Finally, the Random Forest Regressor offered comparable
performance (R-squared of 0.878) but with the added benefit of being more robust to
overfitting.

## Conclusion
Working together on this assignment gave us valuable insights into data pre-processing,
feature engineering, and model evaluation. Our close collaboration allowed us to balance the
workload and effectively share knowledge
In the future, we could improve our workflow by having more frequent check-ins and
exploring advanced model-tuning techniques to improve accuracy further. Nonetheless, this
project demonstrated how effective teamwork can enhance learning and produce high-quality
work.
