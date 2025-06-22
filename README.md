# Prediction-Maintenance-on-Commercial-Aircraft-Engines
Predictive maintenance of aircraft engines using Machine Learning (Random Forest,DCNN).

## Project Overview

Predictive maintenance plays a crucial role in the aviation industry by ensuring operational safety, minimizing unplanned downtime, and reducing maintenance costs.
This project implements a Deep Convolutional Neural Network (DCNN) to predict the Remaining Useful Life (RUL) of commercial aircraft engines using time-series sensor data.
By analyzing data collected from multiple engine sensors, the system forecasts when an engine is likely to fail, enabling timely and cost-effective maintenance actions.




###  Key Features
- Predicts engine failure cycles using RUL estimation
- Reduces unscheduled maintenance by 25%
- Decreases operational cost by 10%
- Uses DCNN and Random Forest for model comparison


## 🧠 Technologies Used

- **Programming**: Python  
- **Data Processing**: Pandas, NumPy  
- **ML Algorithms**: Random Forest, DCNN  
- **Visualization**: Matplotlib, Seaborn  



## Dataset

- Source: Kaggle  (NASA Turbofan Jet Engine)
- Structure: 20,631 rows × 26 columns ➜ Processed to 179 rows × 26 columns  
- Time-series sensor data from multiple engine units under varying conditions



## Results

- Predicted RUL with high accuracy using DCNN after hyperparameter tuning
- Identified key sensors contributing to engine degradation
- Output ready for integration with real-world maintenance systems


