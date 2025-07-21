# 🧠 Diabetes Prediction using ML (Logistic Regression & SVC)

This project focuses on building machine learning models to predict the presence of diabetes based on medical diagnostic measurements. The dataset used is preprocessed and used to train two classification models: **Logistic Regression** and **Support Vector Classifier (SVC)**. Both models were evaluated using various metrics after hyperparameter tuning.

---

## 📂 Project Structure

- `Diabetes Prediction.ipynb` – Main Jupyter notebook containing:
  - Data preprocessing
  - Model training
  - Hyperparameter tuning
  - Evaluation

---

## 📊 Dataset

The dataset contains medical features such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

The target variable indicates the presence (`1`) or absence (`0`) of diabetes.

---

## ⚙️ Machine Learning Models Used

### 1. Logistic Regression
- **Accuracy**: `75.32%`
- **Confusion Matrix**:
[[79 18]
[20 37]]

- **Classification Report**:

| Metric       | Class 0 | Class 1 |
|--------------|---------|---------|
| Precision    | 0.80    | 0.67    |
| Recall       | 0.81    | 0.65    |
| F1-Score     | 0.81    | 0.66    |
| Support      | 97      | 57      |

---

### 2. Support Vector Classifier (SVC)
- **Accuracy**: `75.32%`
- **Confusion Matrix**:
[[80 19]
[19 36]]

- **Classification Report**:

| Metric       | Class 0 | Class 1 |
|--------------|---------|---------|
| Precision    | 0.81    | 0.65    |
| Recall       | 0.81    | 0.65    |
| F1-Score     | 0.81    | 0.65    |
| Support      | 99      | 55      |

---

## 🧪 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🔧 Hyperparameter Tuning

Used `GridSearchCV` for tuning key hyperparameters for both models:

- **Logistic Regression**: `penalty`, `C` (regularization strength)
- **SVC**: `kernel`, `C`, `gamma`

---

## 📌 Conclusion

- Both **Logistic Regression** and **SVC** achieved equal accuracy of **75.32%**.
- SVC showed slightly better performance in classifying non-diabetic cases.
- Logistic Regression had slightly better recall for diabetic cases.
- Choice of model depends on the priority metric (e.g., higher recall for detecting diabetes cases).

---

## 🚀 Future Work

- Explore ensemble methods (Random Forest, XGBoost)
- Use advanced feature engineering
- Try deep learning models
- Build a frontend using Streamlit or Flask

---

## 👨‍💻 Author

**Brijesh Rakhasiya**  
AI/ML Enthusiast | Data Scientist | Problem Solver

---

## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**
   
