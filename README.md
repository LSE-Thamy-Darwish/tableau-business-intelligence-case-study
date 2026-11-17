# Tableau Business Intelligence Case Study
Data Modelling | Tableau | KPI Development | Business Intelligence

## Project Overview
Developed an end-to-end Tableau analytics solution for a simulated facilities management company as part of a technical assessment for a Senior Business Intelligence Analyst position at CBRE.
The objective was to address two operational challenges: reducing work-order costs and improving on-time service delivery.
Using three interconnected datasets, I developed a relational data model, created calculated performance metrics and built three interactive dashboards to support operational decision-making.

## Dashboard Solutions
1. Executive Review
Provides an overview of operational performance, including work-order volumes, costs, completion rates and geographic trends.

2. On-Time Performance Analysis
Examines service delivery performance across vendors, locations and work-order priorities to identify areas requiring improvement.

3. Work Order Cost Analysis
Analyses labour costs, work-order expenditure and vendor cost efficiency to identify opportunities for operational savings.

## Data Modelling & Preparation

Designed a relational data model integrating three datasets:

Work Orders: Work-order identifiers, dates, priorities, status and problem categories.

Work Details: Vendor information, labour rates and hours worked.

Locations: Geographic and facility-level information.

Connected datasets using primary and foreign keys, applying LEFT JOINs to establish relationships between work orders, work details and locations.

Performed data validation, duplicate checks, date-format verification and semantic mapping to prepare the data for analysis.

## KPI Development

Developed Tableau calculated fields and FIXED level-of-detail expressions to measure:

On-time completion percentage

Total and average work-order costs

Average labour cost per hour

Average hours worked per work order

Vendor performance across service priorities

These calculations supported comparisons across vendors, locations and work-order categories.

## Key Findings & Recommendations

The analysis identified differences in vendor performance, labour costs and service efficiency.

Key recommendations included:

Prioritising vendors demonstrating stronger cost efficiency and on-time performance.

Reviewing underperforming facilities and high-priority work orders.

Establishing consistent KPI benchmarks across vendors.

Monitoring performance over time to support evidence-based operational decisions.

## Tools & Technologies

Tableau Desktop: Interactive dashboards, calculated fields, FIXED LOD expressions and data visualisation.

Data Modelling: Relational schema design, primary and foreign key mapping, LEFT JOINs and semantic mapping.

Data Quality: Duplicate detection, date validation and consistency checks.

## Tableau Workbook

The complete packaged Tableau workbook (.twbx) is included in this repository and contains the dashboard implementation, calculations and supporting data.

This project was completed using a simulated assessment dataset and is shared with permission.
