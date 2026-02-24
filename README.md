# APPLYING-ECONOMIC-MODELS-TO-FORECAST-PERSONAL-CREDIT-RISK-ON-A-PEER-TO-PEER-CREDIT-LENDING-PLATFORM
This research examines how various factors influence the credit risk rate on a P2P lending platform using machine learning methods. The dataset, collected from the United States, provides valuable empirical evidence and serves as a reference for the development of this emerging market in Vietnam.
1. Project title: Credit Risk Prediction for P2P Lending Platforms Using Machine Learning
2. Project Overview
This project aims to build and evaluate machine learning models to predict borrower default risk on Peer-to-Peer (P2P) lending platforms. The study applies multiple classification algorithms to identify high-risk borrowers and improve credit risk assessment accuracy. Additionally, the research discusses implications for risk management and regulatory frameworks in emerging P2P markets like Vietnam. The project focuses not only on predictive performance but also on model interpretability and policy relevance.
3. Research problem: P2P lending platforms operate without traditional banking intermediaries, making credit risk assessment critically important.However:
- Vietnam lacks a complete regulatory framework for P2P lending 
- Traditional credit evaluation methods are often manual and inefficient 
- Default rate prediction is challenging due to highly imbalanced data (91.4% non-default vs. 8.6% default) 
- Core problem: How can machine learning models improve default prediction while handling severe class imbalance?
4. Data Description
- Source: Lending Club
- Numbers of observation: 10.000+ loan records
- Key value: Loan status
- Time period: 2007 to 2018
5. Methodology
- Data Preprocessing: Missing value treatment, Encoding categorical variables, Feature selection, Handling multicollinearity, Addressing imbalance using SMOTE + Over/Under Sampling 
- Models Implemented: Logistic Regression, Decision Tree, Random Forest, XGBoost, CatBoost & LightGBM and Stacking Ensemble
- Model Evaluation Metrics: Accuracy, Precision, Recall, F1-score
- Hyperparameter Tuning: Grid Search
6. Key Findings
- Although some models achieved high Accuracy (~90%), Recall for default cases remained extremely low in several models. This indicates that Accuracy alone is misleading in credit risk prediction.
- Despite high overall accuracy (~90.95%), XGBoost detected only 350 defaults out of 46,647 cases → Poor recall for high-risk borrowers.
7. Tools & Technologies
- Programming: Python, Pandas, NumPy, Scikit-learn
- Machine Learning: Logistic Regression, Decision Tree, Random Forest, XGBoost, CatBoost, LightGBM
- Data Techniques: SMOTE, Grid Search, Feature Importance, Confusion Matrix & ROC Curve
  
