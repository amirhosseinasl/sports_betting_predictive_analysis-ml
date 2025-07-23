# sports_betting_predictive_analysis-ml
A machine learning pipeline to predict sports betting outcomes using real-world match data and Scikit-learn.
# 🏈 Sports Betting Predictive Analysis

A machine learning pipeline to predict sports betting outcomes using real-world match data and Scikit-learn.

---

## 🚀 Overview

This project demonstrates how to:
- 🧹 Clean and encode raw match data
- ⚖️ Handle class imbalance using `RandomOverSampler`
- 🌲 Train and evaluate a `RandomForestClassifier`
- 📊 Visualize model performance with insightful plots

---

## 🧠 Techniques Used

- **Data Preprocessing**: missing value handling, label encoding
- **Oversampling**: using `imbalanced-learn` to balance rare outcomes
- **Model**: Random Forest with `class_weight="balanced"`
- **Evaluation**:
  - Confusion Matrix (True vs. Predicted)
  - Feature Importance plot
  - Learning Curve (F1 macro)

---

## 📁 Project Structure

sports-betting-ml/ ├── data/ │ └── sports_betting_predictive_analysis.csv ├── src/ │ └── betting_model_analysis.py ├── README.md └── requirements.txt

---

## ⚙️ How to Run

1. 🔧 Install dependencies:
```bash
pip install -r requirements.txt

2. 🚀 Run the model analysis:



python src/betting_model_analysis.py


---

📦 Dependencies

pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn


---

👨‍💻 Author

[Your Name] – Personal machine learning project to explore predictive modeling in sports analytics using Scikit-learn.


---

💡 License

This project is open-source and free to use under the MIT License.
