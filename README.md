# Fintech-Transactions-and-Channel-Perfomance-Analysis-Report

##  Overview of the Project
This report presents a simplified overview of how customers use our digital services across different channels, age groups, and locations. It highlights our most active users, top-performing platforms, areas needing improvement, and business growth patterns. The goal is to uncover key insights about customer behavior, channel usage, failure rates, transaction types, and regional performance, which will help stakeholders improve service reliability, customer experience, and business efficiency.


##  Business Objectives

- Identify which transaction channels and types drive the most volume and revenue.
- Detect and explain high failure rates across demographics and transaction modes.
- Analyze age, gender, and location data to inform customer engagement strategies.
- Provide actionable recommendations to minimize transaction failures and enhance customer satisfaction.
- Visualize performance indicators for decision-makers using interactive dashboards.


##  Dataset Description

- **Total Records:** 7,000
- **Fields Included:**
  - Transaction_ID, Transaction_Type, Amount
  - Status (Successful, Failed, Pending)
  - Channel (Mobile App, Web, USSD, POS, Agent)
  - Customer_ID, Gender, Age
  - City/Location, Date of Transaction

- **Created Columns:**
  - Age Category (Youth, Young Adult, Mid Adult, Matured Adult, Old)
  - Month (for time-based analysis)


##  Key Metrics and KPIs Visualized

| Metric                       | Description                                 |
|-----------------------------|---------------------------------------------|
| Total Transactions           | Number of transactions processed            |
| Average Transaction Value    | Avg. amount per transaction (₦10.14K)       |
| Failed Transactions          | Transactions that were not successful       |
| Customer Age Distribution    | Segmentation by age category                |
| Channel Performance          | Volume and failure rate per channel         |
| Transaction Type Volume      | Transfer, Airtime, Deposit, etc.            |
| Location-based Transactions  | Top cities by transaction volume            |
| Monthly Transaction Trend    | Seasonality across the year                 |


## Tools and Skills Demonstrated

- **Power BI**: Data modeling, DAX calculations, visual storytelling
- **Power Query**: Data cleaning and transformation
- **Data Segmentation**: Age groups, gender, channels, locations
- **KPI Analysis**: Custom measures for transaction trends
- **Business Intelligence**: Turning raw data into strategic insights
- **Problem Solving**: Identifying and addressing performance issues


##  Insights Discovered

###  Monthly Trends
- Peaks in **March** and **June** (6.4M+ transactions).
- Dips in **May** and **December**, likely due to system strain or holidays.

###  Age Group
- Even distribution across all age categories.
- **Young Adults** had the **highest failure rate (22.88%)**.

###  Channel Performance
| Channel     | Volume     | Failure Count |
|-------------|------------|----------------|
| Mobile App  | 13.49M     | **160 (highest)** |
| Agent       | 14.98M     | 150             |
| Web         | 14.96M     | 142             |
| POS         | 13.63M     | 140             |
| USSD        | 13.95M     | 129             |

### Transaction Type
| Type           | Volume     | Avg. Value |
|----------------|------------|------------|
| Transfer       | 13M        | ₦10.5K     |
| Payment        | 12M        | ₦10.2K     |
| Airtime        | 12M        | ₦10.3K     |
| Deposit        | 12M        | ₦10.1K     |
| Withdrawal     | 11M        | ₦9.9K      |
| Loan Repayment | 11M        | ₦9.9K      |


###  Location Insights
- **Top Cities**: Kano (10M), Benin (9M), Kaduna (9M)
- **Lagos** and **PH**, despite size, show relatively **lower usage**.

###  Gender Distribution
- Failures almost equally split between **male and female** users.
- No significant bias in platform usability by gender.

##  Business Recommendations

1. **Improve Mobile App Stability**
   - Conduct stress tests and optimize backend services.
   - Introduce offline transaction buffering where possible.

2. **Educate Young Adult Users**
   - Use tooltips, in-app onboarding, and visual aids for better UX.
   - Simplify transaction steps for new users.

3. **Debug Airtime & Payment Services**
   - Review logs for failed transactions.
   - Improve retry mechanism and error resolution time.

4. **Target Lagos and Port Harcourt**
   - Boost awareness and trust through city-specific campaigns.
   - Leverage Kano’s high success rate to model new regions.

5. **Plan for High-Traffic Months**
   - Pre-scale infrastructure before **March** and **June**.
   - Launch promo offers during these high-performing windows.


### Limitations:
- **No customer feedback data** was included to validate reasons for failures.
- **No income or spending segmentation** available for deeper personalization.

### Conclusion:
Our digital channels are performing well, and users trust us with critical financial transactions. However, enhancing user experience, reducing failed transactions, and focusing on strategic regional expansion will help us scale and serve more Nigerians effectively.


