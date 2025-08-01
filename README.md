# PRODIGY_DS_03
# Task-03: Decision Tree Classifier - Bank Marketing Dataset

## 🎯 Objective
Build a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit (yes/no) based on their demographic and behavioral data.

## 📊 Dataset
- **Source**: UCI Machine Learning Repository
- **File Used**: `bank.csv`
- **Sample Data Features**:
  - age, job, marital status, education, default
  - balance, housing, loan, contact, month, day, etc.
  - **Target Column**: `y` (yes = subscribed, no = not subscribed)

## 🧪 Tools & Libraries Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

## 🛠️ Steps Followed
1. Unzipped and loaded the dataset.
2. Handled categorical features using `LabelEncoder`.
3. Split the dataset into training and test sets (80/20).
4. Trained a `DecisionTreeClassifier`.
5. Evaluated model performance using accuracy and classification report.
6. Visualized the decision tree using `matplotlib`.

## 📈 Model Performance
- ✅ **Accuracy Achieved**: `89.3%`
- Precision, Recall, and F1-score were satisfactory for both classes (`yes` and `no`).
- Tree visualization helps interpret the decision paths used by the model.

## 📁 Files Included
- `decision_tree_bank.ipynb` – main code (can also be `.py`)
- `bank.csv` – dataset (optional if already provided)
- `README.md` – this file

## 📌 Notes
This project is part of a machine learning task to demonstrate decision tree modeling on a real-world dataset. The model can be improved further with pruning, hyperparameter tuning, or using ensemble methods like Random Forest.

---

📬 **Submitted by**: Jonnadula Mamatha  
🗓️ **Date**: August 2025
