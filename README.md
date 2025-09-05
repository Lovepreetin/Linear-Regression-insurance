This project applies regression techniques to predict medical insurance charges based on a rich dataset of demographic, lifestyle, and healthcare-related features. 
It demonstrates end-to-end data science workflow including EDA, feature engineering, model training, and evaluation.

📂 Dataset Description
Source: insurance_data.csv

Rows: 1300+ entries

Features:

age, sex, bmi, children, smoker, region

claim_amount, past_consultations, num_of_steps

hospital_expenditure, number_of_past_hospitalizations

annual_salary, charges (target)

🔍 Exploratory Data Analysis
Checked for missing values and outliers

Visualized distributions and relationships (e.g., BMI vs. charges)

Correlation heatmaps and pairplots for feature insights

VIF analysis to detect multicollinearity
![Correlation Heatmap](images/correlation_heatmap.png)

🧠 Modeling Approach
Baseline: Linear Regression

Feature Engineering:

Outlier handling using IQR(inter quantile range) approach.

Evaluation Metrics:

R² Score, Mean Squared Error (MSE),RMSE

📈 Results
Achieved strong predictive performance with 82% r2 score.
![Residual Plot](images/residual.png)
![Regplot](images/regplot.png)

🧪 Future Enhancements
Add SHAP values for model interpretability

Deploy using Streamlit or Flask

Integrate with SQL database for real-time predictions

🛠️ Tech Stack
Python, pandas, NumPy, matplotlib, seaborn


scikit-learn, Jupyter Notebook
