# First_Excel
# Employee Payroll Assignment

An Excel workbook that calculates weekly payroll for 17 employees, including regular pay, overtime pay, and a five-week total.

## File

- `Employee_Payroll.xlsx`

## What it does

- **House Worked**: hours worked per week (5 weeks, starting Jan 1)
- **Overtime Hours**: hours over 40 per week, calculated with `IF(hours>40, hours-40, 0)`
- **Pay**: regular pay = Hourly Wage × House Worked
- **Overtime Bonus**: extra pay for overtime hours, at 0.5 × Hourly Wage × Overtime Hours
- **Total**: Pay + Overtime Bonus for each week
- **Jan Total**: sum of all five weekly totals
- Summary rows for Max, Min, Average, and Total across all employees

## Notes

- Week headers are calculated automatically (`=previous date + 7`) so the dates stay in sync if the start date changes.
