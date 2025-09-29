# Bank Loan Report using SQL & PowerBI

**Project Overview:**

**Objective:**

To build a dynamic, interactive dashboard that consolidates financial data from various sources, providing actionable insights for decision-making.
Tools & Technologies:

**SQL:** For data extraction and querying from databases.

**Excel:** For initial data analysis and manipulation.

**Power BI:**  For creating interactive and visually appealing dashboards.

**Dataset Link:** https://www.kaggle.com/datasets/nezukokamaado/auto-loan-dataset

**YT Reference:** https://youtu.be/EBU9wyt-xgo?si=ryJuvOjTkAFWRFhB

Thank You #swapnjeet555 & his channel #DataTutorials for sharing your knowledge…


**PROBLEM STATEMENT**

**DASHBOARD 1: SUMMARY**

"In order to monitor and assess our bank's lending activities and performance, we need to create a comprehensive Bank Loan Report. This report aims to provide insights into key loan-related metrics and their changes over time. The report will help us make data-driven decisions, track our loan portfolio's health, and identify trends that can inform our lending strategies.
 
![Image Alt](https://github.com/SanjayRahul1264/Bank_Loan_Report_using_SQL_and_PowerBI/blob/452cfa26dad99cbb6b366a1fcd906be2aeab2d02/Dashboard%20Snapshots/Summary.png)



**Key Performance Indicators (KPIs) Requirements:**

1.	Total Loan Applications: We need to calculate the total number of loan applications received during a specified period. Additionally, it is essential to monitor the Month-to-Date (MTD) Loan Applications and track changes Month-over-Month (MoM).

2.	Total Funded Amount: Understanding the total amount of funds disbursed as loans is crucial. We also want to keep an eye on the MTD Total Funded Amount and analyse the Month-over-Month (MoM) changes in this metric.

3.	Total Amount Received: Tracking the total amount received from borrowers is essential for assessing the bank's cash flow and loan repayment. We should analyse the Month-to-Date (MTD) Total Amount Received and observe the Month-over-Month (MoM) changes.

4.	Average Interest Rate: Calculating the average interest rate across all loans, MTD, and monitoring the Month-over-Month (MoM) variations in interest rates will provide insights into our lending portfolio's overall cost.

5.	Average Debt-to-Income Ratio (DTI): Evaluating the average DTI for our borrowers helps us gauge their financial health. We need to compute the average DTI for all loans, MTD, and track Month-over-Month (MoM) fluctuations.


**Good Loan v Bad Loan KPI’s**

In order to evaluate the performance of our lending activities and assess the quality of our loan portfolio, we need to create a comprehensive report that distinguishes between 'Good Loans' and 'Bad Loans' based on specific loan status criteria


**Good Loan KPIs:**

1.	Good Loan Application Percentage: We need to calculate the percentage of loan applications classified as 'Good Loans.' This category includes loans with a loan status of 'Fully Paid' and 'Current.'

2.	Good Loan Applications: Identifying the total number of loan applications falling under the 'Good Loan' category, which consists of loans with a loan status of 'Fully Paid' and 'Current.'

3.	Good Loan Funded Amount: Determining the total amount of funds disbursed as 'Good Loans.' This includes the principal amounts of loans with a loan status of 'Fully Paid' and 'Current.'

4.	Good Loan Total Received Amount: Tracking the total amount received from borrowers for 'Good Loans,' which encompasses all payments made on loans with a loan status of 'Fully Paid' and 'Current.'


**Bad Loan KPIs:**

1.	Bad Loan Application Percentage: Calculating the percentage of loan applications categorized as 'Bad Loans.' This category specifically includes loans with a loan status of 'Charged Off.'

2.	Bad Loan Applications: Identifying the total number of loan applications categorized as 'Bad Loans,' which consists of loans with a loan status of 'Charged Off.'

3.	Bad Loan Funded Amount: Determining the total amount of funds disbursed as 'Bad Loans.' This comprises the principal amounts of loans with a loan status of 'Charged Off.'

4.	Bad Loan Total Received Amount: Tracking the total amount received from borrowers for 'Bad Loans,' which includes all payments made on loans with a loan status of 'Charged Off.'


**Loan Status Grid View**

To gain a comprehensive overview of our lending operations and monitor the performance of loans, we aim to create a grid view report categorized by 'Loan Status.' This report will serve as a valuable tool for analysing and understanding the key indicators associated with different loan statuses. By providing insights into metrics such as 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'Month-to-Date (MTD) Funded Amount,' 'MTD Amount Received,' 'Average Interest Rate,' and 'Average Debt-to-Income Ratio (DTI),' this grid view will empower us to make data-driven decisions and assess the health of our loan portfolio.


**DASHBOARD 2: OVERVIEW**

In our Bank Loan Report project, we aim to visually represent critical loan-related metrics and trends using a variety of chart types. These charts will provide a clear and insightful view of our lending operations, facilitating data-driven decision-making and enabling us to gain valuable insights into various loan parameters. Below are the specific chart requirements:

![Image Alt](https://github.com/SanjayRahul1264/Bank_Loan_Report_using_SQL_and_PowerBI/blob/452cfa26dad99cbb6b366a1fcd906be2aeab2d02/Dashboard%20Snapshots/Overview.png)


**1. Monthly Trends by Issue Date (Line Chart):**

**Chart Type:** Line Chart

**Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

**X-Axis:** Month (based on 'Issue Date')

**Y-Axis:** Metrics' Values

**Objective**: This line chart will showcase how 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' vary over time, allowing us to 
identify seasonality and long-term trends in lending activities.


**2. Regional Analysis by State (Tree Map):**

**Chart Type:** Filled Map

**Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

**Geographic Regions:** States

**Objective:** This filled map will visually represent lending metrics categorized by state, enabling us to identify regions with significant lending activity and 
assess regional disparities.


**3. Loan Term Analysis (Donut Chart):**

**Chart Type:** Donut Chart

**Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

**Segments:** Loan Terms (e.g., 36 months, 60 months)

**Objective:** This donut chart will depict loan statistics based on different loan terms, allowing us to understand the distribution of loans across various term lengths.


**4. Employee Length Analysis (Bar Chart):**

**Chart Type:** Bar Chart

**Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

**X-Axis:** Employee Length Categories (e.g., 1 year, 5 years, 10+ years)

**Y-Axis:** Metrics' Values

**Objective:** This bar chart will illustrate how lending metrics are distributed among borrowers with different employment lengths, helping us assess the impact of employment history on loan applications.


**5. Loan Purpose Breakdown (Bar Chart):**

**Chart Type:** Bar Chart

**Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

**X-Axis:** Loan Purpose Categories (e.g., debt consolidation, credit card refinancing)

**Y-Axis:** Metrics' Values

**Objective:** This bar chart will provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in the understanding of the primary reasons borrowers seek financing.


**6. Home Ownership Analysis (Tree Map):**

**Chart Type:** Tree Map

**Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'

**Hierarchy:** Home Ownership Categories (e.g., own, rent, mortgage)

**Objective:** This tree map will display loan metrics categorized by different home ownership statuses, allowing for a hierarchical view of how home ownership 
impacts loan applications and disbursements.

These diverse chart types will enhance our ability to visualize and communicate loan-related insights effectively, supporting data-driven decisions and strategic planning within our lending operations."


**DASHBOARD 3: DETAILS**

In our Bank Loan Report project, we recognize the need for a comprehensive 'Details Dashboard' that provides a consolidated view of all the essential information within our loan data. This Details Dashboard aims to offer a holistic snapshot of key loan-related metrics and data points, enabling users to access critical information efficiently.


**Objective:**

The primary objective of the Details Dashboard is to provide a comprehensive and user-friendly interface for accessing vital loan data. It will serve as a one-stop solution for users seeking detailed insights into our loan portfolio, borrower profiles, and loan performance.

![Image Alt](https://github.com/SanjayRahul1264/Bank_Loan_Report_using_SQL_and_PowerBI/blob/452cfa26dad99cbb6b366a1fcd906be2aeab2d02/Dashboard%20Snapshots/Details.png)



**Conclusions/ Insights from this Dashboard Report:**


**1. Strong Growth and Momentum**

Positive Financial Trend: All key financial metrics show strong Month-over-Month (MoM) growth:

Total Fund Amount (Loans Disbursed) is up 13.0% MoM.

Total Amount Received (Collections) is up 21.6% MoM.

Total Loan Applications are up 6.91% MoM, showing increasing demand.

Loan Volume Growth: The Total Fund Amount by Month chart shows continuous, aggressive growth, peaking at $48M in December (from a low of $25M in February), indicating a successful expansion strategy.


**2. Significant Credit Risk**

**Bad Loan Rate:** The Bad Loan Issued rate is 13.8% (5.3K applications, $65.5M funded), which is a high percentage for the portfolio. This indicates a substantial portion of loans are likely to default.

**Charged Off Status:** Loans currently Charged Off (defaults) account for a Total Loan Amount of $6.55 Billion and a large application count of 5,333, matching the volume of current "Bad Loans Issued." This confirms the high risk shown in the current bad loan rate is materializing into actual losses.


**3. Portfolio Distribution and Concentration**

**Dominant Terms: **60-month loans (62.66%) account for the vast majority of fund amount, meaning the bank has high, long-term exposure.

**Purpose Concentration:** Debt Consolidation ($0.23bn) is the overwhelmingly largest loan purpose, making the portfolio highly susceptible to changes in borrower credit and economic conditions.

**Home Ownership Exposure:** Loans for borrowers with MORTGAGE ($219.3M) and RENT ($185.8M) status are the two biggest segments, with a smaller gap between them than other categories.

**Employee Tenure:** Borrowers with 10+ years of employment are the source of the largest fund amount ($116M), suggesting reliance on an older, more established, but potentially risk-averse, segment.


**Actionable Outcomes**

**Credit Risk Mitigation:** Immediately review the underwriting criteria for loans that have a 13.8% Bad Loan rate. Analyze the characteristics (e.g., DTI, Interest Rate, Grade) of the Charged Off loans to identify and tighten the highest-risk segments, especially within Debt Consolidation.

**Optimize Long-Term Exposure:** Given the concentration in 60-month terms, stress-test the portfolio for long-term rate changes and economic downturns. Consider strategies to increase the proportion of the lower-risk 36-month terms.

**Capitalize on Collections:** The Total Amount Received growth of 21.6% MoM is positive. Investigate the success factors behind this collections performance to ensure it can be sustained and applied to managing the Charged Off amount.
