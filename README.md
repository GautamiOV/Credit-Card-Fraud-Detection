# Credit-Card-Fraud-Detection
# 💳 Credit Card Fraud Detection - Machine Learning Project

This project focuses on detecting fraudulent credit card transactions using **Machine Learning**. It demonstrates how to handle **imbalanced datasets**, preprocess data, train models, and evaluate them using real-world performance metrics. The dataset used is based on anonymized credit card transactions made in Europe.

---

## 📌 Project Objectives

- Understand the nature of fraudulent vs. genuine transactions
- Handle data imbalance using effective techniques
- Train a machine learning model to classify transactions
- Evaluate model performance using appropriate metrics
- Provide a reproducible and well-documented ML pipeline

---

## 📊 Dataset Overview

- Source: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Records: 284,807 transactions
- Features: 30 (including `Time`, `Amount`, `V1` to `V28` as PCA-transformed features)
- Target Variable: `Class` (0 = Non-Fraudulent, 1 = Fraudulent)

---

## 🧠 Machine Learning Workflow

1. **Data Preprocessing**
   - Checked for missing values
   - Scaled `Time` and `Amount` features using StandardScaler
   - Visualized class imbalance

2. **Handling Imbalanced Data**
   - Used techniques like undersampling (RandomUnderSampler)
   - Compared class distribution before and after balancing

3. **Model Training**
   - Logistic Regression was chosen due to its simplicity and interpretability
   - Split data into train/test sets (80/20)

4. **Model Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC Curve

---

## 💡 Key Features

- ✅ Clear handling of imbalanced classes
- ✅ Model trained using scikit-learn
- ✅ Evaluation with multiple classification metrics
- ✅ Clean, modular, and reproducible code
- ✅ Best practices in ML workflow applied

---

## 🧠 Skills Demonstrated

| Skill | Description |
|-------|-------------|
| **Python** | Core scripting and data preprocessing |
| **Pandas & NumPy** | Data manipulation and handling |
| **Matplotlib & Seaborn** | Data visualization and analysis |
| **Scikit-learn** | Model training, evaluation, and metrics |
| **Data Balancing** | Used undersampling techniques |
| **ML Metrics** | Applied precision, recall, F1-score, ROC-AUC |

---

## 📂 Project Structure

credit-card-fraud-detection/
├── credit_card_fraud.ipynb # Jupyter Notebook with full analysis
├── README.md # Project documentation


---

## 🚀 How to Run This Project

### Requirements

- Python 3.8+
- Jupyter Notebook or any Python IDE

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
🙋‍♀️ About Me
I'm a Data Analyst with a passion for solving real-world problems through data. I specialize in:

Python, MySQL, Power BI

Machine Learning & Statistical Analysis

Data Visualization and Business Reporting

📫 Email: ovgautami258@gmail.com
