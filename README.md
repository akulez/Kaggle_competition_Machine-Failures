# Binary-Classification-of-Machine-Failures
This project was completed as part of the Playground Series 3 Episode 17 Challenge organized by Kaggle, an online Data Science Platform which oragnises competitions
for the Data Science Community. The challenge focused on Binary Classification of Machine Failures. The project involved several steps, as listed below:

1. **Data Analysis and Preprocessing**
   - Utilised various descriptive analysis tools to conduct in depth analysis of the data in hand.
   - Removed unnecessay columns which were predominantly dominated by one class.
   - Plotted many visualizations using Seaborn and Matplot Library to understand the distributions of variables and also plotted heatmaps to understand correlations within variables
   - Also replaced Outliers with median, instead of totally removing the outliers, and also finally encoded the variables.

2. **Feature Engineering and Selection:**
   - Created new features to capture additional information about the data which included polynomial as well as some interactive features.
   - Performed feature selection using a combination of p value scores and Ridge Regression to select the best 8 features for making predicting.

3. **Model Fitting, Hyperparameter Tuning Evaluations:**
   - Firstly used GridSearchCV to fidn the best parameters for 3 models - AdaBoost, Random forests and XGBoost
   - Then utilised a voting classifier to combine these models and create a model which can better fit in the data.
   - Evaluated the models using a accuracy score, confusion matrix and other metrics including precision, recall and f1 scores.

