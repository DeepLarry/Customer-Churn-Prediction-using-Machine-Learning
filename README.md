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

      <img width="491" height="288" alt="image" src="https://github.com/user-attachments/assets/e69d1ffe-6369-415c-a0d3-7034a3ab59e6" />


🔍 Insights from Feature Importance
      *Based on the model, the top factors driving customer churn are:
      *Average Transaction Amount
      *Annual Income
      *Total Spend
      *Last Purchase Days Ago
      *Number of Purchases




📝 Conclusion<img width="1192" height="905" alt="Screenshot 2026-04-07 032138" src="https://github.com/user-attachments/assets/d3d921d7-acc9-4986-8714-7fa8168eadf2" />


📝 Conclusion
While the initial model achieved a baseline accuracy, the project demonstrates a complete end-to-end Data Science pipeline—from raw data cleaning to advanced model tuning. This framework can be scaled with larger datasets (5000+ records) to achieve higher predictive precision as mentioned in my professional portfolio.
