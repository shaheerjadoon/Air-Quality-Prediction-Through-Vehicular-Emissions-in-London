1. Project Overview
Title: Air Quality Prediction and Recommendation
Description: This project focuses on predicting vehicular emissions in London using advanced Machine Learning techniques like Random Forest, Decision Tree, XGBoost, and Neural Networks. It utilizes data from 2010, 2013, 2016, and 2019 to forecast pollutants like NOx, PM10, PM2.5, and CO2 emissions. An interactive Streamlit dashboard was developed for stakeholders to visualize actual and predicted emissions, aiding policymakers in making informed decisions to reduce pollution in urban environments.
2. Technologies Used
Programming Languages: Python
Libraries/Tools: Pandas, XGBoost, Random Forest, Decision Tree, Neural Networks, Plotly, Streamlit
Data Source: London Atmospheric Emission Inventory (LAEI)
Data Visualizations: Bar charts, Violin plots, Scatter plots, Correlation matrices
3. Key Features
Predictive Models:
Neural Networks: Achieved R² = 0.988 with low error values, demonstrating robust predictions for future emissions.
XGBoost: Top-performing model with R² = 0.994 and minimal error rates, making it a reliable option for emissions prediction.
Streamlit Dashboard: Provides an interactive interface where users can select years, models, and pollutants to visualize predictions vs. actual emissions. Custom visualizations like bar charts and violin plots allow deeper exploration of the data.
Data Preprocessing: Handled missing data through categorical imputation, normalization, and standardization for consistent model training.
4. Project Details
Data Structure: The emissions data was structured by pollutant concentrations (NOx, NO2, CO2, PM10, PM2.5) and vehicle types, collected across different boroughs in London for the years 2010, 2013, 2016, and 2019.
Challenges Solved:
Addressed data inconsistencies across years, particularly between the 2016 and 2019 datasets, by harmonizing data.
Tackled computational challenges in predictive modeling and avoided overfitting using cross-validation and hyperparameter tuning.
5. Model Performance
Neural Network (2013 emissions):
R² = 0.988, MSE = 397.55, MAE = 2.84
XGBoost (2016 emissions):
R² = 0.994, MSE = 187.60, MAE = 1.03
Random Forest and Decision Tree models were also implemented and showed competitive performance but with slightly lower predictive power compared to XGBoost and Neural Networks.
6. Visualizations
Emissions Trends: Visualized pollutant emissions across boroughs and vehicle types from 2010 to 2019 using scatter plots and bar charts.
Weather Variables Impact: Explored the relationship between emissions and weather data (temperature, humidity, precipitation) through correlation matrices and scatter plots.

8. Case Study/Key Takeaways
Problem Solved: Forecasted how vehicular emissions contribute to London’s air pollution and provided insights for policymakers to implement strategies like expanding Ultra Low Emission Zones (ULEZ).
Impact: This project demonstrates how machine learning can assist in managing urban air quality by predicting future emission levels and offering insights into effective policy measures for pollution reduction.
