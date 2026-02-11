# Task-03 – Decision Tree Classifier (Bank Marketing Dataset)

---

## 🎯 Objective

Build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.

The model is built using the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

---

## 📊 Dataset Used

Bank Marketing Dataset (UCI Repository)

File Used:
- bank-additional-full.csv

The dataset contains customer information such as:
- Age
- Job
- Marital status
- Education
- Housing loan
- Contact type
- Campaign details
- Previous outcomes
- Economic indicators

Target Variable:
- `y` → Whether the customer subscribed to a term deposit (Yes/No)

---

## 🧹 Data Preprocessing Steps

- Removed `duration` column (to avoid data leakage)
- Handled missing values
- Replaced "unknown" values
- Encoded categorical variables using Label Encoding
- Split dataset into training and testing sets (80/20)

---

## 🤖 Model Used

Decision Tree Classifier  
- Criterion: Gini Index  
- Max Depth: 5  
- Random State: 42  

---

## 📈 Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- Feature Importance Analysis
- Decision Tree Visualization

---

## 🔍 Key Insights

- Certain features like contact type, campaign count, and economic indicators significantly influence customer decisions.
- Decision Trees provide interpretable results and help understand customer behavior patterns.

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Folder Structure

Task-03/
│
├── Task_03_Decision_Tree_Bank.ipynb  
├── bank-additional-full.csv  
└── README.md  

---

## 🚀 Conclusion

The Decision Tree model successfully predicts whether a customer will subscribe to a term deposit based on demographic and behavioral attributes.

This task demonstrates:
- Data preprocessing
- Feature engineering
- Classification modeling
- Model evaluation
- Model interpretability

---

⭐ This project is part of my Data Science learning journey.
