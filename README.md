# Anomalydetectionoftransactions
# overview
Anomaly detection in transactions means identifying unusual or unexpected patterns within transactions or related activities. These patterns, known as anomalies or outliers indicates irregular or fraudulent behaviour.
# Prerequisites
1. Pip
2. Python
3. Jupyter Notebook
# Libraries
1. Pandas
2. Matplotlib
3. Seaborn
4. Scikit-learn
# Dataset
The dataset contains information about various financial transactions, each represented by several features:
1. Transaction_ID: Unique identifier for each transaction.
2. Transaction_Amount: The monetary value of the transaction.
3. Transaction_Volume: The quantity or number of items/actions involved in the transaction.
4. Average_Transaction_Amount: The historical average transaction amount for the account.
5. Frequency_of_Transactions: How often transactions are typically performed by the account.
6. Time_Since_Last_Transaction: Time elapsed since the last transaction.
7. Day_of_Week: The day of the week when the transaction occurred.
8. Time_of_Day: The time of day when the transaction occurred.
9. Age: Age of the account holder.
10. Gender: Gender of the account holder.
11. Income: Income of the account holder.
12. Account_Type: Type of account (e.g., personal, business).
# Description
1. Create a virtual environment
2. Load the transaction_anomalies_dataset.csv file for the project
3. Install the necessary libraries
4. Run the code for execution
5. Predict the model by using IsolationForest
# Advantages of Isolation Forests
1. Effective for Unlabeled Data: Isolation Forests do not require labeled data (normal vs. anomaly) for training, making them suitable for scenarios where labeled data is scarce.
2. Efficient for High-Dimensional Data: The algorithm scales well with high-dimensional data sets, which can be challenging for other anomaly detection methods.
3. Robust to Noise: Isolation Forests are relatively insensitive to noise and outliers within the data, making them reliable for real-world datasets.
# Evaluation metrics
Precision: Normal: 1.00 Anomaly: 1.00
Recall: Normal: 1.00 Anomaly: 1.00
Accuracy: 1.00
