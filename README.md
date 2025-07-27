# 🩺 Diabetes Prediction Using Machine Learning

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
- Handled missing values (e.g., zeros replaced or kept with logic)
- **Outlier Detection and Treatment** to remove abnormal values
- **SMOTE** applied to balance the imbalanced target classes
- **Feature Scaling** using:
  - `StandardScaler` or `MinMaxScaler`
- Label encoding (if needed)
- Split into training and testing sets

## 🤖 Models Used
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Classifier (SVC)
- AdaBoost Classifier
- XGBoost (`xgb.XGBClassifier`)
- **GridSearchCV** for hyperparameter tuning

📝 *Note: Random Forest was not used in this project.*

## 📈 Evaluation
Each model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1 Score)
- (Optional) Cross-Validation

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (`SMOTE`)
- XGBoost
- Matplotlib & Seaborn for visualization

## 📎 Notes
This project addresses class imbalance using **SMOTE** and improves model performance by:
- **Cleaning data** via outlier removal
- **Scaling features** for better model learning
- **Tuning hyperparameters** using GridSearchCV

Multiple machine learning classifiers were compared to identify the best-performing model for diabetes prediction based on patient health data.

---

📁 Feel free to explore the Jupyter Notebook for code, visualizations, and model performance comparisons!

