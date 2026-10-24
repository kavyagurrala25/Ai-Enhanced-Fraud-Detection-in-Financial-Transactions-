# 🔐 AI-Enhanced Fraud Detection in Financial Transactions

## 📌 Project Overview

AI-Enhanced Fraud Detection in Financial Transactions is a machine learning project designed to identify potentially fraudulent financial transactions. It analyzes transaction details such as transaction amount, merchant, time, and location to predict whether a transaction is fraudulent or legitimate.

The project uses Python and Scikit-learn to preprocess transaction data, explore patterns, compare classification algorithms, evaluate model performance, and save a trained model for reuse.

## 🎯 Objectives

- Detect potentially fraudulent financial transactions using machine learning.
- Analyze transaction patterns based on amount, merchant, time, and location.
- Compare different classification algorithms.
- Evaluate model performance using classification metrics and visualizations.
- Save and reuse the trained fraud detection model.

## ✨ Key Features

- **Data Preprocessing:** Handles missing values and prepares transaction data for analysis.
- **Exploratory Data Analysis (EDA):** Examines transaction distributions and fraud patterns.
- **Data Visualization:** Uses histograms, box plots, count plots, and correlation heatmaps.
- **Model Comparison:** Evaluates Logistic Regression, Support Vector Machine (SVM), and Random Forest classifiers.
- **Model Evaluation:** Uses accuracy, confusion matrices, and ROC-AUC analysis.
- **Fraud Prediction:** Predicts whether a transaction may be fraudulent or legitimate.
- **Model Persistence:** Saves the trained model in a `.pkl` file for reuse.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Model Saving and Loading:** Joblib
- **Development Environment:** Jupyter Notebook
- **Dataset Format:** CSV

## 📊 Dataset Description

The project dataset, `financial_transactions.csv`, contains 1,000 transaction records and the following six columns:

| Column | Description |
|---|---|
| `transaction_id` | Unique transaction identifier |
| `transaction_amount` | Amount involved in the transaction |
| `merchant` | Merchant associated with the transaction |
| `transaction_time` | Date and time of the transaction |
| `location` | Transaction location |
| `is_fraud` | Target label indicating fraudulent or legitimate activity |

The dataset contains both fraudulent and legitimate transactions. The target column `is_fraud` is used to train and evaluate the classification models.

## 🤖 Machine Learning Algorithms

The project compares the following classification algorithms:

1. **Logistic Regression** – Predicts the probability of a transaction belonging to the fraud class.
2. **Support Vector Machine (SVM)** – Separates transaction classes using a learned decision boundary.
3. **Random Forest Classifier** – Combines multiple decision trees to classify transactions.

The notebook includes preprocessing, model comparison, and evaluation workflows to help assess their performance.

## ⚙️ Project Workflow

1. Load the financial transaction dataset.
2. Inspect and clean the data.
3. Convert transaction timestamps into datetime values.
4. Encode categorical features and prepare numerical features.
5. Perform exploratory data analysis and visualize transaction patterns.
6. Split the dataset into training and testing sets.
7. Train and compare classification models.
8. Evaluate predictions using accuracy, confusion matrices, and ROC-AUC.
9. Save the trained model for future predictions.

## 📂 Project Structure

```text
AI-Enhanced-Fraud-Detection/
│
├── 19-Ai Enhanced Fraud Detection in Financial Transactions as per template .ipynb
├── 19-Ai Enhanced Fraud Detection in Financial Transactions as per template .html
├── financial_transactions.csv
├── fraud_detection_model.pkl
└── README.md
```

The PDF project reports can also be added to the repository if you want to include the documentation.

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd AI-Enhanced-Fraud-Detection
```

Replace the placeholder with your actual GitHub repository URL.

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells in sequence.

### 4. Check the project files

Ensure that `financial_transactions.csv` and `fraud_detection_model.pkl` are in the correct directory before running the relevant notebook cells.

## 🧪 Sample Prediction

The notebook includes sample transaction predictions, such as:

- A transaction predicted as **fraudulent**.
- A transaction predicted as **legitimate**.

The prediction and confidence depend on the trained model and the input transaction details. These examples are illustrative and do not guarantee that real-world transactions are correctly classified.

## 📈 Evaluation Metrics

The project uses or explores the following evaluation methods:

- **Accuracy:** Measures the proportion of correct predictions.
- **Confusion Matrix:** Shows correct and incorrect classifications.
- **ROC Curve:** Illustrates the trade-off between true-positive and false-positive rates.
- **AUC Score:** Measures how well the model distinguishes between the two classes.

For fraud detection, precision, recall, and F1-score are also useful for assessing performance, particularly when fraudulent transactions are less common.

## 🔮 Future Enhancements

- Develop a Flask-based web dashboard for transaction monitoring.
- Add real-time transaction analysis and fraud alerts.
- Improve fraud detection using behavioral analysis and anomaly detection.
- Integrate email or SMS notifications for suspicious transactions.
- Explore advanced models and techniques to improve fraud detection.
- Deploy the system as a web application.

## ⚠️ Limitations

- The current dataset contains 1,000 transaction records and may not represent all real-world fraud scenarios.
- Model predictions depend on data quality and the patterns learned during training.
- A predicted fraudulent transaction requires further verification before taking action.
- Real-time banking integration and a Flask dashboard are potential enhancements, not features confirmed by the supplied notebook.

## 🎓 Conclusion

AI-Enhanced Fraud Detection in Financial Transactions demonstrates how machine learning can support the identification of suspicious financial activities. By combining data preprocessing, exploratory analysis, classification algorithms, and model evaluation, the project provides a foundation for building more effective financial fraud detection systems.

## 👩‍💻 Author

**Kavya Gurrala**

Artificial Intelligence and Data Science Student

---

⭐ If you find this project useful, consider starring the repository and sharing your feedback.

**Topics:** `Python` `Machine-Learning` `Fraud-Detection` `Financial-Transactions` `Scikit-Learn` `Data-Science` `Classification`
