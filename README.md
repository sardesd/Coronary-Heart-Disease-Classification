Coronary Heart Disease Classification
Description
This project aims to predict the presence of coronary heart disease within the next ten years for individuals based on various health metrics. The machine learning models used include K-Nearest Neighbors (KNN), Random Forest, XGBoost, Support Vector Classifier (SVC), and a Voting Classifier that combines multiple models.

Data Preprocessing
The data is cleaned and preprocessed, handling any missing values, outliers, or skewed distributions as necessary. Categorical variables like sex and smoking status are binary encoded.

Feature Selection/Engineering
The relationships between the different features and the target variable are analyzed to identify the most relevant features. New features may also be created to improve the model’s performance.

Model Selection
Various machine learning models suitable for binary classification tasks are experimented with, such as K-Nearest Neighbors (KNN), Random Forest, XGBoost, Support Vector Classifier (SVC), and others. Ensemble methods like Voting Classifier are also explored to combine the strengths of multiple models.

Hyperparameter Tuning
Techniques like GridSearchCV or RandomizedSearchCV are used to find the optimal hyperparameters for the models.

Model Evaluation
The models are evaluated using appropriate metrics such as accuracy, precision, recall, F1 score, and Area Under the ROC Curve (AUC-ROC). The ROC curves of the models are also plotted to visualize their performance.

Variables Description
The dataset contains the following variables:

Date: The specific day when the data was collected.

Rented Bike Count: The total number of bikes rented on a particular day.

Hour: The specific hour of the day when the data was recorded.

Temperature(°C): The outside temperature, measured in degrees Celsius.

Humidity(%): The amount of water vapor in the air, measured as a percentage.

Wind speed (m/s): The wind speed, measured in meters per second.

Visibility (10m): The visibility distance, measured in tens of meters.

Dew point temperature(°C): The temperature at which dew starts to form, measured in degrees Celsius.

Solar Radiation (MJ/m2): The amount of solar energy hitting a square meter of the ground.

Rainfall(mm): The amount of rain that fell on a particular day, measured in millimeters.

Snowfall (cm): The amount of snow that fell on a particular day, measured in centimeters.

Seasons: The season when the data was recorded (Spring, Summer, Autumn, or Winter).

Holiday: Whether or not the day was a holiday.

Functioning Day: Whether or not the day was a working day.

Conclusion
All three models - Polynomial Regression, XGBoost, and Random Forest - were able to predict the ‘Rented Bike Count’ with varying degrees of accuracy.

Polynomial Regression had a training R^2 of 0.79 and a test R^2 of 0.75.
XGBoost performed significantly better, with a perfect R^2 of 1.00 on the training data and 0.94 on the test data.
Random Forest also performed well, with an R^2 of 0.90 on the training data and an impressive 0.99 on the test data.
The Stacking model, which combined the Random Forest and XGBoost models, had performance metrics very similar to those of the XGBoost model.# Coronary-Heart-Disease-Classification
