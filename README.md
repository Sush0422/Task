This project focuses on Exploratory Data Analysis (EDA) and Churn Feature Analysis for a telecommunications company. The goal is to identify the key drivers that cause customers to leave (churn) and provide actionable insights for retention strategies.

 Tech Stack
Language: Python 3.x

Libraries: * Pandas: Data manipulation and cleaning.

NumPy: Numerical operations.

Matplotlib & Seaborn: Advanced data visualization.

Environment: Jupyter Notebook / VS Code.

 Data Cleaning Process
Before analysis, the dataset underwent several cleaning steps:

Handling Data Types: Converted TotalCharges from an object (string) to a numeric float.

Missing Value Imputation: Handled 11 missing values in TotalCharges using the median value to maintain data integrity.

Irrelevant Features: Dropped customerID as it provides no predictive or descriptive value.

Target Encoding: Transformed the Churn variable into a numeric format for correlation analysis.

 Key Insights & Feature Analysis
1. Contract Type Impact

Observation: Customers on Month-to-month contracts have the highest churn rate (over 40%).

Insight: Long-term contracts (1 or 2 years) act as a significant barrier to churn.

2. Tenure & Loyalty

Observation: There is a clear "Danger Zone" in the first 6 months of tenure.

Insight: New customers are at the highest risk. Retention efforts should focus on the initial onboarding phase.

3. Service Quality (Fiber Optic)

Observation: Fiber Optic users churn at a higher rate than DSL users despite the higher speed.

Insight: This suggests issues with either the high price point of fiber or potential service reliability problems.

4. Support Services

Observation: Customers without TechSupport or OnlineSecurity are significantly more likely to churn.
