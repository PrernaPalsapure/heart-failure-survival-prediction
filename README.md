❤️ Prediction of Heart Failure Survival
📌 Project Overview :
This work predicts the survival risk for heart failure patients based on clinical features of age, ejection fraction, serum creatinine, platelets, and follow-up time.
It does cover the entire data science lifecycle:

Overview - 
1. Exploratory Data Analysis (EDA)
2. Feature Engineering & Preprocessing
3. Model Training & Evaluation
4. Hyperparameter Tuning
5. Deployment with Streamlit
6. Power BI Visualization

Selection of Dataset -
1. Source: Heart Failure Clinical Records Dataset
2. Target Variable: DEATH_EVENT
3. Records: 299 patients
4. Features: 13 clinical attributes

⚙️ Preprocessing :
1. Log transformation for skewed variables
2. Feature scaling by using StandardScaler & RobustScaler
3. Handling class imbalance using SMOTE
4. Stratified K-Fold Cross Validation

🤖 Models Used :
1. Logistic Regression
2. Support Vector Classifier (SVC) ✅ Final Model
3. LightGBM
4. XGBoost
5. KNN
6. Decision Tree

🏆 Best Model (SVC) :
1. Recall: 0.84
2. Accuracy: 0.84
3. Optimized using GridSearchCV
4. Evaluation focused on Recall due to medical importance

📈 Power BI Dashboard :
1. An interactive dashboard was developed for analyzing:
2. Event distribution of death by age & sex
3. Platelets vs. age comparison
4. High Blood Pressure Information
5. Survival trends

📽️ Dashboard Video:
👉 dashboard/powerbi_dashboard.mp4

🚀 Deployment :
1. Web app built using Streamlit
2. Temporary public access via ngrok
3. 🔗 Live Demo (Temporary):
https://c5200fd95a5d.ngrok-free.app

Note: ngrok link works only while the app is running.
