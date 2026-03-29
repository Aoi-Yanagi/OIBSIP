# Car Price Prediction using Machine Learning

## 🎯 Objective
The primary goal of this project is to build a predictive model that estimates the selling price of used cars based on various features such as the car's age, current market price, distance driven, fuel type, and transmission. This helps in understanding the depreciation and market value of vehicles.

## 🛠️ Tools Used
* **Python**: The core programming language used for the analysis.
* **Pandas & NumPy**: For data manipulation, cleaning, and handling categorical variables.
* **Matplotlib & Seaborn**: For static data visualizations, including price distribution and feature importance.
* **Scikit-Learn**: For building the machine learning pipeline, including data splitting, the Random Forest model, and evaluation metrics.

## 📝 Steps Performed
1.  **Data Loading & Cleaning**:
    * Loaded the car dataset containing 301 records.
    * Handled missing values by dropping incomplete rows to ensure model stability.
2.  **Feature Engineering**:
    * Separated the target variable (`Selling_Price`) from the independent features.
    * Used **One-Hot Encoding** (via `pd.get_dummies`) to convert categorical text data (like Fuel Type, Transmission, and Car Name) into numerical format suitable for machine learning.
3.  **Model Training**:
    * Split the data into an 80% training set and a 20% testing set.
    * Initialized and trained a **Random Forest Regressor** with 100 estimators.
4.  **Evaluation & Visualization**:
    * Calculated error metrics like Mean Absolute Error (MAE) and R-Squared (Accuracy).
    * Generated visualizations to compare actual vs. predicted prices and to identify the most influential factors in car pricing.

## 📈 Outcome in Brief
* **Model Accuracy**: The Random Forest model achieved a high accuracy of **96.73%** (R-Squared) on the test data.
* **Error Margin**: The Mean Absolute Error was approximately **0.59**, meaning the model's price predictions are off by only a small margin on average.
* **Key Insights**: 
    * The **Present Price** (current market price of a new version of the car) was the most significant factor in determining the used car's value.
    * The **Year** of manufacture and the **Distance Driven** also played critical roles in the valuation process.