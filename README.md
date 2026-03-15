# 📊 ISP Customer Churn Analysis & Retention Strategy
**EverConnect Business Case | RevoU Data Analytics Capstone**

## 🎯 Project Background
EverConnect is a telecommunications provider aiming to reduce its **55.70% churn rate**. This project utilizes data-driven insights to identify churn drivers and provide actionable recommendations to improve customer retention by **15% within 12 months**.

## 🛠️ Methodology & Tools
Followed a structured 5-step data analytics process:
1. **Business Understanding**: Defining objectives to reduce churn and maximize CLV.
2. **Data Research**: Understanding dataset features and constraints from Kaggle.
3. **Data Cleaning**: Utilizing **Python** and **Spreadsheets** for pre-processing.
4. **Exploratory Data Analysis**: Visualizing trends in **Tableau** and **Python**.
5. **Insights & Recommendations**: Generating strategic business logic based on findings.

## 🔍 Key Findings
* **Contract Impact**: Customers with fewer years left on their contract are significantly more likely to churn.
* **Usage Correlation**: There is a clear uptrend in retention as data usage increases; loyal customers average **64.88 GB** vs churned at **26.84 GB**.
* **Subscription Age**: Longer subscription durations correlate with higher **Customer Lifetime Value (CLV)**.
* **TV Service Risk**: Majority of churned customers are TV subscribers, while Movie Package users show very low risk.

## 🤖 Predictive Modeling & Segmentation
### Machine Learning Performance
* **Model**: Random Forest Classifier.
* **Accuracy**: **93.41%** | **ROC-AUC**: **96.2%**.
* **Top Predictors**: Remaining Contract, Bill Average, and Service Failure Count.

### K-Means Customer Segmentation
| Cluster | Segment Name | Churn Rate | Key Strategy |
| :--- | :--- | :--- | :--- |
| 0 | Basic TV Subscribers | 57.45% | Offer bundle services to increase stickiness. |
| 1 | Engaged Movie Users | 33.99% | Maintain loyalty with exclusive content. |
| 2 | Heavy Data (Service Issues) | 55.67% | Address network reliability and service quality. |
| 3 | High Churn (No TV) | **90.59%** | Personalize re-engagement or upgrade offers. |

## 💡 Strategic Recommendations
1. **Retention for TV Subscribers**: Implement personalized loyalty programs for Cluster 0.
2. **Infrastructure Focus**: Improve service quality for Cluster 2 to reduce dissatisfaction-driven churn.
3. **Acquisition Alignment**: Target "No TV" users with entry-level bundles to secure early retention.
4. **Predictive Intervention**: Use the Random Forest model to flag at-risk customers for proactive outreach.

---
**Links:**
* [Full Dataset (Kaggle)](https://www.kaggle.com/datasets/mehmetsabrikunt/internet-service-churn)
* [Interactive Tableau Dashboard](https://public.tableau.com/app/profile/steven.setiawan/viz/DEEPP-EverConnectInternetServiceProvider-StevenWijayaSetiawan/Dashboard1?publish=yes)
