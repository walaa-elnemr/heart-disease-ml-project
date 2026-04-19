# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Overview
This project predicts the presence of heart disease using machine learning models based on medical data.

The goal is to build a reliable classification system that can assist in early detection.

---

## 📊 Dataset
The dataset includes medical features such as:
- Age
- Sex
- Chest pain type
- Blood pressure
- Cholesterol
- Maximum heart rate

Target:
- 0 → No heart disease
- 1 → Heart disease

---

## ⚙️ Models Used

- Decision Tree (baseline model)
- Random Forest (ensemble model using bagging)
- Gradient Boosting (sequential boosting model)

---

## 🤝 Ensemble Method

Soft Voting was applied to combine model predictions using probability averaging.

---

## 📈 Results

| Model            | Accuracy |
|------------------|----------|
| Decision Tree    | 78.7%    |
| Random Forest    | 86.9%    |
| Soft Voting      | 86.9%    |

---

## 🔍 Key Insights

- Random Forest achieved the best overall accuracy.
- Ensemble model did not improve accuracy but improved recall for detecting heart disease.
- In medical problems, recall is critical to avoid missing positive cases.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## ⚠️ Limitations

- Dataset size is relatively small
- No hyperparameter tuning applied
- Model not deployed

---

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Cross-validation
- Model deployment using Streamlit

---

## 👨‍💻 Author
Your Name