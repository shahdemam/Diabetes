# 🩺 Diabetes Classification Project

This project focuses on predicting whether a patient has diabetes using various classification algorithms. The dataset was preprocessed and several models were trained and evaluated for performance.

## 📊 Dataset
The dataset used contains health-related features for patients, including:
- Glucose Level
- Blood Pressure
- BMI
- Age
- Insulin
- And others...

## 🔧 Preprocessing
- Handled missing values (zeros replaced or kept with logic)
- Feature scaling (standardization)
- Label encoding (if needed)
- Split into training and testing sets

## 🤖 Models Used
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Classifier (SVC)
- Random Forest (if used)
- AdaBoostClassifier
- XGBoost (`xgb.XGBClassifier`)
- GridSearchCV for hyperparameter tuning

## 📈 Evaluation
Each model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1)
- (Optional) Cross-Validation

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn for visualization

## 📎 Notes
This project compares the performance of multiple ML classifiers to find the most effective one for predicting diabetes based on patient data.

---

Feel free to check the notebook and explore model comparisons!
