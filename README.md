# 3156Project
# Predicting Student Performance with Machine Learning

This project uses machine learning techniques to predict university students' final grade percentages based on academic, behavioral, and lifestyle factors. The goal is to support early intervention strategies by identifying key performance indicators.

## 📊 Dataset
- Simulated version of the Kaggle dataset: [Factors Affecting University Student Grades](https://www.kaggle.com/datasets/atifmasih/factors-affecting-university-student-grades)
- Contains 10,000+ student records
- Includes features like:
  - High school GPA
  - Attendance rate
  - Study time
  - Social media usage
  - Sleep hours
  - Final grade (target)

## 🧠 Machine Learning Models
Two regression models were developed and evaluated:
1. **Random Forest Regressor**
2. **XGBoost Regressor**

## 🛠️ Features of This Project
- Complete ML pipeline: data preprocessing, training, evaluation
- Model performance metrics (RMSE, R², MAE)
- Feature importance visualization
- Exported results to CSV and PNG for reporting

## 📁 Project Structure
student-performance-ml-project/
├── student_performance_prediction.py # Main ML script
├── README.md # This file
└── outputs/
├── model_evaluation_metrics.csv # Performance of both models
└── xgb_feature_importance.png # Visualization of XGBoost feature importances

shell
Copy
Edit

## 🚀 Getting Started

### Install Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
Run the Script
bash
Copy
Edit
python student_performance_prediction.py
📈 Output Files
outputs/model_evaluation_metrics.csv: Contains RMSE, R², and MAE for each model

outputs/xgb_feature_importance.png: Bar plot of XGBoost’s most important features

📌 Author
Mya Allen
Department of Computer Science
University of North Carolina at Charlotte, Class of 2025

🤖 Acknowledgments
This project was created with support from:

ChatGPT (OpenAI) for research structuring and writing

Scikit-learn and XGBoost documentation

yaml
Copy
Edit

---

You can now paste this directly into your GitHub repo’s README. Want a matching `requirements.txt` file to make installation easier too?






