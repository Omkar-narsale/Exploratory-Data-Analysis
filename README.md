# 📊 Exploratory Data Analysis (EDA)

A collection of Exploratory Data Analysis (EDA) projects built using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. Each project focuses on cleaning real-world datasets, performing exploratory analysis, creating insightful visualizations, and extracting actionable business insights.

---

# 🚀 Repository Overview

This repository contains multiple EDA projects covering different domains such as retail, entertainment, healthcare, transportation, mobile applications, and survival analysis.

## 📂 Repository Structure

```text
Exploratory-Data-Analysis/
│
├── German_Credit_Risk_Analysis.ipynb
├── Loan_Approval_Prediction_Analysis.ipynb
├── IBM_Telco_Customer_Churn_Analysis.ipynb
├── Hotel_Booking_Cancellation_Analysis.ipynb
├── Bank_Customer_Churn_Analysis.ipynb
├── HR_Analytics_Job_Change_Analysis.ipynb
├── Superstore_Sales_Analysis.ipynb
├── Netflix_EDA.ipynb
├── Titanic_EDA.ipynb
├── Google_Playstore_Analysis.ipynb
├── Flight_Price_Analysis.ipynb
├── Wine_Quality_Analysis.ipynb
│
├── datasets/
│   ├── loan_approval_dataset.csv
│   ├── german_credit_data.csv
│   ├── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   ├── hotel_bookings.csv
│   ├── Bank_Churn.csv
│   ├── aug_train.csv
│   ├── Sample-Superstore.csv
│   ├── netflix_titles.csv
│   ├── titanic.csv
│   ├── googleplaystore.csv
│   ├── flight_price.xlsx
│   └── winequality-red.csv
│
└── README.md
```

---

# 📚 Projects Included
---
# 🏦 Loan Approval Analysis

## 🎯 Objective

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on a **Loan Approval** dataset to identify the key factors influencing loan approval decisions. The analysis focuses on understanding how applicant demographics, financial characteristics, credit history, loan attributes, and home ownership are associated with loan approval outcomes, providing actionable business insights that can support better lending decisions and effective credit risk management.

---

## 📊 Analysis Performed

- Performed data understanding and dataset inspection.
- Checked for missing values, duplicate records, and data types.
- Created grouped features using feature binning for better business interpretation:
  - Income Group
  - Loan Amount Group
  - Credit Score Group
  - Experience Group
  - Loan Percentage Group
  - Interest Rate Group
- Performed descriptive statistical analysis of numerical variables.
- Conducted **Univariate Analysis** to understand applicant demographics, financial characteristics, loan attributes, and loan approval distribution.
- Conducted **Bivariate Analysis** to examine relationships between loan approval and:
  - Person Income
  - Loan Intent
  - Loan Percentage of Income
  - Home Ownership
- Performed supporting analyses to validate business hypotheses using:
  - Income Group vs Loan Amount
  - Loan Intent vs Loan Amount
  - Loan Percentage of Income vs Income Group
  - Home Ownership vs Income Group
- Conducted **Multivariate Analysis** using a correlation heatmap to identify relationships among numerical variables.
- Derived business-focused insights and actionable recommendations based on the findings.

---

## 💡 Key Insights

- Applicants with **higher incomes** demonstrated significantly higher loan approval rates, while supporting analysis showed that higher-income applicants generally applied for larger loan amounts, indicating stronger repayment capacity.
- **Loan Intent** influenced approval decisions, suggesting that the purpose of borrowing plays an important role in lending risk assessment.
- Applicants with a **lower Loan Percentage of Income** experienced higher approval rates, while applicants with higher loan burdens were more likely to face rejection, highlighting the importance of affordability in lending decisions.
- Applicants with **Mortgage** home ownership showed higher loan approval rates and were predominantly concentrated in higher income groups, indicating greater financial stability and lower perceived lending risk.
- The correlation heatmap revealed that **financial variables**, including income, loan amount, loan percentage, credit history, and credit score, exhibited stronger relationships with loan approval than demographic characteristics, emphasizing that financial strength is the primary driver of lending decisions.
---
# 📊 IBM Telco Customer Churn Analysis

