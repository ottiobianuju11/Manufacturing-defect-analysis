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

1. Structural defects are the most common defect type in this period

2.January 2024 was the costliest month for repairs

3. Product 81 accounts for the highest defect and repair cost concentration, making it a priority for root-cause investigation
 Severity and inspection method slicers allow drill-down into how defects were caught (Automated Testing, Manual Testing, Visual Inspection)

# Recommendation 

1. Shift inspection focus toward structural checks
Since Structural defects outnumber Functional and Cosmetic, recommend reviewing where structural issues are being caught, are they slipping through until final inspection, or being caught early? If they're caught late, moving structural checks earlier in the production line (in-process inspection vs. end-of-line) could reduce cost per defect, since early-stage catches are almost always cheaper to fix

2. Audit what changed in January
Before writing January off as "just a bad month," recommend pulling production records for that period, new supplier, new batch of raw materials, staffing changes, or a new product launch could all explain the cost spike. If it's a fixable one-time cause, that's a quick win; if it's systemic, it needs a bigger process fix. Also, a yearly maintenance and routine checks are to be carried on all machine before the start of production for the year 

3.   Investigate Product 81 as a priority root-cause case
Since it's both the most defective and one of the highest-cost products, recommend a focused root-cause review (5-whys or fishbone analysis) on its production/inspection process specifically, rather than treating it as part of general QC. A fix here has the best cost-to-effort payoff of anything in the dataset.

4. Set a monthly repair-cost benchmark
 A monthly cost threshold/alert should be set  so the QC team gets flagged when a month is trending like January did, instead of finding out only after the report is compiled.


# Design Notes

The dashboard uses a navy, light green, and red colour system:

Navy for structural/primary chart elements

Navy/red for standout KPI values

Red reserved for the Total Defects KPI, flagging it as the metric needing the most attention

# Tools Used
Power BI Desktop — data modeling, DAX measures, dashboard design
Excel — initial data cleaning and Pareto (80/20) analysis
Background

This project builds on a QC analyst background in manufacturing, applying real-world defect and repair cost data to identify actionable quality improvement priorities.

 # Files

 manufacturing_defect_dashboard.pbix — Power BI source file

 Dataset - excel worksheet
  
 # Author

Otti Obianuju Portfolio · LinkedIn · GitHub
