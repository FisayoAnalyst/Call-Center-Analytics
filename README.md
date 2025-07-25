# Call Center Analytics

## Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Data Description](#data-description)
- [Tools & Technologies Used](#tools--technologies-used)
- [Data Cleaning & Transformation](#data-cleaning--transformation)
- [Dashboard Overview](#dashboard-overview)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Dashboard Access](#dashboard-access)


### Project Overview

This project analyzes operational data from a call center to uncover performance trends, agent efficiency, customer satisfaction patterns, and actionable areas for improvement. The analysis was conducted using Power BI, leveraging key performance indicators to drive strategic recommendations.

### Objectives

The primary objective of this project is to:

- Visualize key performance metrics through a comprehensive Power BI dashboard.

- Track call volume trends and response rates.

- Evaluate agent performance and efficiency.

- Analyze customer satisfaction patterns.

- Identify peak call periods and potential operational bottlenecks.

- Provide data-driven recommendations to improve staffing, training, and call resolution processes.

### Data Description

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
- Explore the visuals, filter data, and review insights across different report pages.

**Download** the Power BI report: [`CallCenterDashboard.pbix`](./CallCenterDashboard.pbix)

*Note:* Power BI Desktop must be installed on your device to open `.pbix` files. You can download it [here](https://powerbi.microsoft.com/en-us/desktop/)