## 🎯 Objective

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on the **IBM Telco Customer Churn** dataset to identify the key factors associated with customer churn. The analysis aims to uncover patterns in customer demographics, service subscriptions, contract types, pricing, and billing behavior to generate actionable business insights that can help telecom companies improve customer retention and reduce churn.

---

## 📊 Analysis Performed

- Performed data understanding and dataset inspection.
- Checked for missing values, duplicate records, and data types.
- Converted the **TotalCharges** column to the appropriate numeric data type.
- Created **Tenure Groups** and **Monthly Charges Groups** using feature binning for better analysis.
- Performed descriptive statistical analysis of numerical variables.
- Conducted **Univariate Analysis** to understand customer demographics, telecom services, billing information, and churn distribution.
- Conducted **Bivariate Analysis** to examine relationships between customer churn and:
  - Payment Method
  - Contract Type
  - Internet Service
  - Online Security
  - Tenure Group
  - Gender
  - Tech Support
  - Monthly Charges Group
- Performed supporting analyses to validate business hypotheses using:
  - Payment Method vs Contract
  - Internet Service vs Monthly Charges Group
  - Contract vs Tenure Group
  - Tech Support vs Contract
- Conducted **Multivariate Analysis** using a correlation heatmap to identify relationships among numerical variables.
- Derived business-focused insights and actionable recommendations based on the findings.

---

## 💡 Key Insights

- Customers using **Electronic Check** experienced the highest churn rate, which was associated with the large proportion of customers on **Month-to-Month** contracts.
- Customers subscribed to **Fiber Optic** internet services exhibited the highest churn rate, while customers without **Online Security** were significantly more likely to leave the company.
- **New customers (0–12 months)** recorded the highest churn rate, whereas long-term customers demonstrated substantially stronger retention. Longer contract durations were associated with increased customer loyalty.
- **Gender** showed minimal influence on customer churn, indicating that service-related factors are much more important than demographic characteristics.
- Customers without **Tech Support** experienced significantly higher churn and were predominantly enrolled in **Month-to-Month** contracts, suggesting that both service quality and contract commitment are associated with customer retention.
- Customers paying **higher monthly charges** were more likely to churn. Supporting analysis revealed that these customers were primarily subscribed to **Fiber Optic** internet plans, indicating that premium-priced services require stronger value propositions to improve customer retention.

---

# 📊 German Credit Risk Analysis

## 🎯 Objective

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on the **German Credit Risk** dataset to identify the key factors influencing customer credit risk. The analysis aims to uncover patterns in customer demographics, financial behavior, loan characteristics, and account information to generate actionable business insights that can help financial institutions make informed lending decisions and minimize the risk of loan defaults.

---

## 📊 Analysis Performed

- Performed data understanding and dataset inspection.
- Removed the unnecessary **Unnamed: 0** index column.
- Checked for missing values, duplicate records, and data types.
- Generated summary statistics for numerical features.
- Created an **Age Group** feature using binning for better demographic analysis.
- Conducted **Univariate Analysis** to understand the distribution of customer demographics, loan characteristics, account information, and credit risk.
- Conducted **Bivariate Analysis** to examine relationships between credit risk and key variables, including:
  - Age Group vs Credit Risk
  - Checking Account vs Credit Risk
  - Gender vs Credit Risk
  - Loan Purpose vs Credit Risk
  - Credit Amount Group vs Credit Risk
- Performed supporting analyses to validate business hypotheses using:
  - Age Group vs Credit Amount & Loan Duration
  - Gender vs Credit Amount
  - Loan Purpose vs Credit Amount
  - Credit Amount Group vs Loan Duration
- Performed **Multivariate Analysis** using a correlation heatmap to identify relationships among numerical variables.
- Derived business-focused insights and recommendations based on the findings.

---

## 💡 Key Insights

