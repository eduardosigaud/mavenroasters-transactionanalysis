# Maven Roasters Transaction Analysis

## Introduction
This project involves the analysis of transaction records for Maven Roasters, a fictitious coffee shop operating out of three NYC locations. The data includes detailed transaction information, providing a comprehensive basis for deriving insights into sales patterns, customer behavior, and operational efficiency across the different branches.

## Objectives

### Objective 1 - Prepare the Data for Analysis
- **Revenue Calculation**: Introduced a new column to compute Revenue using the formula `price * quantity`.
- **Date Components Extraction**: Implemented new columns to derive Month and Day of Week from the transaction date, enhancing temporal analysis capabilities.
- **Time Component Extraction**: Added a new column to extract the Hour from the transaction time, enabling hourly trend analysis.

### Objective 2 - Create PivotTables
- **Monthly Revenue Analysis**: Inserted a PivotTable on a new tab to display revenue by month, providing insights into monthly revenue trends.
- **Weekly and Hourly Transaction Analysis**: Added two additional PivotTables on the same sheet to present the number of transactions by day of the week and by hour of the day, facilitating the identification of peak and off-peak periods.
- **Product Category Transaction Analysis**: Created a PivotTable on the same sheet to show the number of transactions by product category, sorted in descending order by transactions, allowing for the evaluation of category performance.
- **Product Type Analysis**: Developed a PivotTable on the same sheet to show the number of transactions and revenue by product type, sorted in descending order and filtered to the Top 15 (by transactions), highlighting the most popular and profitable products.

### Objective 3 - Build a Dynamic Dashboard
- **Pivot Charts Integration**: Added Pivot Charts to visualize revenue by month (line chart), transactions by day of the week and hour of the day (column charts), and transactions by product category (bar chart), providing a comprehensive visual representation of the data.
- **Dashboard Layout Assembly**: Organized the charts into a preliminary dashboard layout and allocated space for the PivotTable displaying the Top 15 product types, ensuring a cohesive and informative dashboard design.
- **Interactive Slicer Addition**: Introduced a slicer for store location and linked it to all PivotTables on the sheet, enabling dynamic filtering and interactive data exploration.
- **Final Adjustments**: Refined formatting, alignment, and overall presentation to polish the dashboard and enhance readability and usability.

## Conclusion
Based on the in-depth analysis of the graphical representations and pivot tables, several critical insights emerged regarding the Lower Manhattan branch's operational efficiency and sales patterns.

The hourly transaction analysis revealed a significant drop in sales during the late evening hours, particularly after 6 PM. This trend was consistent across multiple days of the week, suggesting a pattern rather than an anomaly. The day-of-week analysis further supported this finding, indicating that the volume of transactions was considerably lower on weekdays during these hours compared to peak times.

Moreover, the revenue analysis corroborated these observations. The revenue generated during the late evening hours was disproportionately low compared to the operational costs incurred during these periods. This imbalance indicates inefficiency in resource utilization during the late hours.

From a strategic standpoint, closing the Lower Manhattan branch earlier in the evening could lead to substantial cost savings. By aligning operational hours with peak sales periods, the branch can optimize staffing levels, reduce utility costs, and enhance overall profitability. This recommendation is further strengthened by the comparative analysis of sales and revenue data across different branches, where it was observed that branches with reduced late evening hours maintained or even improved profitability margins.

In conclusion, by adjusting the operational hours to close earlier in the evening, the Lower Manhattan branch can achieve a significant reduction in expenses without adversely affecting revenue. This strategic adjustment is poised to enhance the branch's financial performance and operational efficiency, thereby contributing positively to the overall business objectives.

<!--
**EduardoSigaud/eduardosigaud** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
