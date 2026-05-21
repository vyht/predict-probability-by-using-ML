This research provides a bankruptcy forecasting model using machine learning techniques. The results indicate that bankruptcy risk is influenced by various macroeconomic and firm-level indicators. The model achieves an accuracy of 80%, and other evaluation metrics also demonstrate strong performance.

1. Project title: Bankruptcy risk map: Forecasting business health from a machine learning perspective
2. Project overview Forecasting business health is not only an important tool in financial risk management but also plays a vital role in building sustainable business strategies. This study focuses on analyzing internal factors of businesses such as financial structure, operational efficiency, profitability, along with macroeconomic factors such as economic growth rate, inflation, and market volatility, to identify key factors impacting the future state of the business. It answers the question of whether the business is in a safe or precarious situation. The study also applies advanced methods in econometrics and machine learning to improve forecasting accuracy. Models such as Random Forest, XGBoost, and SVM are deployed to compare performance and determine the most suitable model. The research findings not only provide a comprehensive approach to identifying businesses at risk of bankruptcy but also contribute to supporting investors, banks, and regulators in making strategic decisions to minimize losses and ensure the stability of the financial market.
3. Business problem Forecasting the future health of businesses helps them adjust their current business strategies to avoid collapse, which improves the annual exit rate of businesses from the market, contributing many benefits to society and the country such as ensuring unemployment rates, inflation, etc.
4. Data description
- Source: collected from annual financial report of 1000 companies in Viet Nam security market
- Numbers of observation: 338 observations with 10 independent variables
- Key value: bankruptcy possibility
- Time period: 2021 to 2023
5. Methodology
- Data Preprocessing: Cleaning, handling missing values, EDA and feature engineering
- Modeling Approach: SVM, Decision Tree, Random Forest, XGBoost, Confusion Matrix, Probability calibration and evaluation indicators
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score and ROC-AUC.
6. Key Findings
- The most influential factors affecting bankruptcy risk include financial leverage, profitability ratios, and firm size, alongside macroeconomic indicators such as GDP growth and inflation. Firms with higher leverage and declining profitability show significantly higher default probabilities.
- A clear pattern was observed where companies experiencing deteriorating financial performance over consecutive years were more likely to be classified as high-risk by the model. Macroeconomic instability further amplifies this risk.
- The meaningful insight is that bankruptcy is not triggered by a single variable, but by the interaction between internal financial weakness and external economic conditions. This highlights the importance of combining firm-level and macro-level data in predictive modeling.
7. Business Implications
- The model can be applied as an early warning system for financial institutions, investors, or corporate risk management teams to identify high-risk firms in advance.
- Organizations can take proactive actions such as tightening credit policies, adjusting investment strategies, or improving financial restructuring plans based on predicted risk levels.
- Policymakers may also monitor macroeconomic stress signals to reduce systemic financial risk.
8. Tools & Technologies
- Python
- Pandas, Numpy, Matplotlib
- Scikit-learn
