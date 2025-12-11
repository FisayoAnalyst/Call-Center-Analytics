  # Call Center Performance Report

  ## Client Background

**ConnectCall Solutions** is a fictional customer engagement company created as part of a data analytics demonstration project. The organization operates within the Business Process Outsourcing (BPO) industry, providing outsourced customer service and technical support solutions for a wide range of client companies. The company manages inbound and outbound interactions aimed at improving customer satisfaction, resolution efficiency, and overall service experience.

The dataset used for this analysis was sourced from the **Forage Virtual Experience Program**, designed to simulate real-world business data. It contains **5,000 call records** collected over a three-month period **(January to March)**, including fields such as call status (answered or abandoned), resolution status, talk duration, and customer satisfaction rating.

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate **ConnectCall Solutions'** performannce, while identifying possible **operational bottlenecks** that affect service delivery.
This detailed review provides actionable intelligence that internal cross-functional teams will utilize to streamline daily operations, improve overall customer experience, and enhance service delivery. The key inisghts and recommendations focus on the following areas:

- **Operational Efficiency** – assessed using metrics such as **Total Calls**, **Answer Rate**, **Abandonment Rate**, **Average Speed of Answer**, and **Resolution Rate**.

- **Customer Satisfaction** – evaluated through **Average Satisfaction Rating**, **Resolution Status**, and **Call Abandonment Patterns**, revealing how service quality impacts customer experience.

- **Agent Performance** – measured using **Total Calls Handled**, **Resolution Rate per Agent**, **Average Talk Duration**, and **Customer Rating** providing insights into performance consistency and training needs.

  ## Executive Summary

The dataset, sourced from TheForage Virtual Experience Program, includes call records that capture customer support activity between January and March. Key features in the dataset:

- Call ID: Unique identifier per call.

- Agent: Name of the service representative.

- Date/Time: Timestamp of call initiation.

- Topic: Call reason (e.g., Technical Support, Payment).

- Answered/Resolved: Status of call handling.

- Speed of Answer: Time taken to respond to calls.

- Average Talk Duration: Duration of conversations.

- Satisfaction Rating: Customer feedback score (1-5).

### Tools & Technologies Used

- Power BI: Data modeling, dashboard design, and DAX calculations.

- DAX: Custom measures and performance calculations.

- Microsoft Excel: Preliminary data exploration.

### Data Cleaning & Transformation

To ensure data accuracy and consistency, the following steps were applied:

- Filled missing values with zero where appropriate.

- Removed duplicate entries and standardized data types.

- Created a Star Schema model with Fact and Dimension tables.

- Engineered new features including 'Weekday Type' and extracted call hours.

- Developed DAX measures for average speed of answer, resolution rate, agent KPIs, and satisfaction analysis.

### Dashboard Overview

The Power BI dashboard provides a holistic view of call center operations:

- KPI Summary: Total calls, resolution rates, and satisfaction score.

- Call Volume Trends: Daily and monthly breakdowns.

- Agent Performance: Comparison of call handling and resolution efficiency.

- Customer Feedback: Satisfaction ratings across topics and times.

- Operational Metrics: Abandonment rates and response times.


<img width="1328" height="735" alt="Dashboard_Overview" src="https://github.com/user-attachments/assets/d2fc936b-8a30-4c73-8928-2c521e76302b" />

### Key Insights

- Answered Calls: 81.08% with a resolution rate of 89.94%.

- Peak Hours: 9 AM and 12 PM; highest abandonment at 5 PM (36.36%).

- Top Topics: Technical Support, Streaming, and Payment Issues.

- Top Agents: Jim, Greg, and Dan for resolution rates; Becky had the fastest response.

- Customer Satisfaction: Peaks at 10 AM (4.00), lowest during 1-2 PM.

### Recommendations

1. Reduce Abandonment: Introduce call-back options and optimize shift scheduling.

2. Improve Agent Efficiency: Provide tailored training and implement performance incentives.

3. Enhance Customer Experience: Deploy post-call surveys and self-service tools.

4. Optimize Staffing: Increase availability during peak times using predictive scheduling.

5. Upgrade Technical Support: Provide troubleshooting tools and better call scripts.

### Conclusion

The analysis reveals strong resolution rates and agent performance but highlights areas needing attention, particularly high call abandonment and low satisfaction during peak hours. Implementing strategic staffing, targeted training, and AI-driven solutions can significantly enhance operational efficiency and customer experience.

### Dashboard Access

To interact with the report:

- Open the `.pbix` file using [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).
- Explore the visuals, filter data, and review insights across different report pages. (https://github.com/FisayoAnalyst/Call-Center-Analytics/blob/main/Call_Center_Analytics_Report.pdf)

**Download** the Power BI file [`CallCenterDashboard.pbix`](https://github.com/FisayoAnalyst/Call-Center-Analytics/releases/download/v1.0/Call.Center.Analytics.Dashboard.pbix)

*Note:* Power BI Desktop must be installed on your device to open `.pbix` files. You can download it [here](https://powerbi.microsoft.com/en-us/desktop/)








