# Unemployment Analysis with Python 📊

## 🎯 Objective
The primary goal of this project is to analyze the unemployment landscape in India, with a specific focus on the period surrounding the COVID-19 pandemic in 2020. By examining the relationships between unemployment rates, employment counts, and labor participation, this analysis identifies which states and regions were most economically impacted.

---

## 🛠️ Tools & Libraries
The analysis was performed using **Python** and several key data science libraries:
* **Pandas**: For data cleaning, manipulation, and structural analysis.
* **NumPy**: For efficient numerical computations.
* **Matplotlib & Seaborn**: For generating static visualizations and statistical heatmaps.
* **Plotly Express**: For creating high-level interactive visualizations (Sunburst charts).

---

## 📝 Steps Performed
1.  **Data Acquisition**: Imported the dataset containing regional unemployment statistics up to late 2020.
2.  **Data Wrangling**: 
    * Stripped whitespace from column names.
    * Handled missing values by dropping empty rows.
    * Renamed columns (e.g., `Region` to `State`) for better code readability.
3.  **Feature Engineering**: Extracted the `Month` from the date column to facilitate time-series grouping.
4.  **Exploratory Data Analysis (EDA)**:
    * Built a **Correlation Heatmap** to understand the dependencies between labor participation and unemployment.
    * Calculated mean unemployment rates across various Indian states.
5.  **Interactive Visualization**: 
    * Developed a **Sunburst Chart** using Plotly to allow users to click and zoom into specific regions and states for a granular view of the data.

---

## 📈 Outcome in Brief
* **Visual Insights**: The project successfully visualized the sharp economic fluctuations caused by the 2020 lockdowns.
* **Regional impact**: Identified specific clusters and states where the unemployment rate peaked most aggressively.
* **Data-Driven Conclusion**: The correlation analysis highlighted that while employment numbers dropped, the labor participation rate showed varied resilience across different sectors (Rural vs. Urban).

---

## 🚀 How to Run
1. Ensure you have Python installed.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly`
3. Open the `unemployment_analysis.ipynb` in Jupyter Notebook or VS Code and run all cells.