# Logistic-Regression-Binary-Classification-
### Logistic Regression Model for Diabetes Prediction

This project focuses on predicting whether a patient is diabetic or non-diabetic using a Logistic Regression classification model. The dataset was cleaned by handling invalid values and treating missing observations appropriately. Exploratory Data Analysis (EDA) was performed to understand data distributions, identify outliers, detect skewness, and analyze relationships between variables.

Feature selection was carried out using the ANOVA F-test (`f_classif`), and multicollinearity was checked using VIF scores. After splitting the data into training and testing sets, feature scaling was applied using StandardScaler. A Logistic Regression model was then trained and evaluated using various performance metrics such as Accuracy Score, Confusion Matrix, Classification Report, ROC-AUC Score, and Log Loss.

The trained model and scaler were saved using Pickle for future use. Additionally, deployment code was developed to load the saved model and scaler, accept user input, preprocess the data, and generate real-time predictions, making the model ready for practical application.

**Key Techniques Used:**

* Data Cleaning and Missing Value Treatment
* Exploratory Data Analysis (EDA)
* Outlier Detection and Treatment
* Feature Selection (`f_classif`)
* Multicollinearity Check (VIF)
* Feature Scaling (`StandardScaler`)
* Logistic Regression
* Model Evaluation (Accuracy, ROC-AUC, Log Loss, Confusion Matrix)
* Model Serialization using Pickle
* Deployment Code for Real-Time Prediction

**Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels, and Pickle.
