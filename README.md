
## 🛡️ Credit Card Fraud Detection Using Machine Learning

### 📌 Abstract

Credit card fraud leads to billions of dollars in losses each year, posing a major threat to financial institutions and consumers alike. Leveraging machine learning, this project aims to detect fraudulent transactions by identifying suspicious patterns in credit card usage. Credit card fraud may involve unauthorized access to card information or the physical theft of cards. This project implements and evaluates several machine learning models trained on historical transaction data to classify and detect fraudulent activity.

**Keywords**: Credit Card Fraud Detection, Machine Learning, Fraudulent Transactions, K-Nearest Neighbors, Support Vector Machine, Logistic Regression, Decision Tree

---

### 🔍 Overview

The global rise in credit card usage demands more robust fraud prevention mechanisms. As of 2019, over 2.8 billion people used credit cards, with fraud incidents growing rapidly each year. In 2020 alone, the U.S. saw a 44.7% increase in fraud reports. There are primarily two types of credit card fraud:

1. Fraudulent creation of new accounts using stolen identities.
2. Unauthorized use of existing accounts by stealing card information.

This project seeks to address the second type by employing multiple machine learning algorithms to detect anomalies and fraudulent transactions from a large dataset. The work compares models' effectiveness and provides visual and statistical insights into their performance.

---

### 🎯 Project Goals

* Detect fraudulent credit card transactions with high accuracy.
* Compare the performance of multiple machine learning algorithms.
* Identify the most effective model for fraud detection.
* Provide visualizations and insights based on model results.
* Review existing literature and techniques used in fraud detection.

---

### 📂 Dataset

* **Source**: [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
* **Description**: The dataset contains 284,808 transactions made by European cardholders over two days in 2013.
* **Features**:

  * 31 total attributes
  * 28 anonymized features transformed using PCA
  * 3 remaining attributes:

    * `Time`: Seconds elapsed between first and subsequent transactions
    * `Amount`: Transaction amount
    * `Class`: Binary (1 = Fraudulent, 0 = Legitimate)

---

### ⚙️ Algorithms Used

* K-Nearest Neighbors (KNN)
* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree

---

### 🔮 Future Work

To enhance the system, future iterations could:

* Use diverse datasets with varying transaction patterns.
* Experiment with different train-test splits or additional ML techniques.
* Integrate external data (e.g., geolocation from telecom sources) to enhance prediction accuracy based on cardholder presence vs. transaction location.

---

### ✅ Conclusion

This project successfully developed and evaluated four machine learning models for credit card fraud detection. KNN and Decision Tree classifiers achieved the highest accuracy (100%) on this dataset, making them strong candidates for real-world implementation. These models can help financial institutions proactively detect fraud, reducing losses and improving customer trust.

---

Let me know if you'd like a [Markdown README version for direct use in your repo](f) or [add visual plots and model metrics](f) to make the repo even more appealing.
