# Fraudulent Transaction Detection Model

This repository contains a machine learning model designed to detect fraudulent transactions based on various criteria. The model flags suspicious transactions using rule-based methods and anomaly detection techniques. The criteria for flagging transactions include:

- Frequent transactions from the same IP address.
- Multiple transactions between specific accounts.
- Transactions made within a very short period of time.
- Transactions with abnormal amounts.
- Transactions of specific amounts more than twice from the same IP address.
- Transactions with significant differences in amounts compared to previous transactions.

#Features

- Data Preprocessing: Separates dates and times for better analysis.
- Rule-Based Flags: Implements multiple criteria to identify suspicious transactions.
- Anomaly Detection: Uses Isolation Forest to detect anomalies in transaction amounts.
- Evaluation: Includes confusion matrix and classification report to assess model performance.
- Output: Saves flagged transactions to a CSV file for further investigation.

#Installation

To run this project, you need to have Python installed along with the following libraries:
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install these libraries using pip:
```bash
pip install pandas scikit-learn matplotlib seaborn
