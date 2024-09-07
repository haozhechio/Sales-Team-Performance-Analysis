# TechCore Technologies Sales Managers Team Performance Insights - Project Overview (Excel, Tableau)

## Overview
The goal of this project is to investigate the performance of TechCore Technologies’ sales managers in order to surface recommendations that improve overall sales efficiency and deal outcomes.

TechCore Technologies is a simulated company created for the purpose of this project. All data used in this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/innocentmfa/crm-sales-opportunities) to demonstrate sales performance analysis techniques. TechCore Technologies sells computer hardware, serving over 80 B2B clients throughout the United States. In 2017, the company sought to optimise its sales performance by evaluating the effectiveness of its sales teams across various regions, led by different managers.

The main objectives of this analysis is **to improve overall sales revenue and number of deals**

## Dataset Structure - ER Diagram
The dataset consists of four tables, providing detailed information about the sales team, account information, products, and sales pipeline. The data was prepared with **Excel** and organised into relational tables, which allowed for in-depth analysis of team performance.

<img src="https://github.com/user-attachments/assets/c1890447-3409-4b5a-b690-9b7e39496381" alt="ERD" width="500"/>

## Insights Summary

### North Star Metrics
In order to evaluate manager performance, we focused on the following key metrics:
- **Total Revenue**: The revenue generated by each sales team across the year.
- **Total Closed Deals**: The number of deals, both won and lost, handled by each team.
- **Average Sales Conversion Rate**: The percentage of deals successfully converted into Won deals.
- **Average Sales Velocity**: The average time it takes for a deal to move from engagement to closing.
- **Average Deal Size**: The average revenue per Won deal.

### Total Revenue
- Melvin Marxen generated the highest revenue, $225M, with Dustin Brinkmann at the lowest, with only $109M, less than half of Melvin’s total.
- While Melvin Marxen led his team to the highest revenue, a closer look at the sales agent performance scatterplot chart reveals that more than half of the revenue came from just one standout performer. The rest of the agents on his team performed below average.
- Revenue trends indicate a cyclical dip every three months (April, July, and October), suggesting possible seasonal factors impacting performance.
- Melvin’s team maintained a high average sales price with only a 0.12% deviation from the suggested retail price, while Dustin Brinkmann had the largest deviation at -0.32%.

### Conversion Rate
- The conversion rate across all managers is fairly uniform, with only a ±2% variation between the highest and lowest performers. This consistency implies a higher probability that conversion success is driven by standardized company processes rather than individual manager tactics.

### Total Closed Deals vs. Average Deal Size
- Melvin Marxen’s team had the highest number of closed deals (1,418) and the highest average deal size ($138K). However, the standout performance was driven by one agent, who closed deals with an average value 250% higher than the overall sales agents’ average.
- Cara Losch and Dustin Brinkmann performed the worst in terms of closed deals and average deal size, with Dustin having the lowest deal size at $79K.
- Based on the sales agent performance scatterplot chart, teams led by Summer Sewald and Rocco Neubert, while not showing the highest performance, were marked by balanced agent performance and performing well across the board, with no single agent drastically outperforming the others. This suggests strong overall leadership and effective resource allocation.

### Average Sales Velocity
- The average sales velocity across all managers is fairly similar, with only a 2-day difference between the fastest and slowest performers. This minimal gap suggests that the company’s sales cycle is efficient across the board, though further improvements could still be made to speed up the process.

## Recommendations

### Leverage High-Performing Agents
- Darcel Schlecht from team Melvin Marxen should be closely analyzed to understand and replicate his strategies across the rest of the team. Implementing mentorship programs or standardizing successful sales tactics could help raise overall team performance

### Address Performance Imbalance
- Melvin Marxen’s team relies heavily on one standout performer. Investigate whether resources and attention are being disproportionately allocated to this agent, which might indicate a leadership imbalance. Alternatively, the team’s success may be largely driven by the individual efforts of this agent rather than Melvin’s leadership.

### Study Leadership in Balanced Teams
- **Summer Sewald and Rocco Neubert’s teams** show a more balanced performance across all agents, indicating good leadership strategies. Their methods could be studied and potentially applied to underperforming teams.

### Improve Pipeline Management for Underperforming Teams
- Cara Losch and Dustin Brinkmann need to focus on increasing their pipeline volume and value to ensure better future performance. Expanding lead generation efforts and improving client engagement strategies could help boost their overall success

## Dashboard
The dashboard used for this project can be found in Tableau Public [here](https://public.tableau.com/views/SalesTeamPerformanceManagementDashboard/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link). The dashboard visualizes metrics of revenue, sales performance and pipeline and allows users to filter the data by manager, month, product and accounts' sector.

![Dashboard](https://github.com/user-attachments/assets/b8e2209b-7641-487b-a6fb-da2eebda6527)
