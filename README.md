# Customer-Churn-Prediction-using-Machine-Learning
This project aims to predict customer attrition (Churn) for an online retail business using Machine Learning. By analyzing customer behavior, demographics, and transaction history, the model identifies customers who are likely to stop using the service, enabling the business to take proactive retention measures.


🛠️ Tech StackLanguage: Python Libraries: Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Visualization),
                        Scikit-Learn (Machine Learning) 

Tools: Jupyter Notebook, Git/GitHub 




📈 Key Features & WorkflowData Preprocessing: Handled missing values, encoded categorical variables (Gender, Promotion Response), and converted boolean types to numeric.

     1.) Exploratory Data Analysis (EDA): Analyzed correlations between Annual_Income, Total_Spend, and Satisfaction_Score                                               with the churn rate.
     2.) Model Building: Implemented Random Forest Classifier to handle complex non-linear relationships in the data.
     3.) Optimization  : Performed Feature Scaling using StandardScaler and Hyperparameter Tuning via GridSearchCV (tuning                             max_depth, n_estimators, etc.).
      Evaluation: Used Confusion Matrix and Classification Reports (Precision, Recall, F1-Score) to assess model performance.

      <img width="596" height="452" alt="image" src="https://github.com/user-attachments/assets/4c76b41a-c059-4c12-980c-5011a4f3df79" />

🔍 Insights from Feature Importance
      *Based on the model, the top factors driving customer churn are:
      *Average Transaction Amount
      *Annual Income
      *Total Spend
      *Last Purchase Days Ago
      *Number of Purchases



📝 Conclusion
While the initial model achieved a baseline accuracy, the project demonstrates a complete end-to-end Data Science pipeline—from raw data cleaning to advanced model tuning. This framework can be scaled with larger datasets (5000+ records) to achieve higher predictive precision as mentioned in my professional portfolio.
