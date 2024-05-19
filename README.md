# House-price-prediction
Efficiently predict house prices using machine learning algorithms. Explore advanced models and data preprocessing techniques for accurate and insightful predictions in this engaging project.

# Introduction
This project challenges data science enthusiasts with a regression and time series forecasting assignment, providing an ideal opportunity for those familiar with Python and basic machine learning concepts. Tailored for students who have completed an online machine learning course, the project focuses on predicting house prices in Ames, Iowa, using 79 explanatory variables. By exploring advanced regression techniques such as random forest and gradient boosting, participants will refine their feature engineering skills and address missing data challenges.

# Objective
1. **Experiment with Various Regression Methods:** Utilize different regression methods, including Random Forest Regressor, Decision Tree Regressor, MLP Regressor, Support Vector Regressor, and Gradient Descent Regressor. Implement hyperparameter tuning with cross-validation to enhance predictive accuracy.
2. **Ensemble Predictions Through Stacking:** Perform one-layer stacking by combining outputs from top-performing algorithms such as Decision Tree, Random Forest, and Support Vector Machines. Explore different combinations for optimal predictive performance.
3. **Hyperparameter Tuning for Stacked Model:** Conduct hyperparameter tuning with cross-validation specifically for the stacked model, refining parameters to achieve optimal performance.

# Dataset
This project leverages the Ames Housing dataset, meticulously compiled by Dean De Cock for data science education. With 79 explanatory variables capturing nearly every aspect of residential homes in Ames, Iowa, this dataset serves as the focal point of a Kaggle competition. Your task is to predict the final price of each home, going beyond conventional considerations. Explore creative feature engineering and advanced regression techniques such as random forest and gradient boosting in this Kaggle challenge. For detailed information and to access the dataset, visit the Kaggle competition page:[House Prices Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

# Python Packages Used
1. vecstack
2. pandas
3. numpy
4. plotly.express
5. LabelEncoder, OneHotEncoder from sklearn.preprocessing
6. train_test_split, GridSearchCV, RandomizedSearchCV, cross_val_score from sklearn.model_selection
7. RandomForestRegressor, GradientBoostingRegressor from sklearn.ensemble
8. DecisionTreeRegressor from sklearn.tree
9. MLPRegressor from sklearn.neural_network
10. mean_squared_error, accuracy_score from sklearn.metrics

# Result
The project culminated in refined predictive models, effectively leveraging advanced regression techniques. By employing creative feature engineering and experimenting with diverse algorithms like random forest and gradient boosting, the models achieved enhanced accuracy in predicting house prices. Evaluation metrics, including mean squared error, underscore the models' effectiveness in capturing intricate patterns within the Ames Housing dataset. The ensemble predictions, facilitated through one-layer stacking, demonstrated synergistic insights from decision tree, random forest, and support vector machines. Comprehensive hyperparameter tuning further optimized the stacked model, elevating its predictive performance.
