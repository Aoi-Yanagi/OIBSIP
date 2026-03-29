# Sales Prediction using Machine Learning

## 🎯 Objective
The primary objective of this project is to build a predictive model that estimates sales based on advertising expenditures across different channels, such as TV, Radio, and Newspaper. By analyzing these relationships, businesses can better understand the impact of their marketing budget and optimize their future advertising strategies.

## 🛠️ Tools Used
* **Python**: The core programming language for the entire analysis.
* **Pandas**: Used for data manipulation and structured data handling.
* **Matplotlib & Seaborn**: Employed for data visualization, including plotting regression lines and error distributions.
* **Scikit-Learn**: The primary library for machine learning tasks, specifically for:
    * **Train-Test Split**: Dividing the data for model training and evaluation.
    * **Random Forest Regressor**: The machine learning algorithm used for prediction.
    * **Metrics**: Calculating performance indicators like Mean Squared Error and R-Squared.

## 📝 Steps Performed
1.  **Data Loading & Preparation**:
    * Imported the advertising dataset and inspected the initial rows to understand the feature structure.
    * Prepared the features (TV, Radio, Newspaper) and the target variable (Sales) for modeling.
2.  **Model Training**:
    * Split the dataset into training and testing sets to ensure the model can generalize to new data.
    * Trained a **Random Forest Regressor**, an ensemble learning method that provides robust predictions by averaging multiple decision trees.
3.  **Performance Evaluation**:
    * Assessed the model's accuracy using the **R-Squared (R2)** score, which measures how well the independent variables explain the variance in sales.
    * Calculated the **Mean Squared Error (MSE)** to quantify the average squared difference between predicted and actual values.
4.  **Visual Analysis**:
    * Created a **Residual Plot** to visualize the distribution of errors (Actual - Predicted), which helps in identifying any patterns the model might have missed.

## 📈 Outcome in Brief
* **Predictive Capability**: The model demonstrates a strong ability to predict sales figures based on the provided advertising data.
* **Error Distribution**: The residual analysis indicates that the model's predictions are generally well-aligned with actual sales, with most errors clustered around zero.
* **Optimization Potential**: The insights gained from this model allow for a data-driven approach to allocating advertising budgets to maximize sales returns.