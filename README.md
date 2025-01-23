# PowerBI_HRDashboard_project
This Power BI project focuses on creating an end-to-end centralized dashboard for monitoring key HR metrics. The dashboard empowers HR managers to identify trends in employee performance, monitor retention rates, and conduct real-time workforce reviews.

Project Objective:

- Build a dynamic and centralized Power BI dashboard for HR monitoring.
- Analyze trends in employee performance, retention, and attrition.
- Support data-driven decisions for improving workforce efficiency and engagement.

Features:

1. Key Metrics Overview:

- Employee performance by department, role, and tenure.
- Retention and attrition trends across time.
- Gender diversity, age demographics, and promotion rates.

2.Real-Time Updates:

- Integrated with data sources for automatic updates.
- Designed for real-time workforce monitoring.

3.Data Analysis:

- Identified trends using calculated measures and KPIs built with DAX. Example:

Employee Turnover Rate = 
DIVIDE(
    SUM('Employee Data'[Attrition]),
    COUNTROWS('Employee Data')
  )
 - Visualized employee retention patterns using advanced Power BI visuals.

Conclusion:
This HR Dashboard project demonstrates the value of centralized data visualization for HR analytics. By providing actionable insights and real-time updates, the dashboard equips HR professionals to make informed decisions about employee performance, retention strategies, and workforce planning.

