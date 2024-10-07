### Auto Loan Default Prediction

**Ranjeev Kumar**

#### Executive summary

This project explores the key factors influencing auto loan defaults and develops machine learning models to predict the likelihood of default. By analyzing a dataset from Kaggle containing vehicle loan information, we aim to provide actionable insights for lenders to mitigate risk and enhance financial decision-making.

#### Rationale

Understanding and predicting auto loan defaults is crucial for financial institutions as it directly impacts their profitability and risk management strategies. High default rates can lead to significant financial losses and increased credit risk. By addressing this question, lenders can reduce defaults, optimize loan portfolios, and contribute to a more stable lending environment.

#### Research Question

What are the key factors that influence whether an auto loan application will default, and how can we predict the likelihood of default using machine learning techniques?

#### Data Sources

Dataset: Vehicle Loan Default Prediction
Description: The dataset includes borrower information, loan details, credit history, and indicators of loan default.

#### Methodology

Data Preprocessing: Handled missing values, encoded categorical variables, and scaled numerical features.
Exploratory Data Analysis (EDA): Conducted statistical analyses and visualizations to uncover patterns and relationships.
Feature Selection: Identified significant predictors using correlation analysis and feature importance scores.
Model Building: Trained Logistic Regression, Random Forest, and Gradient Boosting models.
Model Evaluation: Assessed models using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrices.
Hyperparameter Tuning: Optimized model parameters using GridSearchCV for improved performance.


#### Results

Key Factors Influencing Default:
Low credit scores significantly increase default risk.
Higher loan amounts are associated with higher default rates.
Employment length and income levels are influential predictors.
Model Performance:
Random Forest Classifier achieved the best performance with:
Accuracy: 85%
ROC-AUC Score: 0.88
Insights:
Implementing stricter lending criteria for high-risk profiles can reduce default rates.
Monitoring key factors can help in proactive risk management.


#### Next steps

Feature Engineering: Explore additional features or transformations to improve model accuracy.
Model Deployment: Develop a user interface or API for real-time default prediction.
Ethical Considerations: Assess models for potential biases and ensure fair lending practices.


#### Outline of project

Data Preprocessing and EDA Notebook 


##### Contact and Further Information

For questions or further information, please contact ranjeevkumar@gmail.com
