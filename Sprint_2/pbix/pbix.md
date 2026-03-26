## Data Transformation using Power BI (Power Query)

During data preparation, Power Query was used to perform data cleaning and transformation tasks.

### Intern ID Creation
A unique Intern_ID column was created to uniquely identify each intern and avoid duplication issues.

### Steps Performed:
- Loaded the dataset into Power BI (Power Query Editor)
- Ensured proper data types for all columns
- Added an Index column starting from 1
- Created a custom column to generate Intern IDs in the format:
  - INTERN001, INTERN002, ..., INTERN261
- Used formatting logic to maintain leading zeros for consistency

### Purpose:
- To uniquely identify each record
- To improve data organization and tracking
- To enable efficient filtering and analysis in dashboards
