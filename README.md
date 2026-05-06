 📌 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Due to the highly imbalanced nature of fraud datasets, effective modeling and evaluation are crucial to accurately identify fraudulent activities while minimizing false positives.

The project uses the **Credit Card Fraud Detection dataset** and implements a **Random Forest Classifier** to classify transactions as legitimate or fraudulent.

---

## 🎯 Objective
- To build a machine learning model that can accurately detect fraudulent credit card transactions.
- To analyze model performance using appropriate evaluation metrics such as Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC score.

---

## 📂 Dataset Information
- **Dataset Name:** Credit Card Fraud Detection
- **Source:** Kaggle
- **Total Transactions:** 284,807
- **Fraudulent Transactions:** 492
- **Legitimate Transactions:** 284,315
- **Features:** 30 numerical features (`V1` to `V28`, `Time`, `Amount`)
- **Target Variable:** `Class`
  - `0` → Legitimate Transaction  
  - `1` → Fraudulent Transaction

> Note: The dataset is highly imbalanced, making fraud detection a challenging task.

---

### Key Characteristics:
- Highly imbalanced dataset
- Fraud cases represent a very small percentage of total transactions
- Requires special evaluation metrics beyond accuracy

---

## 🛠 Tools & Technologies Used
- **Programming Language**: Python  
- **Platform**: Google Colab  
- **Version Control**: GitHub  
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Imbalanced-learn (SMOTE)

---

## ⚙️ Methodology
1. Loaded and explored the dataset.
2. Performed feature–target separation.
3. Split the dataset into training and testing sets using an 80:20 ratio with stratification.
4. Trained a **Random Forest Classifier** with optimized hyperparameters.
5. Generated predictions on the test dataset.
6. Evaluated the model using standard classification metrics.

---

## 🤖 Machine Learning Model
- **Random Forest Classifier**
  - Handles non-linearity well
  - Performs effectively on imbalanced datasets
  - Reduces overfitting using ensemble learning

---

## 📊 Evaluation Metrics
The model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC–AUC Score

These metrics provide a comprehensive understanding of the model’s ability to detect fraudulent transactions.

---

## 📈 Results
- The Random Forest model achieved high accuracy.
- Precision and recall values indicate effective fraud detection.
- Confusion Matrix visualization highlights correct and incorrect classifications.
- ROC-AUC score demonstrates strong discriminative ability between fraud and non-fraud transactions.

---

## 📌 Conclusion
The Random Forest model proved to be effective in detecting fraudulent credit card transactions. Despite the class imbalance, the model achieved strong performance across evaluation metrics. This approach can assist financial institutions in reducing fraud-related losses.

---

## 🚀 Future Enhancements
- Apply SMOTE or other resampling techniques to handle class imbalance.
- Compare performance with other models such as Logistic Regression, XGBoost, or Neural Networks.
- Deploy the model as a web application for real-time fraud detection.

---

## 📁 Repository Contents
- `Credit_Card_Fraud_Detection.ipynb` – Complete implementation
- `creditcard.csv` – Dataset (optional)
- `README.md` – Project documentation

---

## 👤 Author
**Krishna Bhargavi**

 
