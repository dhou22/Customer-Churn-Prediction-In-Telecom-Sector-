# Customer Churn Prediction In The Telecom Sector 
-------------------------------------------------
**Project Overview**  <br>
* This project focuses on predicting customer churn in the telecom industry using various machine learning algorithms.<br>
* By analyzing customer behavior and engagement data, the goal is to identify patterns that lead to churn, enabling telecom companies to implement proactive retention strategies.<br>
* The project includes data preprocessing, model training, evaluation, and insights derived from explainability tools like SHAP.<br> <br>


**Tools and Libraries Used**  <br>
- pandas, numpy - For data manipulation and analysis <br>
- matplotlib, seaborn - For data visualization <br>
- xgboost, RandomForestClassifier, GradientBoostingClassifier, LogisticRegression, DecisionTreeClassifier, SVC - For machine learning modeling <br>
- LabelEncoder, StandardScaler - For preprocessing and feature engineering <br>
- imblearn (SMOTE, EditedNearestNeighbours) - For handling class imbalance <br>
- sklearn.metrics - For model evaluation (accuracy, F1 score, precision, recall, ROC AUC, etc.) <br>
- GridSearchCV - For hyperparameter tuning <br>
- shap - For feature importance analysis and model explainability <br>
- joblib - For saving and loading trained models <br> <br>


**Methodology**  <br>
Following CRISP-DM methodology : <br>
1. Business Understanding: <br>
    Understanding the importance of customer retention in the telecom sector. <br>
2. Data Understanding: <br>
    Analyzing key features and patterns in customer data that influence churn. <br>
3. Data Preparation: <br>
    Preprocessing the data, handling missing values, encoding categorical features, and addressing class imbalances using SMOTE and Edited Nearest Neighbours. <br>
4. Modeling and Evaluation: <br>
   Training multiple machine learning models. <br>
5. Evaluating models : <br>
   using metrics like accuracy, F1 score, and ROC AUC. <br>
   Analyzing feature importance using SHAP. <br>
6. Deployment : <br>
   Exporting the trained models for production use. <br>  <br>


**Key Findings** <br>
1. Top Contributing Features to Churn: <br>   
- Total Day Charge: Higher charges correlate with increased churn probability. <br>
- International Plan: Customers with international plans are more likely to churn. <br>
- Voice Mail Plan: Customers with this plan also exhibit higher churn tendencies. <br>

2.  Best Performing Model: <br>
XGBoost achieved the highest accuracy and ROC AUC scores.  <br>  <br>


**Proposed Solutions**
- Tailored Pricing Plans: Implement tiered pricing models to address high daily charges. <br>
- Enhanced Communication: Engage customers with international and voice mail plans through loyalty programs and retention campaigns. <br>
- Segmented Marketing: Target high-risk customers with personalized promotions, such as discounts or bundled services. <br>


