# Big Sales Data Prediction (YBI Foundation Internship Project)

### Two-Month Data Science Internship Project

---

## Objective
The goal of this project is to build a predictive model for sales forecasting using machine learning techniques.  
The project leverages **RandomForest Regressor** to predict future sales performance based on historical data.

---

## Data Source
- **Dataset:** Big Sales Data.csv (provided during the YBI Foundation internship)  
- **Size:** 12,000+ rows of retail sales data  
- **Features:** Product attributes, store-level information, and historical sales values  

---

## Methodology
### Data Preprocessing
- Handled missing values  
- Label encoding of categorical features  
- Standardization and cleaning  

### Exploratory Data Analysis (EDA)
- Distribution plots using Matplotlib & Seaborn  
- Correlation heatmaps for feature importance  
- Outlier detection  

### Model Building
- **Algorithm:** RandomForestRegressor  
- Hyperparameter tuning for better accuracy  
- Train-test split to validate model performance  

### Model Evaluation
- **Metrics:** R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE)  
- Compared performance across different parameter settings  

---

## Results & Challenges
**Model Performance:**  
- R² Score: ~0.56  
- MAE: ~845  
- MSE: ~1,200,000  

**Key Challenge:**  
Despite multiple rounds of hyperparameter tuning and feature adjustments, the score did not improve significantly.  

This indicates that:  
- The dataset may have high noise or missing explanatory variables.  
- RandomForest, while robust, might not capture certain complex sales patterns.  
- Additional techniques (feature engineering, boosting methods, or deep learning models) could be explored to enhance performance.  

---

## Technologies & Libraries
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

## Deliverables
- Final Jupyter Notebook: `final_file_rfr.ipynb`  
- Source Code and Model Training Pipeline  
- Visualizations of data insights and model performance  

---

## Key Learnings
- Practical application of regression models in business forecasting  
- Importance of feature engineering and EDA before modeling  
- Learned that not every dataset yields high accuracy — understanding limitations is equally valuable  
- Experience in building end-to-end data science projects for real-world datasets  

---

## Future Work
To improve predictive performance, future enhancements could include:  
- **Feature Engineering** – Creating new meaningful features (e.g., promotions, seasonality, holidays).  
- **Boosting Algorithms** – Trying models like XGBoost, LightGBM, or CatBoost for better accuracy.  
- **Neural Networks** – Experimenting with deep learning models (LSTM/GRU) to capture time-series sales patterns.  
- **Ensemble Methods** – Combining multiple models for improved generalization.  
- **External Data Integration** – Adding macroeconomic factors, festivals, or weather data to enrich the dataset.  

---

## Acknowledgment
This project was completed as part of the **YBI Foundation Data Science Internship Program**.  
Special thanks to the mentors for guidance and support throughout the two-month internship.
