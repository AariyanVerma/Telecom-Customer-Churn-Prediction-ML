# Telecom-Customer-Churn-Prediction-ML
A machine learning project focused on predicting customer churn in the telecom industry using Python. This project includes data cleaning, EDA, SMOTE for class imbalance, and classification models like Random Forest, XGBoost, and Logistic Regression to identify churn patterns and improve customer retention strategies.


# Telecom Customer Churn Prediction using Machine Learning

This project focuses on predicting customer churn for a telecom company using machine learning techniques in Python. The goal is to identify customers who are likely to leave the service, enabling proactive retention strategies.

# Dataset

- Dataset Name: Telco Customer Churn
- Source: Kaggle (https://www.kaggle.com/blastchar/telco-customer-churn)
- Total Records: ~7043
- Target Variable: Churn (Yes/No)
- Includes: Customer demographics, subscription details, billing, and payment info

# Technologies and Libraries Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Scikit-learn
- XGBoost
- imblearn (SMOTE)

# Project Workflow

1. Data Preprocessing
   - Handled missing values
   - Encoded categorical variables
   - Normalized numerical features
   - Applied SMOTE for class imbalance

2. Exploratory Data Analysis (EDA)
   - Analyzed churn by tenure, contract, and internet service
   - Visualized correlation heatmaps
   - Pie charts for churn prediction by payment method

3. Model Training
   - Naive Bayes
   - Logistic Regression
   - Random Forest
   - XGBoost

4. Evaluation Metrics
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix

# Results

| Model           | Accuracy | F1 Score |
|----------------|----------|----------|
| Random Forest  | 81.2%    | High     |
| XGBoost        | Competitive | High  |

Key features influencing churn:
- Contract Type
- Monthly Charges
- Tenure

## Future Scope

- Deploy the model using Flask API
- Integrate with a customer-facing dashboard
- Use NLP to analyze customer feedback
- Apply similar methodology in industries like banking or SaaS

# Project Files

- EDA_on_Telecom_churn_dataset_using_machine_learning_Algorithms.ipynb - Code Notebook
- python_final_project.pptx - Project Presentation
- Untitled design.mp4 - Project Video

# Authors

- Aariyan Verma
- Misha Patel
- Pratham Modi
- Pushpak Sriperumbuduri

# License

This project is for educational purposes and licensed under the MIT License.
