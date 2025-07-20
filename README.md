#Credit Risk Assessment and Scoring Model

A modular machine learning project for credit risk analysis and scoring, built on top of cleaned financial data. This project uses various models like Logistic Regression, Random Forest, K-Nearest Neighbors (KNN), and Decision Trees to assess creditworthiness, predict default probabilities, and understand key financial relationships.

📁 Project Structure
File/Notebook	Description
credit_risk_dataset.csv	Main dataset used across notebooks
credit_score.csv	Additional dataset for credit score prediction
CreditRiskDataSetOverview.ipynb	Dataset exploration: structure, types, missing values
CleaningCreditDataSet.ipynb	Handles data cleaning, imputations, outlier treatment
Analyzing_Relationship_Between_Loan_Amount,_Loan Intent,_and_Default_Rate.ipynb	Visual and statistical analysis on loan parameters vs default
AnalyzeRelationalshipBetweenOutstandingDebt&CreditScore.ipynb	Explores debt burden and credit score relationship
FindingCorrelationBetweenDebttoIncomeRatio&DefaultRate.ipynb	DTI vs default correlation analysis
BuildingCreditRiskAssessmentModwithLogisticRegression.ipynb	Builds a logistic regression model with ROC/KS metrics
BuildingCreditRiskAssessmentModelWithRandomForest.ipynb	Random Forest model for classification
BuildingcreditRiskAssessmentModelwithKNN.ipynb	KNN model training and performance evaluation
PredictingCreditScorewithDecisionTreeRegressor.ipynb	Regression model for estimating credit score

🎯 Key Objectives
Clean and preprocess real-world credit datasets

Perform feature engineering & visualization

Train and compare classification models for credit default prediction

Evaluate models using ROC-AUC, KS, confusion matrix, and accuracy

Predict credit score using regression techniques

🔍 Core Features
✔️ End-to-End ML Workflow
✔️ Exploratory Data Analysis (EDA)
✔️ Multiple Modeling Techniques (LogReg, RF, KNN, DTR)
✔️ Credit Score Estimation
✔️ Correlation Studies: DTI, Loan Amount, Default Risk
✔️ Model Comparison & Evaluation

🧪 Dependencies
Install via requirements.txt (if added), or manually:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
💻 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/jayantkumar1604/Credit-Risk-Assessment-And-Scoring-Model.git
cd Credit-Risk-Assessment-And-Scoring-Model
Launch Jupyter:

bash
Copy
Edit
jupyter notebook
Open any notebook (start with CreditRiskDataSetOverview.ipynb), run all cells, and analyze results.

📈 Example Insights
💳 Borrowers with high outstanding debt and low credit scores show higher default risk.

📊 Logistic regression provides interpretable coefficients for business understanding.

🌲 Random Forest outperforms simpler models in terms of accuracy and AUC.

📉 DTI ratio positively correlates with the probability of loan default.

📌 Loan intent (e.g., Education, Medical, Venture) is a significant factor in default behavior.

🔄 Future Improvements
Add hyperparameter tuning and cross-validation

Explore XGBoost and LightGBM for enhanced accuracy

Create a Streamlit dashboard for risk score prediction

Add model explainability (e.g., SHAP, LIME)

📜 License
This project is licensed under the MIT License.

✍️ Author
Jayant Kumar
