🏥 Medical Insurance Cost Prediction using Machine Learning

📌 Project Overview

This project focuses on predicting medical insurance charges based on demographic, lifestyle, and health-related factors. By applying data analysis and machine learning techniques, the model helps identify key drivers of healthcare costs and supports data-driven decision-making in the insurance domain.

📊 Dataset Description

The dataset contains information such as:

Age

Sex

BMI

Smoking status

Number of children

Region

Insurance charges (target variable)

The dataset was split into training and testing sets to simulate real-world prediction scenarios.

🔍 Exploratory Data Analysis (EDA)

Key insights discovered:

Insurance charges are right-skewed, with a small group of high-cost individuals.

Smoking status is the most influential factor in determining insurance cost.

Higher BMI and age are associated with increased charges.

Regional differences have comparatively lower impact.

🛠 Feature Engineering

Created age groups based on insurance-relevant brackets.

Categorized BMI using standard medical classifications.

Encoded categorical variables using binary encoding and one-hot encoding.

Ensured consistency between training and test datasets.

🤖 Model Building

Multiple regression models were trained and evaluated:

Linear Regression

Ridge Regression

Random Forest Regressor

📌 Random Forest outperformed linear models by capturing non-linear relationships.

📈 Model Performance
Model	MAE	RMSE	R² Score
Linear Regression	~3805	~5618	~0.73
Ridge Regression	~3806	~5618	~0.73
Random Forest	~1615	~3397	~0.90
🔑 Key Insights

Smoking, obesity, and age are the strongest predictors of insurance cost.

Tree-based models significantly improve prediction accuracy for healthcare cost data.

💾 Model Deployment

The trained Random Forest model was saved using joblib for reuse and deployment.

Predictions were generated on unseen test data.

🧰 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook
