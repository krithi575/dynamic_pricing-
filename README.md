# 🚕 Dynamic Pricing Prediction

This project builds and evaluates multiple machine learning models to **predict the historical cost of a ride** based on various customer, booking, and vehicle-related features.  
It uses **data preprocessing, feature engineering, exploratory data analysis (EDA), and multiple regression algorithms** to find the best-performing model.

---

## 📌 Features of the Project
- **Data Cleaning & Preprocessing**
  - Encoding categorical variables (e.g., Location_Category, Vehicle_Type, Time_of_Booking, Customer_Loyalty_Status).
  - Handling missing values using `SimpleImputer`.
  - Train-test split for model evaluation.

- **Exploratory Data Analysis (EDA)**
  - Histograms with mean/median indicators for numerical features.
  - Distribution plots for categorical features.
  - Outlier detection using Z-scores.
  - Correlation heatmaps.
  - Scatter plots & regression lines using Seaborn.

- **Machine Learning Models**
  1. **Linear Regression**
  2. **Decision Tree Regressor**
  3. **Random Forest Regressor**
  
  
- **Model Evaluation**
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score

- **Model Saving**
  - Trained models saved as `.pkl` files using `pickle`.

---

## 📊 Dataset
- **File**: `dynamic_pricing.csv`
- **Target Variable**: `Historical_Cost_of_Ride`
- **Example Features**:
  - `Location_Category` (Urban, Rural, Suburban)
  - `Customer_Loyalty_Status` (Silver, Regular, Gold)
  - `Vehicle_Type` (Premium, Economy)
  - `Time_of_Booking` (Night, Afternoon, Morning, Evening)
  - `Expected_Ride_Duration`, `Traffic_Conditions`, etc.

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/krithi575/dynamic_pricing.git
cd dynamic_pricing

# Install dependencies
pip install -r requirements.txt

# Run the script
python main.py
