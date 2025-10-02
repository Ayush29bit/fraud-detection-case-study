# fraud-detection-case-study
This notebookfocuses on building a fraud detection model using the PaySim synthetic financial transaction dataset (6M+ rows). The goal was to predict fraudulent transactions, understand key risk factors, and provide actionable insights for prevention.

The notebook follows a structured ML workflow:

Data Cleaning – handling missing values, encoding categorical variables, retaining outliers (important for fraud).

Exploratory Data Analysis (EDA) – class imbalance analysis, transaction type distribution, feature correlations.

Feature Engineering – categorical encoding, removal of redundant features, and handling multicollinearity.

Class Imbalance Handling – applied SMOTE after train-test split to balance fraud vs non-fraud classes.

Modeling – trained XGBoost Classifier due to its ability to handle imbalance and provide feature importance.

Evaluation – Confusion matrix, ROC-AUC (0.99), Precision, Recall, and F1-score.

Interpretability – XGBoost feature importance, correlation with fraud target, and business reasoning behind predictors.

Recommendations – prevention strategies and evaluation methods for future fraud monitoring.

