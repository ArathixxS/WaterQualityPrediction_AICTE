# WaterQualityPrediction_AICTE
* The project aims to predict multiple water quality parameters using machine learning techniques,specifically MultiOutputRegressor wrapped around a RandomForestRegressor.

# Overview
* Used actual water quality datasets that were already collected and cleaned (preprocessed).
Applied machine learning techniques (specifically multi-target regression) to predict multiple water quality values at once.
Created a machine learning pipeline using a MultiOutputRegressor combined with RandomForestRegressor — this means you trained one model that can predict many outputs simultaneously.
Evaluated how well the model works using standard measures used in regression tasks .

# Technologies used 
Python 3.12
Pandas, NumPy – For data handling
Scikit-learn – For building and evaluating the machine learning model
Matplotlib, Seaborn – For data visualization
Jupyter Notebook – For interactive experimentation and development

# Predicted Water Quality Parameters
The model predicts multiple water quality parameters such as:

NH4
BOD5 (BSK5)
Colloids
O2, NO3, NO2, SO4, PO4 and
CL

# Model Perfomance
 The model was evaluated using 
 
 R² Score
Mean Squared Error (MSE)
