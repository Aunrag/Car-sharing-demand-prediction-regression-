# Car Sharing Demand Prediction

A machine learning project aimed at predicting hourly demand for car sharing services based on environmental, seasonal, and temporal features.

## Project Overview

The goal of this project is to build a regression model that can accurately forecast car sharing demand. By analyzing historical data, we identify key patterns and factors (like temperature, humidity, hour, and weekday) that influence the number of users at a given time.

## Dataset

The dataset contains hourly records of car sharing usage along with the following features:
- **Temperature**
- **Humidity**
- **Windspeed**
- **Hour of day**
- **Day of week**
- **Holiday / Working day**
- **Season**

## Tools & Technologies

- **Python**
- **Pandas, NumPy** – for data manipulation
- **Matplotlib, Seaborn** – for visualization
- **Scikit-learn** – for model training and evaluation
- **XGBoost** – for improved regression performance

## Key Steps

1. **Data Preprocessing**
   - Handling missing values
   - Feature engineering (hour, day, month, etc.)
   - Encoding categorical features

2. **Exploratory Data Analysis**
   - Visualizing feature correlations
   - Identifying seasonal patterns

3. **Modeling**
   - Linear Regression
   - Random Forest
   - XGBoost Regressor
   - Hyperparameter tuning using GridSearchCV

4. **Evaluation**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score

## Results

The XGBoost model performed best, showing:
- **MAE**: 76.537654
- **RMSE**: 139.969747
- **R² Score**: 0.945592 

## How to Run

```bash
# Step 1: Clone the repository
git clone https://github.com/your-username/car-sharing-demand-prediction.git
cd car-sharing-demand-prediction

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the notebook
jupyter notebook Car_Sharing_Demand_Prediction.ipynb

