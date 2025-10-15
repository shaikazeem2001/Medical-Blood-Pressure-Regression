# 📈 Medical-Blood-Pressure-Regression

## 💡 Overview
This project performs an exploratory data analysis (EDA) and correlation study on a medical dataset to understand the relationships between **Age**, **Systolic Blood Pressure (BP)**, and **Diastolic Blood Pressure (BP)**. The primary objective is to quantify the strength of these linear relationships as a preliminary step toward building a regression model for blood pressure prediction.

* **Skills:** Correlation Analysis, Pandas, NumPy, Regression Modeling (Conceptual), Data Preprocessing, Data Visualization.

## 🔑 Key Results
The correlation analysis provided clear quantitative insights into the relationships between the variables:

| Relationship | Correlation Coefficient (r) | Strength & Interpretation |
| :--- | :--- | :--- |
| **Systolic vs. Diastolic BP** | **0.6585** | **Strong Positive Correlation.** As expected, blood pressures move together. This provides a strong basis for a multivariate model. |
| **Age vs. Systolic BP** | **0.5148** | **Moderate Positive Correlation.** Indicates that as age increases, Systolic BP tends to increase. This suggests Age is a relevant predictor for a regression model. |
| **Age vs. Diastolic BP** | **0.3083** | **Weak-to-Moderate Positive Correlation.** The relationship between Age and Diastolic BP is weaker than with Systolic BP. |

These results confirm that Age is a more significant predictor for Systolic BP than for Diastolic BP in this dataset.

---

## 💻 Methodology & Files

1.  **Data Loading and Cleaning:** The medical dataset was loaded and inspected for missing values and anomalies.
2.  **Correlation Matrix:** Pearson correlation coefficients were calculated for all relevant variable pairs (Age, Systolic BP, Diastolic BP).
3.  **Visualization (Conceptual):** Scatter plots and a heatmap of the correlation matrix were used to visually confirm the linear relationships (ensure these visuals are included in the `.ipynb` file).
4.  **Regression Baseline (Conceptual):** The project likely sets the stage for a simple linear regression model to predict Systolic BP based on Age.

**Main File:** [`Blood_Pressure_Analysis.ipynb`](./Blood_Pressure_Analysis.ipynb) - *Convert your HTML file back to this .ipynb format for the best display on GitHub.*

## 🚀 How to Run

To execute the analysis, ensure you have the necessary libraries installed and run the Jupyter Notebook:

```bash
# Clone the repository
git clone [https://github.com/YourUsername/Your-Portfolio-Repo.git](https://github.com/YourUsername/Your-Portfolio-Repo.git)
cd Medical-Blood-Pressure-Regression

# Install required Python dependencies
pip install pandas numpy seaborn jupyter

# Launch the notebook
jupyter notebook Blood_Pressure_Analysis.ipynb
