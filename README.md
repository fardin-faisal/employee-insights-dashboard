# Employee Insights Dashboard

An Excel based HR analytics dashboard built with PivotTables, PivotCharts and slicers
on a dataset of 1,470 employees (1,233 current, 237 former).

![Dashboard](Dashboard%20Images/employee-insights-dashboard.png)

## Questions answered
- How many current employees do we have, and what is the total salary paid? (1,233; 8,424,768)
- Current employees by gender (Male 732, Female 501)
- Education level, job satisfaction and work-life balance ratings
- Monthly salary trend (average salary by start month)
- Salary by years at the company, Full-time vs Contractor
- Salary by total working years, by gender

## How it works
- Source data is an Excel Table; all analysis uses PivotTables with Attrition = "No" (current employees).
- Answer cells use GETPIVOTDATA, so they stay linked to the pivots.
- A Gender slicer filters every chart and card on the dashboard.

## Tools
Microsoft Excel: PivotTables, PivotCharts, slicers, GETPIVOTDATA, dashboard design.

## Files
- `employee-insights-dashboard.xlsx` – the workbook
- `Dashboard%20Images/` – dashboard screenshots (all, Male, Female)

## Author
Mohammed Faisal Fardin Chowdhury – B.Sc. in CSE, IIUC
