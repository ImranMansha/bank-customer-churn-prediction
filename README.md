# Bank Customer Churn Prediction

This project uses the European bank churn dataset to build a predictive model that identifies customers who are likely to leave the bank. The goal is to help the bank retain valuable customers by leveraging machine learning techniques.

## Dataset Overview
The dataset includes customer demographics, account balance, credit score, tenure, transaction history, and churn status. It is used to classify whether a customer will churn or not.

## Techniques & Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn for machine learning models
- Logistic Regression, Random Forest, and XGBoost
- Confusion Matrix, Accuracy, ROC-AUC score
- Feature importance analysis
- Data preprocessing and train-test split

## Model Performance
Achieved strong performance with XGBoost, highlighting key features that influence customer churn such as:
- Credit Score
- Tenure
- Balance
- Age
- IsActiveMember

## 📁 Project Structure
├── bank_churn_competition.ipynb 
├── dataset.csv # Dataset file 
└── README.md # Project documentation


## Key Insights
- Age and activity level are strong indicators of churn.
- High balance alone doesn't guarantee loyalty.
- Feature engineering and model selection significantly impact accuracy.

## License
This project is for educational purposes only.
