# Telecom-Churn-Prediction

This project builds a machine learning model using PySpark to predict customer churn in the telecom sector. 
It performs data preprocessing, feature engineering, and uses a Random Forest classifier to identify customers who are likely to churn.

## 🔍 Project Overview

- **Language**: Python with PySpark
- **Model**: Random Forest Classifier
- **Goal**: Predict whether a customer will churn based on behavioral and demographic data
- **Dataset**: `churn_data.csv` (not included in this repo)
  
  
⚙️ Steps Performed

    Load and clean the dataset

    Encode categorical columns using StringIndexer

    Assemble features using VectorAssembler

    Train a RandomForestClassifier

    Evaluate model using accuracy, precision, and recall

📈 Evaluation Metrics

    Accuracy

    Precision

    Recall

These metrics are calculated on a hold-out test set (30% of the data).
📊 Feature Importance

After model training, the script prints the top 10 features contributing to churn prediction.
🚀 How to Run

    Install Apache Spark and PySpark

    Place the dataset CSV file in the appropriate path

    Run the script:

spark-submit telecom_churn_prediction.py

Or in a Jupyter notebook environment:

!python telecom_churn_prediction.py

📦 Dependencies

    PySpark

    Python 3.x

Install PySpark using:

pip install pyspark





