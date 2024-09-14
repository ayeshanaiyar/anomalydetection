# Anomalydetectionoftransactions
Anomaly detection in transactions means identifying unusual or unexpected patterns within transactions or related activities. These patterns, known as anomalies or outliers, deviate significantly from the expected norm and could indicate irregular or fraudulent behaviour.
# Prerequisites
1. Pandas
2. Matplotlib
3. Seaborn
4. Scikit-learn
# Description
1. I create a virtual environment
2. Then I have used the transaction_anomalies_dataset.csv file for the project
3. Install the necessary libraries
4. Run the code for execution
5. The model I have used is IsolationForest
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
# Evaluation metrics
Precision: Normal: 1.00 Anomaly: 1.00
Recall: Normal: 1.00 Anomaly: 1.00
Accuracy: 1.00
