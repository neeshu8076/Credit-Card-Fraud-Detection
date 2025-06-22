# 💳 Credit Card Fraud Detection

This project focuses on identifying fraudulent credit card transactions using machine learning techniques. It leverages various classification models on a real-world dataset to detect anomalies and reduce financial risk.

---

## 📌 Problem Statement

Credit card fraud is a growing concern in the digital world. The goal of this project is to build models that can detect suspicious transactions with high accuracy, even when working with imbalanced datasets.

---

## 📊 Dataset

- **Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- The dataset contains transactions made by European cardholders in September 2013.
- It includes 284,807 transactions, out of which 492 are fraudulent.
- Features are anonymized using PCA due to confidentiality reasons.

---

## 🧠 Machine Learning Algorithms Used

- Logistic Regression
- Random Forest
- Isolation Forest (Anomaly Detection)

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Handling missing values (if any)
   - Scaling features
   - Dealing with class imbalance using under/oversampling techniques

2. **Model Training**
   - Splitting data into training and testing sets
   - Training models with appropriate hyperparameters

3. **Model Evaluation**
   - Confusion Matrix
   - Precision, Recall, F1-Score
   - ROC-AUC Score

---

## 📈 Results

| Model              | Precision | Recall | F1-Score | ROC-AUC |
|-------------------|-----------|--------|----------|---------|
| Logistic Regression | 0.91      | 0.60   | 0.72     | 0.94    |
| Random Forest       | 0.97      | 0.76   | 0.85     | 0.98    |
| Isolation Forest    | 0.89      | 0.58   | 0.70     | 0.93    |

*(Note: These are sample values. Replace with your actual results.)*

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📚 Future Improvements

- Use deep learning models like Autoencoders.
- Implement real-time fraud detection system.
- Integrate with a web dashboard for visualization.

---

## 📂 Project Structure

├── data/
│ └── creditcard.csv
├── notebooks/
│ └── CreditCardFraudDetection.ipynb
├── README.md


---

## 🙋‍♂️ Author

- **Neeshu Gautam**
- [https://linkedin.com/in/neeshu-gautam-17961a291](#) | [https://github.com/neeshu8076](#)


