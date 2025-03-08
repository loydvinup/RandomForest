Customer Churn Prediction - Random Forest Classifier
Dataset Overview

This project uses the Customer Churn dataset (customer_churn.csv), which contains telecom customer details. The dataset includes information about contract types, service usage, and billing details to predict whether a customer will churn.
Key Features:

    Tenure – Duration of customer subscription
    TotalCharges – Total amount charged
    TechSupport, InternetService, Contract Type – Service-related features
    Churn (Target Variable) – 1 = Churned, 0 = Retained

Approach Used
1️⃣ Data Preprocessing

    Handled missing values (TotalCharges) by imputing the mean
    Encoded categorical variables using Label Encoding
    Dropped irrelevant columns like customerID

2️⃣ Exploratory Data Analysis (EDA)

    Checked data distributions and outliers
    Visualized feature distributions and churn rates using seaborn

3️⃣ Model Training - Random Forest Classifier

    Implemented RandomForestClassifier from scikit-learn
    Used train-test split (70-30) for model training
    Tuned n_estimators (number of trees) to optimize performance

4️⃣ Evaluation & Results

    Measured accuracy, precision, recall, and F1-score
    Visualized performance using a confusion matrix heatmap

Technologies Used

🚀 Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