- Customers aged **18–30** exhibited the highest proportion of **bad credit risk**, although this pattern could not be explained solely by larger loan amounts or longer repayment durations.
- Customers with **moderate checking account balances** recorded the highest bad credit risk, while customers with **rich checking account balances** showed the lowest.
- **Female customers** demonstrated a higher percentage of bad credit risk than male customers; however, this difference was not explained by larger loan amounts, suggesting that additional financial factors contribute to the observed pattern.
- Loans taken for **Vacation/Others** had the **highest bad credit risk (41.7%)** and were also associated with the **highest average credit amount**, indicating that larger discretionary loans may carry greater repayment risk.
- Customers requesting loans above **8K** showed the **highest bad credit risk (54.3%)**. Supporting analysis revealed that these loans were also associated with **longer repayment durations**, increasing the financial burden on borrowers.
- The correlation analysis showed a **strong positive relationship between Credit Amount and Loan Duration (0.62)**, while **Loan Duration (0.21)** and **Credit Amount (0.15)** exhibited positive relationships with credit risk. Demographic variables such as **Age** and **Job** showed comparatively weak relationships with credit risk.
---
# 🏦 Bank Customer Churn Analysis

## 🎯 Objective

The objective of this project is to perform **Exploratory Data Analysis (EDA)** on the **Bank Customer Churn** dataset to identify the key factors influencing customer attrition. The analysis aims to uncover patterns in customer behavior, evaluate relationships between different features and customer churn, and generate actionable business insights that can help the bank improve customer retention and reduce churn.

---

## 📊 Analysis Performed

- Performed data understanding and dataset inspection.
- Checked for missing values and duplicate records.
- Generated summary statistics for numerical features.
- Conducted **Univariate Analysis** to understand the distribution of customer demographics and banking attributes.
- Conducted **Bivariate Analysis** to examine relationships between customer churn and important features such as:
  - Geography vs Customer Churn
  - Geography vs Complaint Rate
  - Active Member vs Customer Churn
  - Active Member vs Complaint Rate
  - Age Group vs Customer Churn
  - Number of Products vs Customer Churn
- Performed **Multivariate Analysis** using a correlation heatmap to identify relationships among numerical variables.
- Derived business-focused insights and recommendations based on the findings.

---

## 💡 Key Insights

- Germany recorded the highest customer churn rate among all geographical regions.
- Germany also had the highest complaint rate, indicating potential service quality issues.
- Inactive customers were significantly more likely to churn than active customers.
- Customers who were inactive also reported more complaints.
- Customers aged **51–60 years** showed the highest likelihood of leaving the bank.
- Customers with **two banking products** demonstrated the strongest customer retention, while churn increased considerably for customers with three or more products.
- The correlation analysis showed that **Age**, **Complaint**, and **Active Membership** were the most influential factors associated with customer churn, whereas credit score, salary, tenure, and card type had relatively weak relationships.
---
# 🏨 Hotel Booking Cancellation Analysis
---
## 📌 Objective

Analyze hotel booking data to identify the key factors influencing booking cancellations and customer behavior. The goal is to uncover actionable business insights that help improve demand forecasting, optimize booking strategies, enhance customer retention, and reduce cancellation rates.

---

## 🔍 Analysis Performed

- Data Cleaning & Missing Value Handling
- Removed the `company` column (94% missing values)
- Replaced missing values in the `country` column with **"Unknown"**
- Duplicate Value Check
- Hotel Type Analysis (City Hotel vs Resort Hotel)
- Lead Time vs Booking Cancellation Analysis
- Monthly Cancellation Rate Analysis
- Special Requests vs Booking Cancellation
- Top Booking Countries Analysis
- Market Segment vs Booking Cancellation
- Repeated Guest vs Booking Cancellation
- Business Insight Generation

---

## 📈 Key Insights

- **Longer lead times** were associated with significantly higher booking cancellation rates.
- **City Hotels** consistently recorded higher cancellation rates than Resort Hotels throughout the year.
- Guests with **more special requests** were much less likely to cancel their bookings, indicating stronger booking commitment.
- A large proportion of bookings originated from a **small number of countries**, making them key customer markets for hotels.
- **Group bookings** showed the highest cancellation rates, whereas **Direct** and **Corporate** bookings were the most reliable.
- **Repeated guests** had substantially lower cancellation rates than first-time guests, highlighting the importance of customer loyalty in reducing cancellations.
- Hotels can improve operational planning by focusing on **high-risk booking segments**, encouraging **direct bookings**, and strengthening **customer retention strategies**.
# 👨‍💼 HR Analytics – Job Change Prediction Analysis

