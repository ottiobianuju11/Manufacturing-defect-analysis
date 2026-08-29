# Manufacturing-defect-analysis
A Power BI dashboard analyzing manufacturing defect data across a 6-month period, built to identify defect patterns, cost drivers, and quality control priorities

# 📊 Overview

This dashboard analyzes 1,000 defect records to help quality teams pinpoint where defects are occurring, what they're costing, and which products need the most attention.

# Key Metrics
Metric	Value
 Total Defects	1,000
 
 Total Repair Cost	$507.63K

Most Expensive Month	January 2024

Most Defective Product ID	81

#  Visuals Included

Defect Type Breakdown — Count of defects by type (Structural, Functional, Cosmetic)

Defect Location Breakdown — Sum of defects by location (Surface, Component, Internal)

Defect Trends by Month/Year — Monthly defect volume trend, Jan–Jun 2024

Repair Cost by Product ID — Which products are driving repair spend

Slicers — Inspection method, severity (Critical / Moderate / Minor), defect type, and date range
# Key Insights

Structural defects are the most common defect type in this period

January 2024 was the costliest month for repairs

Product 81 accounts for the highest defect and repair cost concentration, making it a priority for root-cause investigation
Severity and inspection method slicers allow drill-down into how defects were caught (Automated Testing, Manual Testing, Visual Inspection)

# Design Notes

The dashboard uses a navy, light green, and red color system:

Navy for structural/primary chart elements

Navy/red for standout KPI values

Red reserved for the Total Defects KPI, flagging it as the metric needing the most attention

Tools Used
Power BI Desktop — data modeling, DAX measures, dashboard design
Excel — initial data cleaning and Pareto (80/20) analysis
Background

This project builds on a QC analyst background in manufacturing, applying real-world defect and repair cost data to identify actionable quality improvement priorities.

Files

 manufacturing_defect_dashboard.pbix — Power BI source file

 Dataset - excel worksheet
  
Author

Otti Obianuju Portfolio · LinkedIn · GitHub
