# Flight-Price-Prediction

This project aims to predict the flight prices using regression analysis. The dataset used in this project is in the form of an Excel file, 
which is loaded using the pandas read_excel function. After loading the dataset, we check the complete information of the data, which can indicate 
any hidden information such as null values.

In order to handle null values, we can either impute data using the Imputation method in sklearn or fill NaN values with mean, median, and mode using the fillna() method. Further, we perform Exploratory Data Analysis (EDA) to analyze the data, including converting the Date_of_Journey column into a timestamp and handling categorical data.

We also use feature selection methods to find the best feature that will contribute and have a good relation with the target variable. The model is fitted using the Random Forest algorithm, and the dataset is split into train and test sets. Scaling is not done in Random Forest. we check the RSME score and plot the graph.

Finally, we perform hyperparameter tuning using RandomizedSearchCV or GridSearchCV to find the best parameters and best score. We also use the metrics.r2_score function to evaluate the model's performance.
