Cardiovascular Disease Analysis 

This project presents a comprehensive analysis of cardiovascular disease (CVD) risk using a large patient dataset. The analysis integrates data cleaning, feature engineering, descriptive statistics, predictive modeling, clustering, and data visualization to extract meaningful insights applicable to healthcare decision-making and business intelligence.

1. Data Preparation and Understanding

The raw dataset was first imported and cleaned to ensure consistency and reliability. Key steps included:

Feature Engineering:

age_years was calculated by converting patient age from days to years.

BMI (Body Mass Index) was derived from weight and height.

Categorical Variables Transformation: Coded variables such as gender, cholesterol, gluc, smoke, alco, active, and cardio were converted into descriptive factor labels.

Outlier Filtering: Records with unrealistic values in blood pressure (ap_hi, ap_lo), BMI, or height were removed to improve data quality.

The final dataset contained no missing values and was ready for exploratory and predictive analysis.

Insight: Patients with CVD were generally older and had higher blood pressure and BMI, highlighting key risk indicators.

2. Descriptive Analytics

Exploratory analysis revealed important patterns:

Correlation Analysis: Positive correlations were observed among age_years, ap_hi, and ap_lo. BMI and weight were strongly correlated, reflecting their physiological relationship.

Age Distribution: Most patients fell between 50–65 years of age, consistent with the age range where cardiovascular risk increases.

Patient Counts: The dataset was well-balanced with respect to disease outcome, allowing fair modeling without bias toward a particular class.

3. Business Intelligence Insights

Comparative Analysis: Average blood pressure, BMI, and age were higher in patients with CVD.

Statistical Testing: ANOVA confirmed significant differences in systolic blood pressure between patients with and without cardiovascular disease.

Predictive Modeling:

Logistic Regression: Identified key predictors such as ap_hi (systolic blood pressure), cholesterol, and age_years. Odds ratios were used to quantify the effect of each variable on disease risk.

K-Nearest Neighbors (KNN): Served as an alternative model, optimized with cross-validation.

Model Comparison: Logistic Regression slightly outperformed KNN in both accuracy and AUC, making it a robust choice for CVD prediction.

Implication: Blood pressure management, cholesterol monitoring, and attention to BMI and age are critical factors in predicting and preventing CVD.

4. Big Data Analytics – Clustering

K-Means Clustering: Identified three distinct patient groups based on numeric features.

Cluster-Outcome Alignment: Cluster membership corresponded meaningfully with disease presence, highlighting natural patient groupings that can inform preventive strategies.

5. Data Visualization

Glucose Levels: Boxplots showed differences in glucose levels across CVD outcomes, though less pronounced than blood pressure differences.

Age vs. Systolic BP: Scatterplots revealed that older patients with higher systolic blood pressure had higher disease prevalence, visually confirming the importance of these factors.

Insight: Visualizations reinforced statistical findings and helped identify key high-risk patient segments.

6. Key Takeaways

Age, systolic blood pressure, and BMI are primary predictors of cardiovascular disease.

Logistic Regression provides the most reliable predictive model for this dataset.

Clustering reveals patient subgroups that may benefit from targeted preventive care.

Visual analytics effectively communicates patterns and supports decision-making for healthcare professionals.

Conclusion: This analysis combines statistical, predictive, and visual methods to provide a holistic understanding of cardiovascular disease risk, offering actionable insights for healthcare analytics, policy-making, and patient management.
