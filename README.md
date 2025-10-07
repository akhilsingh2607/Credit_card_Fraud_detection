# Credit_card_Fraud_detection
🧠 Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques.
The model helps identify potential frauds from real-world transaction data, improving financial security and reducing business losses.

⚙️ Tools & Technologies Used

Python (Jupyter Notebook)

Pandas, NumPy, Matplotlib, Seaborn – Data preprocessing and visualization

Scikit-learn – Model training and evaluation

SMOTE – Handling class imbalance

Logistic Regression, Random Forest, Decision Tree – Model experimentation

📈 Dataset Overview

Source: Kaggle – Credit Card Fraud Dataset

Transactions: 284,807

Fraudulent Transactions: 492 (~0.172%)

Imbalance Ratio: 1:577

🔍 Key Steps

✅ Data Cleaning & Preprocessing:
Removed nulls, scaled features, and separated target variables.

✅ EDA (Exploratory Data Analysis):
Visualized transaction patterns, correlations, and fraud distribution.

✅ Feature Engineering:
Created balanced datasets using SMOTE (Synthetic Minority Over-sampling Technique).

✅ Model Building:
Trained multiple models and compared accuracy, precision, recall, and F1-score.

✅ Model Evaluation Metrics:

Accuracy: 99.93%

Precision: 94%

Recall: 90%

F1 Score: 92%

✅ Result:
Random Forest Classifier gave the best performance with high precision and recall, effectively detecting fraudulent transactions while minimizing false positives.

📊 Visualizations

Fraud vs. Non-Fraud Transaction Distribution

Correlation Heatmap of Features

Precision-Recall Curve

Confusion Matrix Visualization

🧩 Business Impact

Helps banks and financial institutions reduce financial loss and prevent fraud.

Demonstrates how machine learning can enhance security analytics in real-world financial datasets.

🚀 Future Enhancements

Integrate real-time transaction stream analysis

Implement Deep Learning (LSTM/Autoencoder) for anomaly detection

Deploy as a REST API for live fraud detection
