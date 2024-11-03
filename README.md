# HR Attrition Analysis 2024

A synthetic HR dataset and analysis workbook exploring employee attrition between **1 January 2024 and 30 November 2024**.

**Business question:** Why are employees leaving, and which groups are most at risk?

## Contents

| File | Description |
| --- | --- |
| `HR_Attrition_2024.xlsx` | Excel workbook containing the dashboard, analysis, employee-level data, data dictionary, and summary notes. |

## Workbook Structure

- **Dashboard** – headline metrics and visuals.
- **Analysis** – pivot-style breakdowns by department, tenure, overtime, and salary band.
- **Data** – 1,000 employee records across 18 fields.
- **Data Dictionary** – definition, meaning, and valid values for every column.
- **Notes** – findings, recommendations, and the business question.

## Data Dictionary

| Column | Meaning | Values |
| --- | --- | --- |
| Employee ID | Unique employee code | EMP1001 to EMP2000 |
| Full Name | Employee name (synthetic data) | Text |
| Gender | Employee gender | Female / Male |
| Age | Age as of 30 Nov 2024 | 22 to 58 |
| Department | Department the employee belongs to | 8 departments |
| Job Title | Role within the department | Text |
| Office Location | Main office city | Text |
| Hire Date | Date the employee joined | 2015 to 2024 |
| Tenure (Years) | Years between hire date and exit date (leavers) or 30 Nov 2024 (current) | Number |
| Annual Salary (USD) | Gross annual salary | Number |
| Performance Rating (1-5) | Latest appraisal rating, 1 = poor, 5 = outstanding | 1 to 5 |
| Job Satisfaction (1-4) | Survey score, 1 = very low, 4 = very high | 1 to 4 |
| Overtime | Regularly works overtime | Yes / No |
| Attrition | Left the company in 2024 (up to 30 Nov) | Yes / No |
| Attrition Flag (1=Left) | Numeric version of Attrition, used for averages and rates | 1 / 0 |
| Exit Date | Date the employee left | Blank if still employed |
| Exit Reason | Main reason given in the exit interview | Blank if still employed |

## Key Findings

1. **Overall attrition is 14.6%.** 146 of 1,000 employees left during the period.
2. **Highest risk by department:** Sales (22.3%), Customer Support (21.7%), and Operations (20.7%). Lowest: Engineering (7.6%) and Finance (6.5%).
3. **New employees are most at risk.** Staff with under 2 years' tenure have a 26.0% attrition rate, compared with 13.3% for 2 to 5 years. No employee with 8+ years' tenure left.
4. **Overtime matters.** Employees who work overtime leave at 17.8%, versus 13.4% for those who do not.
5. **Pay and workplace factors dominate.** Attrition is 20.1% for salaries under 50K, versus 7.1% for 110K and above. Top exit reasons: better pay elsewhere (40), work-life balance (39), and manager relationship (27).

## Recommendations

1. Run a retention review for new hires in Sales, Customer Support, and Operations. Add check-ins at 3, 6, and 12 months and review onboarding for these teams.
2. Review workloads for employees working regular overtime, starting with Customer Support and Operations. Examine staffing levels and shift planning.
3. Benchmark pay for roles under 50K against the market and track whether pay and work-life balance remain the main reasons people leave.

## Notes

- The data is synthetic and intended for learning and demonstration purposes.
- All attrition figures cover 1 January 2024 to 30 November 2024.

---

*Created: 3 November 2024*