### 📌 Objective

Analyze employee demographics, education, work experience, company characteristics, and training information to identify the factors associated with job change behavior after completing training and generate actionable HR insights.

### 🔍 Analysis Performed

- Data Cleaning & Missing Value Handling
- Feature Engineering
- Target Variable Mapping (Stay vs Leave)
- Education Level Analysis
- Major Discipline Analysis
- Work Experience Analysis
- Relevant Experience Analysis
- Company Type Analysis
- Company Size Analysis
- City Development Index Analysis
- Training Hours Analysis
- Correlation Analysis
- Business Insights & Recommendations

### 📈 Key Insights

- 🎓 Candidates with **Graduate** degrees exhibited the highest job-change rate compared to other education levels.
- 💻 **STEM** candidates accounted for the largest proportion of employees likely to change jobs after training.
- 💼 Employees with **less work experience** showed a higher tendency to seek new job opportunities.
- ✅ Candidates **without relevant work experience** had a significantly higher leave rate than those with relevant industry experience.
- 🏢 Employees working in **small organizations (10–49 employees)** were more likely to change jobs than those employed in larger organizations.
- 🚀 Candidates from **Early Stage Startups** demonstrated a relatively higher likelihood of changing jobs.
- 🌍 Employees from **less-developed cities** showed higher job mobility, while candidates from highly developed cities had better retention rates.
- 📚 **Training hours** showed only a weak relationship with job-change behavior, indicating that employee retention depends more on experience and organizational factors than training duration alone.
- 📊 Correlation analysis revealed that **City Development Index** and **Experience** were negatively associated with employee job changes, while **Training Hours** showed almost no correlation with the target variable.

---
# 🛒 Superstore Sales Analysis

### 📌 Objective

Analyze retail sales data to identify sales trends, profitable regions, customer purchasing behavior, product performance, and business opportunities.

### 🔍 Analysis Performed

- Data Cleaning
- Datetime Feature Engineering
- Region-wise Sales Analysis
- Category & Sub-Category Analysis
- Customer Segment Analysis
- City-wise Sales Analysis
- Shipping Mode Analysis
- Customer Sales Analysis
- Product Demand Analysis
- Sales Trend Analysis
- Profit Analysis
- Business Insights

### 📈 Key Insights

- 🌎 West region generated the highest sales and accounted for the highest proportion of total orders.
- 💰 West was the strongest-performing region, while South showed the lowest sales and customer activity.
- 👥 Consumer customers generated the highest revenue among all customer segments.
- 💻 Technology products consistently performed well across customer segments.
- 🏙️ New York City generated the highest total sales, followed by Los Angeles.
- 🚚 Nearly **60%** of all orders were shipped using **Standard Class**, making it the preferred shipping method.
- 🤝 A small group of customers contributed a significant share of total sales, highlighting the importance of customer retention.
- 📦 Binders, Paper, Phones, and Storage were among the highest-demand sub-categories, particularly in the West region.
- 📈 Sales showed steady growth from **2014 to 2017**, with 2018 requiring validation due to partial-year data.

---

# 🎬 Netflix Dataset Analysis

### 📌 Objective

Analyze Netflix's content library to discover trends in Movies, TV Shows, genres, countries, actors, directors, and release patterns.

### 🔍 Analysis Performed

- Data Cleaning
- Missing Value Handling
- Datetime Feature Engineering
- Movies vs TV Shows Analysis
- Country-wise Analysis
- Director Analysis
- Cast Analysis
- Rating Distribution
- Year-wise Content Growth
- Monthly Content Trends
- Genre Analysis
- Business Insights

### 📈 Key Insights

- 🎬 Movies dominate Netflix's content library.
- 🇺🇸 United States contributes the highest number of Netflix titles.
- 🇮🇳 India is the second-largest content producer.
- 🎥 Rajiv Chilaka has the highest number of directed titles.
- 🎭 Anupam Kher appears in the highest number of Netflix titles.
- 📅 Netflix experienced rapid content growth between **2016–2020**.
- 📺 TV Shows have grown significantly in recent years.

---

# 🚢 Titanic Dataset Analysis

### 📌 Objective

Analyze passenger demographics and identify the factors that influenced survival.

