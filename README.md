Smart Demand Forecasting System

This project focuses on predicting product demand and improving inventory management using machine learning and business logic.

The system takes historical sales data and processes it through multiple steps including preprocessing, feature engineering, and model training. It uses an XGBoost model to generate demand predictions. These predictions are further refined using business rules such as promotions, events, and demand volatility.

Based on the final demand values, the system provides inventory recommendations, calculates safety stock, and identifies risks like stockouts and overstocking. It also generates structured output files that can be used in dashboards.

The pipeline is designed to handle large datasets efficiently by processing data in chunks to avoid memory issues.

Project Structure:

data/raw/ contains the original datasets (not included in repository)
output/ contains generated results (not included)
models/ contains training and prediction logic
features/ contains feature engineering and business rules
frontend/ contains dashboard interface
utils/ contains helper functions
main.py runs the complete pipeline
app.py runs the dashboard
How to Run:

Install required libraries using requirements.txt
Place dataset files inside data/raw/
Run the pipeline using: python main.py
Launch dashboard using: streamlit run app.py
Note: The dataset is not included due to its large size. The model is trained locally using full data. Sample data can be used for testing.

This project demonstrates how machine learning and domain knowledge can be combined to make better business decisions in retail demand forecasting.

Username admin
Pssword admin123
