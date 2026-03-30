# Sprint 3 – KPI Definition & Dashboard Development

## Overview

In Sprint 3, the focus was on defining key performance indicators (KPIs) and developing an interactive dashboard for analyzing intern performance. This phase transformed the prepared dataset from Sprint 2 into meaningful insights through structured metrics and visual representations.


## Objectives

* Define relevant KPIs for intern performance evaluation
* Implement KPI calculations using DAX in Power BI
* Design and develop an interactive dashboard
* Enable data-driven analysis through visualizations


## KPI Definition

Key Performance Indicators (KPIs) were defined to measure intern performance, attendance, and overall engagement. These KPIs provide a structured way to evaluate and compare intern data.

### Defined KPIs

1. **Total Interns**
   Represents the total number of interns in the dataset.
   Purpose: To understand dataset size and scope

2. **Average Performance Score**
   Calculates the average performance rating of interns
   Purpose: To evaluate overall performance level

3. **Top Performers**
   Interns with performance rating greater than 7 and attendance not categorized as low
   Purpose: To identify high-performing interns

4. **Low Performers**
   Interns with performance rating less than or equal to 4
   Purpose: To identify interns who need improvement

5. **Attendance Distribution**
   Categorization of interns based on attendance levels (High, Medium, Low)
   Purpose: To analyze engagement and consistency

6. **Top Performer Percentage**
   Ratio of top performers to total interns
   Purpose: To measure overall performance quality


## Implementation

### Data Modeling

* Established relationships between datasets using Intern ID
* Ensured data consistency and removed redundancy
* Structured tables for efficient analysis

### DAX Calculations

* Created calculated columns and measures for KPIs
* Applied conditional logic for performance categorization
* Used aggregation functions such as COUNT, AVERAGE, and CALCULATE


## Dashboard Development

An interactive dashboard was created using Power BI with the following components:

### Visual Elements

* KPI Cards: Display key metrics such as total interns and average performance
* Bar Charts: Compare performance across different categories
* Pie Charts: Show attendance distribution
* Tables: Provide detailed intern-level information

### Interactivity

* Filters based on department, education, and gender
* Drill-down functionality for deeper analysis
* Dynamic updates based on user selection


## Key Insights

* Interns with higher attendance tend to have better performance scores
* Certain groups show consistently strong performance trends
* A small portion of interns have low performance, indicating areas for improvement
* Majority of interns fall within the medium performance range


## Challenges Faced

* Defining meaningful KPIs aligned with project objectives
* Ensuring accurate DAX calculations
* Managing data relationships without errors
* Designing a clear and user-friendly dashboard layout


## Outcome

* Successfully defined and implemented KPIs
* Developed an interactive and analytical dashboard
* Enabled better understanding of intern performance trends
* Established a foundation for advanced insights in the next sprint


## Next Steps (Sprint 4)

* Finalize dashboard design and layout
