Customer Churn Prediction - Random Forest Classifier
Overview

This project implements a Random Forest Classifier to predict customer churn using a dataset of telecom customers. It includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and hyperparameter tuning.
Dataset

📂 Dataset Name: customer_churn.csv
📊 Features: Various customer-related attributes, such as:

    tenure: How long a customer has stayed
    TotalCharges: Total amount charged
    TechSupport, InternetService, etc.
    🎯 Target Variable: Churn (1 = Churned, 0 = Retained)
    📉 Goal: Predict if a customer will churn based on their service usage and contract details.

Project Workflow

1️⃣ Data Preprocessing

    Handling missing values (TotalCharges)
    Label encoding categorical variables
    Dropping irrelevant features (customerID)
    2️⃣ Exploratory Data Analysis (EDA)
    Checking feature distributions
    Identifying outliers with box plots
    Visualizing churn distribution
    3️⃣ Model Training & Evaluation
    Implementing RandomForestClassifier
    Hyperparameter tuning (n_estimators)
    Evaluating with accuracy, confusion matrix, and classification report
    4️⃣ Visualization & Results
    Plotting model performance
    Heatmap of confusion matrix

Installation & Usage

    Clone the repository

git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

Install dependencies

    pip install -r requirements.txt

    Run the notebook
        Open RF.ipynb in Jupyter Notebook or Google Colab
        Execute all cells to train and evaluate the model

Results

📊 Model performance was evaluated using:
✔ Accuracy Score
✔ Confusion Matrix
✔ Precision, Recall, and F1-Score
Technologies Used

🚀 Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
