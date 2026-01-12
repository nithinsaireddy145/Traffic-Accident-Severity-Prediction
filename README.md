Project Overview
Road accidents are a major global concern and cause thousands of preventable deaths every year. This project applies data analytics and machine learning to identify key factors contributing to accident severity and propose actionable safety recommendations. The goal is to build a predictive system that supports traffic authorities, city planners, and public safety initiatives.

Objectives
Identify critical risk factors influencing accident severity
Analyze trends across time, geography, weather, and road conditions
Build predictive machine learning models to classify or forecast accident severity
Provide data-driven recommendations to improve road safety
Dataset Information
Source: Kaggle – Key Factors in Traffic Accidents Dataset
Key Features Include:
Accident time and location
Weather conditions
Road quality (pavement, lighting, traffic signals)
Vehicle count and speed
Severity indicators (injuries, fatalities)
Data Cleaning Steps: Missing value imputation, outlier treatment, encoding categorical variables, feature normalization.
Tech Stack
Category	Tools/Technologies
Programming	Python (Pandas, NumPy, Scikit-learn, Matplotlib)
Modeling	Voting Regressor, Random Forest, XGBoost, CatBoost, Linear/Ridge/Lasso Regression
Feature Engineering	Encoding, MinMaxScaler, Custom Severity Metrics
Visualization	Matplotlib, Seaborn, Geospatial Analysis
Evaluation Metrics	R² Score, MSE, RMSE, Cross-Validation
Exploratory Data Analysis – Key Insights
Poor road conditions, rainfall, and high vehicle speed significantly increase accident severity
Most accidents occur during evening/night hours and in busy urban intersections
Traffic congestion and pavement issues show strong correlation with accident frequency
Higher accident rates in poorly lit or unregulated traffic areas
Machine Learning Models & Results
Model	Performance (R² Score)	Key Notes
Voting Regressor	0.8453	Best performer
XGBoost / CatBoost	High accuracy	Handles non-linear patterns well
Random Forest	Good baseline	Robust to noise
Linear / Ridge / Lasso	Baseline models	Used for comparison
✔ Most influential features: traffic signal presence, vehicle speed, road surface condition, total vehicle count

Geospatial & Temporal Insights
Urban Clusters: High accident density at intersections & city centers
Time-Based Trends: Evening rush hours and weekends show peak incidents
Road Infrastructure: Poor pavement, lack of signage, and low visibility contribute to accidents
Recommendations
Area	Suggestion
Infrastructure	Improve road lighting, signage, and pavement maintenance
Speed Management	Enforce speed limits in high-risk areas
Traffic Signals	Optimize timing using historical congestion and accident patterns
Public Awareness	Awareness campaigns for night-time and rainy conditions