### 🔍 Analysis Performed

- Missing Value Handling
- Passenger Class Analysis
- Gender Analysis
- Age Analysis
- Embarkation Analysis
- Survival Rate Analysis
- Correlation Analysis

### 📈 Key Insights

- 👩 Female passengers had a much higher survival rate than males.
- 🛳️ First-Class passengers survived more frequently than Third-Class passengers.
- 🚢 Passengers boarding from **Cherbourg (C)** had the highest survival rate.
- 👶 Children had a relatively higher chance of survival.
- 💰 Higher ticket fares were associated with higher survival rates.

---

# 📱 Google Play Store Dataset Analysis

### 📌 Objective

Understand application trends, ratings, installs, pricing, and user engagement in the Google Play Store.

### 🔍 Analysis Performed

- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Data Type Conversion
- Category Analysis
- Rating Distribution
- Install Analysis
- Reviews Analysis
- Free vs Paid Apps
- Correlation Analysis

### 📈 Key Insights

- 📱 Most applications on Google Play Store are free.
- 🎮 Family and Game categories contain the largest number of apps.
- ⭐ Most applications have ratings between **4.0–4.5**.
- 📈 Apps with more installs generally receive more reviews.
- 💰 Paid apps represent only a small portion of the Play Store.

---

# ✈️ Flight Price Dataset Analysis

### 📌 Objective

Analyze airline ticket prices and identify factors affecting airfare.

### 🔍 Analysis Performed

- Airline Analysis
- Source & Destination Analysis
- Flight Duration Analysis
- Stops Analysis
- Journey Date Analysis
- Price Distribution
- Correlation Analysis

### 📈 Key Insights

- ✈️ Flight duration has a strong impact on ticket prices.
- 🛫 Flights with more stops generally cost less than direct flights.
- 📅 Ticket prices vary across different months and travel seasons.
- 🏷️ Airline choice significantly influences airfare.

---

# 🍷 Wine Quality Dataset Analysis

### 📌 Objective

Analyze the relationship between chemical properties and wine quality.

### 🔍 Analysis Performed

- Data Cleaning
- Feature Distribution
- Correlation Analysis
- Quality Distribution
- Alcohol Analysis
- Acidity Analysis
- Density Analysis

### 📈 Key Insights

- 🍷 Higher alcohol content is positively associated with better wine quality.
- 🧪 Certain acidity measures influence wine quality.
- 📊 Most wines fall within the medium-quality range.
- 🔥 Alcohol is one of the strongest predictors of wine quality.

---

# 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 📈 Seaborn
- 📒 Jupyter Notebook

---

# 📊 Visualizations Used

- 📊 Bar Charts
- 📈 Line Charts
- 📉 Histograms
- 📦 Box Plots
- 🥧 Pie Charts
- 🎯 Scatter Plots
- 🔥 Correlation Heatmaps
- 📌 Count Plots

---

# 🎯 Skills Demonstrated

- ✅ Data Cleaning
- ✅ Data Preprocessing
- ✅ Handling Missing Values
- ✅ Feature Engineering
- ✅ Exploratory Data Analysis
- ✅ Statistical Analysis
- ✅ Data Visualization
- ✅ Business Insight Generation
- ✅ Trend Analysis
- ✅ Customer Segmentation
- ✅ Profitability Analysis
- ✅ Correlation Analysis

---

# 💻 Getting Started

Clone the repository

```bash
git clone https://github.com/Omkar-narsale/Exploratory-Data-Analysis.git
```

Navigate into the project

```bash
cd Exploratory-Data-Analysis
```

Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# ⭐ Future Additions

I continuously update this repository with new EDA projects, including:

- 🏥 Healthcare Analysis
- 🏦 Banking Customer Analysis
- 🏠 House Price Analysis
- 🛍️ Amazon Sales Analysis

---

# 🤝 Contributions

Contributions, suggestions, and improvements are always welcome.

If you found this repository useful, consider giving it a ⭐ to support the project.

---

# 👨‍💻 Author

## **Omkar Narsale**

🐙 GitHub: https://github.com/Omkar-narsale

💼 LinkedIn: https://www.linkedin.com/in/omkar-narsale45
