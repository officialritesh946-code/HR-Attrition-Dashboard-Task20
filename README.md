# HR Attrition Dashboard — Task 20

## Objective
Build a management dashboard showing attrition by department, role and tenure and turn HR data into management insights.

## Deliverables
- `HR_Attrition_Dashboard.xlsx` — professional Excel workbook with dashboard, analysis sheets, raw data and Power BI DAX measures.
- `HR_Attrition_Dashboard.html` — interactive, browser-based dashboard preview.
- `HR_Attrition_PowerBI_Ready.csv` — presentation-facing dataset for Power BI.
- `HR_Attrition_Project_Report.pdf` — concise project report and five insights.
- `PowerBI_DAX_Measures.txt` — copy/paste DAX measures.

## Headline metrics
- Employees: 1,470
- Attritions: 237
- Attrition rate: 16.1%
- Average monthly income: $6,503
- Overtime attrition rate: 30.5%

## Five insights
1. Overall attrition is 16.1% (237 of 1470 employees), establishing the baseline for all segment comparisons.
2. Sales has the highest department attrition at 20.6%, compared with 17.8% across the three departments.
3. Sales Representatives are the highest-risk role at 39.8%, followed by Laboratory Technicians at 23.9%.
4. Overtime is strongly associated with attrition: 30.5% for employees working overtime versus 10.4% for those who do not.
5. Early tenure is the clearest tenure signal: employees with 0–1 years at the company have 34.9% attrition, while 11–20 years is only 6.7%.

## Power BI build
1. Import `HR_Attrition_PowerBI_Ready.csv`.
2. Create the measures in `PowerBI_DAX_Measures.txt`.
3. Add KPI cards for Total Employees, Attritions and Attrition Rate.
4. Add bar charts for Department and Job Role.
5. Add a tenure bucket chart.
6. Add slicers for Department, JobRole, OverTime, BusinessTravel and TenureBucket.
7. Format Attrition Rate as Percentage with one decimal place.
8. Use aggregate views; do not place employee-level identifiers on the report canvas.

## Data note
The source is an HR attrition analytics dataset. The dashboard focuses on aggregate patterns and excludes EmployeeNumber from the presentation-facing CSV.
