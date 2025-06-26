## PROJECT 1- Customer Lifetime Value Prediction Model
## Objective
- To accurately predict Customer Lifetime Value using historical customer data, including demographics and behavioral patterns. The goal is to help businesses:

- Improve marketing ROI through customer segmentation.

- Focus on high-value customers.

- Drive personalized strategies for retention and growth.
---
## Dataset
- File Used: Customer_Lifetime_Value_Prediction.csv

- Key Features:

- Demographics: Age, Gender, Tenure

- Behavioral: NumPurchases, TotalSpend, AvgPurchaseValue, RecencyDays, FrequencyPerMonth

- Target: LifetimeValue (continuous)
- -
## Tools & Technologies
- Python: pandas, numpy, matplotlib, seaborn, scikit-learn

- Excel: Dashboard with visual insights

- Machine Learning: Random Forest Regressor (main model)

-- 
## Methodology
- Data Cleaning:

- Handled missing values and outliers.

- Converted data types appropriately.

- Removed duplicates.

- Feature Engineering:

- Derived Recency, Frequency, and Avg Purchase Value.

- Standardized numeric values.

- One-hot encoded categorical features.

- Model Building:

- Used RandomForestRegressor and optionally XGBoost.

- Evaluated with MAE and RMSE.

- Random Forest was chosen for final predictions.

- Segmentation:

- Used pd.qcut() to divide predicted CLTV into 3 segments: Low, Medium, High.

- Visualization:

- EDA plots, heatmaps, boxplots.

- Excel dashboard: Pie, Line, and Bar charts.

--
## Results
- Model Metrics:

- MAE ≈ 338.79

- RMSE ≈ 457.30

- Customer Segments:

- Low: 334 customers | Avg LTV ≈ 1897.75

- Medium: 333 customers | Avg LTV ≈ 3478.33

- High: 333 customers | Avg LTV ≈ 5358.38

--
## Key Insights
- Most customers fall in the Low-Medium range—potential to upsell.

- High LTV customers are fewer but generate significant revenue.

- Recency-Frequency relationship can signal churn risks or loyal behavior.

- Medium-value customers can be nurtured to become high-value.

--
## Deliverables
-  Python Notebook (CLTV.ipynb)

-  Final Predictions CSV (final_ltv_predictions.csv)

 - Excel Report with Charts

-  PDF Summary Report (LTV_Prediction_Report.pdf)

- Documentation (CLTV.odt)
- --
##Insights (approx. 100 words)
- Segment Distribution: The majority of customers are in the Low and Medium LTV segments, indicating a large base with potential for upselling.

- High-Value Customers: Though fewer in number, High LTV customers contribute a significant portion of the predicted revenue—these should be prioritized for VIP programs, exclusive offers, and retention strategies.

- Churn Analysis: Customers with low frequency and high recency may be at risk of churn and need targeted re-engagement.

-Demographics: Males and Gold segment members tend to have higher predicted LTV.
## Conclusion 
- In this project, a robust Customer Lifetime Value (CLV) Prediction Model was developed using customer demographic and behavioral data. The Random Forest Regressor was chosen due to its strong performance and reliability with tabular data, achieving good prediction accuracy (MAE ≈ 338.79, RMSE ≈ 457.30). Post-prediction, customers were segmented into Low, Medium, and High value groups using quantile-based binning. This segmentation is vital for targeted marketing, customer retention, and optimizing business resources.

- A comprehensive Excel dashboard was created to visualize segment distribution, customer trends, and feature impacts, making insights accessible for both technical and non-technical stakeholders. The analysis revealed that High LTV customers, although fewer, drive substantial value, and Medium segment customers show strong potential for growth. By applying these insights, businesses can make data-driven decisions, personalize outreach, improve customer engagement, and ultimately enhance profitability. The CLV model thus serves as a valuable tool in strategic customer management.
----



## PROJECT2 - HR Analytics - Predict Employee Attrition
## Objective
- To analyze HR data and build a predictive model that can identify employees likely to leave the organization, helping HR teams take proactive measures to reduce attrition.
- --

## Project Structure
- HR_Attrition_Dataset.csv – Main dataset used for training and analysis.

- HR_Analysis_Prediction.ipynb – Python notebook with preprocessing, model building, and evaluation.

- HR_Attrition_Model_Accuracy_Report.pdf – Report showing performance metrics of the model.

- Attrition_Prevention_Suggestions.pdf – Business suggestions based on findings.

- hr_attrition_powerbi.csv – Cleaned dataset used in Power BI for visualization.

- Visual Output/ – Contains plots from the analysis.

- HR_ analysis_prediction_dashboard.twb – Tableau dashboard file.

- Hr_analysis_ prediction.pdf – A summarized project report.
---

## Workflow Summary
## Data Cleaning & Preprocessing:

- Handled missing values and categorical encoding.

- Feature engineering applied to generate meaningful features.

- Exploratory Data Analysis (EDA):

- Used visualization to find key patterns in attrition trends.

-- 
  ## Model Building:

- Machine Learning model built using XGBoost.

- Achieved classification accuracy (detailed in PDF report).

--
## Dashboard:

- Interactive dashboards created in Tableau  for HR insights.
--
## Insights:

- Identified departments with high attrition.

- Suggested retention strategies.
- --
## Tools Used
- Python (Pandas, Sklearn, XGBoost)

- Tableau

- Jupyter Notebook
- --
## Model Performance
- Metrics are provided in HR_Attrition_Model_Accuracy_Report.pdf.

- Accuracy: (exact value to be confirmed from report, or code execution if needed)
- --
##  Key Insights
## Work-Life Balance is Crucial

- Employees with poor work-life balance were more likely to leave.

- Overtime and high workload significantly increased attrition risk.

## Recognition Drives Retention

- Employees who feel appreciated and recognized tend to stay longer.

- Lack of appreciation or celebration of milestones correlated with higher attrition.

## Career Growth Opportunities Are Vital

- Employees without clear promotion paths or learning opportunities were more prone to leave.

- Upskilling and professional development had a positive impact on retention.
  ##Employee Engagement & Feedback Matters

## Teams with lower engagement scores had higher turnover.

- Regular feedback loops built trust and reduced resignation rates.

  ## Compensation Issues

- Salary dissatisfaction was a strong predictor of attrition.

- Non-transparent bonus structures led to mistrust.
- --
##  Conclusion
- This HR analytics project successfully identified key drivers of employee attrition using machine learning and data analysis. The model’s predictions allow HR teams to proactively retain top talent by focusing on:

- Enhancing employee experience through flexible work, recognition, and career development.

- Conducting regular surveys and acting on feedback.

- Providing competitive, transparent compensation.

- Targeting high-risk groups for support before resignation occurs.

- By integrating these insights into daily HR practices and dashboards (via Power BI/Tableau), the organization can reduce turnover, improve morale, and save costs associated with hiring and training.
