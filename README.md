# 📉 Customer Churn & Retention Analytics

**Tools:** Python · SQL · Power BI · Statistics

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses. This project analyzes telecom customer data to identify churn patterns, understand the factors associated with customer attrition, and develop data-driven retention strategies.

Using Python, SQL, statistical hypothesis testing, and Power BI, this project transforms customer data into actionable business insights.

## 🎯 Business Objectives

- Measure the overall customer churn rate.
- Identify customer segments with higher churn risk.
- Analyze the relationship between churn and contract type, internet service, and payment method.
- Evaluate churn patterns across customer tenure.
- Build an interactive Power BI dashboard.
- Recommend strategies to improve customer retention.

## 📊 Dataset Overview

- **Dataset:** Telecom Customer Churn
- **Total Records:** 7,043 customers
- **Attributes:** 21
- **Target Variable:** Churn
- **Domain:** Telecommunications

The dataset contains customer demographics, account information, subscribed services, contract details, payment methods, tenure, and churn status.

**Dataset Source:** [Add your actual Kaggle dataset link here]

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data cleaning and manipulation |
| Matplotlib | Data visualization |
| SQL | Customer segmentation and churn analysis |
| Statistics | Chi-square hypothesis testing |
| Power BI | Interactive retention dashboard |

## 🔄 Project Workflow

1. **Data Understanding:** Inspected the dataset structure, columns, and data types.
2. **Data Cleaning:** Checked missing values, duplicates, and inconsistent data.
3. **Exploratory Data Analysis:** Examined churn patterns across customer segments.
4. **SQL Analysis:** Queried customer records to calculate churn rates and compare groups.
5. **Statistical Testing:** Applied chi-square tests to evaluate associations between categorical variables and churn.
6. **Dashboard Development:** Created an interactive Power BI dashboard to explore customer retention.
7. **Business Recommendations:** Converted analytical findings into practical retention strategies.

## 📈 Key Performance Indicators

- Total Customers: 7,043
- Overall Churn Rate: 26.5%
- Month-to-Month Contract Churn: 42.7%
- Two-Year Contract Churn: 2.8%
- First-Year Customer Churn: 47.4%

*Figures are based on the project's reported analysis. Verify that each metric uses the intended customer group and denominator before publication.*

## 🔍 Key Insights

### 1. Overall Customer Churn
The overall churn rate was 26.5%, indicating that approximately one in four customers in the analyzed dataset had churned.

### 2. Contract Type
Month-to-month customers had a churn rate of 42.7%, compared with 2.8% for customers on two-year contracts. This highlights a strong association between contract type and customer retention.

### 3. Customer Tenure
First-year customers experienced a churn rate of 47.4%, highlighting early customer tenure as an important period for retention efforts.

### 4. Customer Services and Payments
Internet service and payment method were also associated with churn patterns in the analysis, helping identify customer segments that may benefit from targeted retention strategies.

## 🧪 Statistical Analysis

Chi-square tests of independence were used to examine associations between customer churn and selected categorical variables.

The analysis reported statistically significant associations for:

- Contract Type
- Internet Service
- Payment Method

**Reported significance:** p < 0.001.

These results suggest that the observed relationships are unlikely to be explained by random variation alone under the test assumptions. However, statistical association does not establish causation.

## 💡 Business Recommendations

### 1. Encourage Long-Term Contracts
Offer suitable discounts or benefits to month-to-month customers to encourage longer contract commitments.

### 2. Improve First-Year Retention
Introduce onboarding support, early engagement campaigns, and proactive customer check-ins during the first year.

### 3. Personalize Retention Campaigns
Use churn patterns across internet services and payment methods to identify segments for further investigation and targeted offers.

### 4. Monitor Churn KPIs
Track churn rate, customer tenure, contract mix, and segment-level retention through a regularly updated dashboard.

## 📊 Power BI Dashboard

The dashboard is designed to present:

- Overall churn rate and customer count.
- Churn comparison by contract type.
- Churn patterns by tenure.
- Churn breakdown by internet service and payment method.
- Interactive filters for exploring customer segments.

**Dashboard Preview:** Add screenshots of your completed Power BI dashboard to the repository.

## 📁 Repository Structure

```text
customer-churn-retention-analytics/
├── data/
│   └── README.md
├── notebooks/
│   └── customer_churn_analysis.ipynb
├── sql/
│   └── churn_analysis.sql
├── powerbi/
│   └── customer_retention_dashboard.pbix
├── screenshots/
│   └── dashboard_preview.png
├── requirements.txt
└── README.md
```

Update the filenames and folders to match your actual repository.

## ▶️ How to Run

1. Clone or download this repository.
2. Install the required Python libraries:

   ```bash
   pip install pandas matplotlib scipy jupyter
   ```

3. Download the dataset from the linked source.
4. Place the dataset in the appropriate
