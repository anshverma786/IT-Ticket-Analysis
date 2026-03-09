# IT-Ticket-Analysis
IT Ticket Analysis – Analyze IT support tickets using Excel with data cleaning, trend analysis, pivot tables, and interactive dashboards to identify recurring issues, high-priority tickets, and actionable insights for improving support efficiency.

### 📂 Project Database
You can view the full IT Ticket Analysis project and dashboard here:

[Access IT Ticket Analysis Database (Excel)](https://docs.google.com/spreadsheets/d/1TtkAyJIjM0c10jiJVpOnRowAMGZKe9nA/edit?gid=2040522332#gid=2040522332)

# 📋 Overview
This project involves a comprehensive analysis of an IT support ticket management system using a dataset covering 97,498 tickets handled by 50 agents between 2016 and 2020. The primary objective was to evaluate IT agent performance, assess ticket resolution efficiency, and understand customer satisfaction levels to drive data-informed improvements in staffing, training, and operational processes.

# 🚀 Key Objectives

- **Performance Evaluation:** Identify high and low-performing IT agents.
- **Efficiency Analysis:** Assess the effectiveness of the ticket resolution process.
- **Actionable Insights:** Pinpoint bottlenecks and areas for improvement to enhance service quality.
- **Strategic Decision Making:** Provide recommendations for staffing, hiring, and training based on data

# 📊 Methodology

- **The analysis was performed using Excel with the following steps:**
- **Data Cleaning:** Removed duplicates, handled missing values, corrected typos (e.g., "Mayor" to "Major"), and standardized categories.
- **Data Preparation:Ticket Sheet:** Extracted date components (Day, Month, Year) and split Severity/Priority fields.
- **Agent Sheet:** Calculated agent age, defined seniority bands (Junior ≤35, Mid-Level 36–45, Senior >45), and aggregated performance metrics.
- **Analysis Tools:** Utilized Pivot Tables for trend analysis, correlation calculations for severity vs. resolution time, and conditional formatting to flag agents for training.

# 🔑 Key Insights & Findings

- **Workload Distribution:** System and Login Access tickets constitute ~70% of the total workload.
- **Resolution Efficiency:** 79% of tickets are resolved within 0–8 days. However, hardware requests represent a bottleneck, taking significantly longer to resolve (~7.6 days).
- **Priority Misalignment:** A critical gap exists where 30% of tickets remain unassigned, and high-severity (Major/Urgent) tickets are not consistently mapped to high-priority levels, causing inefficiencies.
- **Customer Satisfaction:** Overall satisfaction is stable (~4.10), with slight dips observed in February–March and among the 36–45 age group.Peak Periods: Higher ticket volumes are consistently observed from August to October.

# 💡 Strategic Recommendations

- **Enhance Prioritization:** Implement strict SLA rules in the ticketing software to automatically map Major/Urgent tickets to High priority to reduce delays.
- **Targeted Training:** Focus training on agents identified with high resolution times and low satisfaction scores to improve overall performance.
- **Optimize Processes:** Address hardware bottlenecks by reviewing procurement or repair workflows and document common system issues in a knowledge base.
- **Resource Allocation:** Adjust staffing levels to match the increased workload during the peak months of August–October.

# 🛠 Tech Stack

- **Tool:** Microsoft Excel (Pivot Tables, Advanced Formulas, Conditional Formatting, Data Visualization).
