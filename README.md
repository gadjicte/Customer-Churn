# 📉 Customer Churn Prediction

This project uses machine learning to predict customer churn based on behavioral and demographic features. The goal is to classify whether a customer is likely to leave (churn) or stay with the company.

## 🧾 Project Summary

- 📁 **Data**: Real-world customer data (training and testing)
- 📊 **Task**: Binary classification (churn or not)
- 🔍 **Model(s)**: Logistic Regression, Decision Tree, or others (see notebook)
- 🛠️ **Tools**: Python, Pandas, Scikit-learn, Matplotlib

---

## 📁 Project Structure

```text
customer-churn-prediction/
│
├── main.ipynb                      # Jupyter notebook with full analysis and model
├── README.md                       # Project overview
├── requirements.txt                # List of Python libraries used
└── data/
    ├── customer_churn_dataset-training-master.csv
    └── customer_churn_dataset-testing-master.csv
```
## 🚀 How to Run
1.Clone the repository
```bash
git clone https://github.com/gadjicte/customer-churn-prediction.git
cd customer-churn-prediction
```
2.Install dependencies
```
pip install -r requirements.txt
```
3.Launch the notebook
```
jupyter notebook main.ipynb
```
## 🔍 Dataset Info
customer_churn_dataset-training-master.csv: Training data

customer_churn_dataset-testing-master.csv: Test data

Columns include customer demographics, usage behavior, and churn labels.

## 🧠 Machine Learning Workflow
📊 Exploratory Data Analysis (EDA)

🧼 Data Preprocessing

🧠 Model Training

📈 Evaluation with metrics like accuracy, precision, recall

🔮 Prediction on test set

## 📦 Requirements
See requirements.txt or install manually:
```
pip install pandas numpy matplotlib scikit-learn
```
## 📊 Output
Add screenshots here if you want, like:

Confusion matrix

Accuracy/loss plots

Example predictions

## 🎓 Learning Goals
Understand churn prediction

Preprocess real-world datasets

Train and evaluate ML models

Visualize model performance



