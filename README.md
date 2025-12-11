  # Call Center Performance Analysis

  ## Executive Summary

ConnectCall Solutions is a simulated Business Process Outsourcing (BPO) call center created for this data analytics demonstration project. The company manages inbound and outbound customer interactions, aiming to optimize customer satisfaction, operational efficiency, and service quality.

This analysis leverages a dataset of 5,000 call records collected over a three-month period (January–March) from the Forage Virtual Experience Program. The dataset includes call outcomes, resolution status, talk duration, and customer satisfaction ratings.

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate **ConnectCall Solutions'** performannce, while identifying possible **operational bottlenecks** that affect service delivery.
This detailed review provides actionable intelligence that internal cross-functional teams will utilize to streamline daily operations, improve overall customer experience, and enhance service delivery. The key inisghts and recommendations focus on the following areas:

- **Operational Efficiency** – assessed using metrics such as **Total Calls**, **Answer Rate**, **Abandonment Rate**, **Average Speed of Answer**, and **Resolution Rate**.
- **Customer Satisfaction** – evaluated through **Average Satisfaction Rating**, **Resolution Status**, and **Call Abandonment Patterns**, revealing how service quality impacts customer experience.
- **Agent Performance** – measured using **Total Calls Handled**, **Resolution Rate per Agent**, **Average Talk Duration**, and **Customer Rating** providing insights into performance consistency and training needs.

**Key findings:**

- **High overall service performance:** 81% of calls answered, 89.94% resolution rate, and average satisfaction of 3.40/5.
- **Topic-level bottlenecks:** Streaming and Payment issues had lower resolution rates and satisfaction scores, indicating complex or recurring customer challenges.
- **Time-of-day inefficiencies:** Early afternoon (1–2 PM) showed dips in resolution and satisfaction, suggesting staffing gaps or agent fatigue.
- **Agent performance variations:** Certain agents consistently outperformed peers, highlighting opportunities for mentorship and targeted coaching.
- **Technical Support insights:** Despite a 21% abandonment rate, resolution for answered calls was 91%, showing strong agent capability.

**Recommendations:**
- Targeted training for high-friction topics
- Optimize staffing during low-performance hours
- Investigate recurring Streaming and Payment issues
- Leverage high-performing agents as mentors
- Improve Technical Support accessibility

## Dataset Structure

> The original dataset of 5,000 call records was split into **one fact table** and **six dimension tables** following star schema best practices. The fact table stores transactional call data, while the dimension tables provide descriptive attributes for analysis.

### Fact Table – `FactCalls`
| Column Name        | Data Type | Description |
|-------------------|-----------|-------------|
| CallID             | INT       | Unique identifier for each call |
| AgentID            | INT       | Foreign key referencing `DimAgent` |
| TopicID            | INT       | Foreign key referencing `DimTopic` |
| AnsweredID         | INT       | Foreign key referencing `DimAnswered` |
| ResolvedID         | INT       | Foreign key referencing `DimResolved` |
| DateID             | INT       | Foreign key referencing `DimDate` |
| TimeID             | INT       | Foreign key referencing `DimTime` |
| TalkDuration       | INT       | Duration of call in seconds |
| SatisfactionRating | FLOAT     | Customer rating (1–5) |

### Dimension Tables
| Table Name       | Description |
|-----------------|-------------|
| **DimAgent**     | Agent details (AgentID, AgentName) |
| **DimTopic**     | Call categories/topics (TopicID, TopicName) |
| **DimAnswered**  | Call answered status (AnsweredID, Status) |
| **DimResolved**  | Resolution status (ResolvedID, Status) |
| **DimDate**      | Date attributes (DateID, Date, DayOfWeek, Month, Year) |
| **DimTime**      | Time attributes (TimeID, Hour, Minute, Period) |

---

## ERD (Entity-Relationship Diagram)

> The diagram below illustrates the structure of the fact and dimension tables and their relationships:

## Insights Deep-Dive

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








