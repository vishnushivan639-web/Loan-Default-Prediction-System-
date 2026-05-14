🏦 Loan Default Prediction Project  
Predicting Borrower Default Risk Using Data Analytics and Machine Learning

📌 Overview

This project focuses on analyzing borrower financial data to identify potential loan defaulters using Exploratory Data Analysis (EDA), Linear Regression, and interactive dashboard visualization.

The system is designed with a structured and scalable workflow that helps financial institutions understand borrower behavior, reduce credit risk, and support better loan approval decisions.

The workflow includes:

• Data preprocessing and cleaning  
• Exploratory Data Analysis (EDA)  
• Risk behavior analysis  
• Linear Regression model building  
• Dashboard visualization using Plotly  
• Model evaluation and insights generation  

The main goal is to identify high-risk borrowers and improve decision-making in loan approval processes.

---

📂 Dataset

Source: Kaggle – Lending Club Loan Data

Dataset Link:  
https://www.kaggle.com/datasets/wordsforthewise/lending-club

Description:

The dataset contains real-world borrower and loan-related information collected from Lending Club.

Selected features include:

• Loan Amount  
• Loan Term  
• Interest Rate  
• Annual Income  
• Employment Length  
• Home Ownership  
• Loan Purpose  
• Loan Grade  
• Loan Status (Fully Paid / Default)

---

🎯 Objectives

• Analyze borrower financial behavior and loan repayment patterns  
• Identify key factors influencing loan default  
• Perform data cleaning and preprocessing  
• Conduct statistical and relationship analysis  
• Build a Linear Regression model for loan amount prediction  
• Evaluate model performance using standard metrics  
• Create an interactive dashboard for visual analysis  
• Support financial institutions in risk management decisions

---

⭐ Project Highlights

🧹 1. Data Preprocessing

• Handled missing and null values  
• Removed unnecessary and sparse columns  
• Converted categorical variables into usable formats  
• Cleaned interest rate and employment length fields  
• Ensured correct data types and consistency

---

📊 2. Exploratory Data Analysis (EDA)

Analyzed borrower and loan patterns using statistical and visual techniques.

Key analysis performed:

• Loan amount distribution  
• Interest rate analysis  
• Income distribution  
• Default vs Fully Paid comparison  
• Employment length analysis  
• Home ownership analysis  
• Loan purpose analysis

Identified major influencing factors such as:

• Interest rate  
• Annual income  
• Employment length  
• Loan grade

---

📈 3. Data Visualization

Visualization techniques were used to understand patterns and trends:

• Bar Charts → Loan status distribution  
• Histograms → Income and loan amount distribution  
• Scatter Plots → Relationship analysis  
• Box Plots → Outlier detection  
• Heatmaps → Correlation analysis

Interactive dashboards were created using Plotly for better insights and exploration.

<img width="673" height="400" alt="sc6" src="https://github.com/user-attachments/assets/cc4844b6-db48-4acd-a6f6-43134e1eb8c9" />
<img width="605" height="418" alt="sc7" src="https://github.com/user-attachments/assets/393bbf22-110b-40c8-88b7-e2b4caba36ef" />
<img width="605" height="429" alt="sc8" src="https://github.com/user-attachments/assets/3eee8646-c223-4872-85f9-c2a980f29002" />




---

⚠️ 4. Risk Analysis

Borrowers were classified into:

• Low Risk  
• Medium Risk  
• High Risk

Risk categorization was based on borrower financial characteristics and interest rate patterns.

The analysis helps identify:

• Potential defaulters  
• High-risk loan categories  
• Financial behavior trends

---

🤖 5. Machine Learning Model

Implemented a Linear Regression model for predictive analysis.

Model Workflow:

• Selected independent variables:
  - Annual Income
  - Interest Rate
  - Loan Term

• Dependent variable:
  - Loan Amount

• Split dataset into training and testing sets  
• Trained Linear Regression model  
• Generated predictions for loan amount

---

📏 6. Model Evaluation

The model was evaluated using:

• R² Score  
• Mean Absolute Error (MAE)  
• Root Mean Squared Error (RMSE)  
• Residual Analysis

These metrics helped measure prediction accuracy and model performance.

---

📊 7. Dashboard Creation

Created interactive dashboards using Plotly.

Dashboard Features:

• Income vs Loan Amount visualization  
• Loan distribution charts  
• Default comparison analysis  
• Interest rate trends  
• Dynamic and interactive graphs

The dashboard supports data-driven financial decision-making.

---

🛠️ Tools and Technologies

• Python  
• pandas  
• NumPy  
• Matplotlib  
• Seaborn  
• Plotly  
• Scikit-learn  
• Jupyter Notebook

---

📌 Key Insights

• Higher interest rates are strongly associated with loan defaults  
• Lower-income borrowers show increased default probability  
• Employment stability impacts repayment capability  
• Certain loan purposes have higher default rates  
• Data visualization improves financial risk interpretation

---

🚀 Future Improvements

• Implement classification models such as:
  - Random Forest
  - XGBoost
  - Logistic Regression

• Deploy the model using Flask or Streamlit  
• Add real-time prediction support  
• Improve risk scoring using advanced ML techniques

---

📚 Conclusion

This project demonstrates how data analytics and machine learning can help financial institutions identify risky borrowers and improve credit risk management.

Through EDA, predictive modeling, and interactive dashboards, the system provides meaningful insights that support smarter loan approval strategies and reduce financial losses.



