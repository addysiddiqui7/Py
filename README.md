Big Sales Data Prediction (YBI Foundation Internship Project)

Two-Month Data Science Internship Project

<u>Objective</u>

The goal of this project is to build a predictive model for sales forecasting using machine learning techniques. The project leverages RandomForest Regressor to predict future sales performance based on historical data.

<u>Data Source</u>

Dataset: Big Sales Data.csv (provided during the YBI Foundation internship)

Size: 12,000+ rows of retail sales data

Features: Product attributes, store-level information, and historical sales values

<u>Methodology</u>

Data Preprocessing

Handled missing values

Label encoding of categorical features

Standardization and cleaning

Exploratory Data Analysis (EDA)

Distribution plots using Matplotlib & Seaborn

Correlation heatmaps for feature importance

Outlier detection

Model Building

Algorithm: RandomForestRegressor

Hyperparameter tuning for better accuracy

Train-test split to validate model performance

Model Evaluation

Metrics: R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)

Compared performance across different parameter settings

<u>Results & Challenges</u>

Model Performance:

R² Score: ~0.56

MAE: ~845

MSE: ~1,200,000

Key Challenge:
Despite multiple rounds of hyperparameter tuning and feature adjustments, the score did not improve significantly.
This indicates that:

The dataset may have high noise or missing explanatory variables.

RandomForest, while robust, might not capture certain complex sales patterns.

Additional techniques (feature engineering, boosting methods, or deep learning models) could be explored to enhance performance.

<u>Technologies & Libraries</u>

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

<u>Deliverables</u>

Final Jupyter Notebook: final_file_rfr.ipynb

Source Code and Model Training Pipeline

Visualizations of data insights and model performance

<u>Key Learnings</u>

Practical application of regression models in business forecasting

Importance of feature engineering and EDA before modeling

Learned that not every dataset yields high accuracy — understanding limitations is equally valuable

Experience in building end-to-end data science projects for real-world datasets

<u>Future Work</u>

To improve predictive performance, future enhancements could include:

Feature Engineering – Creating new meaningful features (e.g., promotions, seasonality, holidays).

Boosting Algorithms – Trying models like XGBoost, LightGBM, or CatBoost for better accuracy.

Neural Networks – Experimenting with deep learning models (LSTM/GRU) to capture time-series sales patterns.

Ensemble Methods – Combining multiple models for improved generalization.

External Data Integration – Adding macroeconomic factors, festivals, or weather data to enrich the dataset.

<u>Acknowledgment</u>

This project was completed as part of the YBI Foundation Data Science Internship Program.
Special thanks to the mentors for guidance and support throughout the two-month internship.
