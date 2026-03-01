# Snack Nutrition Analysis (SQL + Tableau)

## Project Overview
This project demonstrates an end-to-end data analysis workflow:
SQL database creation, data cleaning, analysis, and visualization using Tableau.

## Tools Used
- SQLite (DB Browser for SQLite)
- SQL
- Microsoft Excel
- Tableau Public

## Dataset
Snack nutrition dataset including:
- Snack name
- Category
- Calories
- Protein (grams)
- Notes

Total snacks analyzed: 6

## SQL Work Performed
- Created table with primary key
- Inserted multiple snack records
- Removed duplicates
- Queried highest and lowest calorie snacks
- Calculated average calories
- Sorted and aggregated data

## Key SQL Queries
Example: Highest calorie snack

```sql
SELECT snack_name, calories
FROM snacks
ORDER BY calories DESC
LIMIT 1;

Tableau Dashboard
🔗 View the interactive dashboard here:
https://public.tableau.com/views/SnackNutritionAnalysisDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Key Insights:
Generic Granola Bar (medium) had the highest calorie content (342 kcal)
Regular Snack Crackers had the lowest calorie count (82 kcal)
Calorie variation across snack types is significant

Skills Demonstrated:
Data modeling
SQL querying (SELECT, ORDER BY, LIMIT, AVG)
Data cleaning
Data visualization
Dashboard design
