# 🚗 Car Price Prediction  

## Introduction  
Welcome to the **Car Price Prediction** project!  
This app is a user-friendly tool designed to predict the selling price of a car based on its features, such as present price, car age, fuel type, and more. It allows users to explore datasets, perform Exploratory Data Analysis (EDA), train models, and predict prices using machine learning algorithms.  

---

## Features  
- Upload car dataset in CSV format.  
- Explore the dataset with summary statistics and visualizations.  
- Perform EDA with interactive plots using Plotly.  
- Train a machine learning model using a Random Forest Regressor.  
- Predict car selling prices based on user-provided inputs.  
- Visualize feature importances to understand key factors influencing price predictions.  

---

## Tools and Technologies Used  
- **Programming Language**: Python  
- **Framework**: Streamlit  
- **Data Analysis and Visualization**: Pandas, NumPy, Matplotlib, Seaborn, Plotly  
- **Machine Learning**: Scikit-learn (Random Forest Regressor)  
- **Interactive Visualizations**: Plotly Express  

---

## Dataset Description  
- The dataset includes car attributes such as:  
  - `Year`: Year of manufacturing.  
  - `Selling_Price`: Price of the car (target variable).  
  - `Present_Price`: Current showroom price of the car.  
  - `Fuel_Type`: Type of fuel used (Petrol/Diesel/CNG).  
  - `Transmission`: Type of transmission (Manual/Automatic).  
  - `Driven_kms`: Kilometers driven by the car.  

- **Preprocessing Steps**:  
  - Computed `Car_Age` as `2024 - Year`.  
  - Dropped irrelevant columns such as `Year` and `Car_Name`.  
  - One-hot encoded categorical columns (`Fuel_Type`, `Transmission`, `Selling_Type`).  

---

## Algorithms  
- **Random Forest Regressor**:  
  - A powerful ensemble learning method used for regression tasks.  
  - Combines multiple decision trees to improve model accuracy.  

---

## Workflow  
1. **Data Loading**: Upload CSV dataset.  
2. **Data Cleaning**: Handle missing values and preprocess data.  
3. **Exploratory Data Analysis (EDA)**: Analyze data distributions and correlations.  
4. **Model Training**: Train Random Forest Regressor with user-configured parameters.  
5. **Prediction**: Use the trained model to predict car prices.  

---

## Steps to Run the Project  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/car-price-prediction.git
   cd car-price-prediction
