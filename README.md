# Payroll# Payroll Calculator (Excel Project)

## Overview
This Excel-based Payroll Calculator is designed to simplify payroll management for businesses of all sizes. It automates the calculation of employee pay, including overtime bonuses, based on the data provided for each employee. The tool is easy to use and can be customized to suit specific organizational needs.

## Features
1. **Employee Information Management**:
   - Capture employee names (Last Name, First Name).
2. **Hourly Wage Tracking**:
   - Input each employee's hourly wage.
3. **Work Hours Calculation**:
   - Record standard hours worked and overtime hours.
4. **Automated Payroll Calculations**:
   - Compute regular pay based on hours worked.
   - Calculate overtime bonuses.
   - Total pay combines regular and overtime earnings.
5. **Customizable Formulas**:
   - The formulas can be adjusted to accommodate different wage structures or overtime policies.

## How to Use
1. Open the Excel file.
2. Fill in the following columns for each employee:
   - **Last Name**: Employee's last name.
   - **First Name**: Employee's first name.
   - **Hourly Wage**: Hourly rate of the employee.
   - **Hours Worked**: Standard hours worked during the pay period.
   - **Overtime Hours**: Additional hours worked beyond standard hours.
3. The following columns are auto-calculated:
   - **Pay**: `Hours Worked * Hourly Wage`.
   - **Overtime Bonus**: Formula to compute overtime pay based on overtime hours and hourly wage.
   - **Total Pay**: Sum of Pay and Overtime Bonus.

## Formula Breakdown
- **Pay**: `Hours Worked * Hourly Wage`
- **Overtime Bonus**: A custom formula, e.g., `Overtime Hours * Hourly Wage * Overtime Rate` (adjustable).
- **Total Pay**: `Pay + Overtime Bonus`

## Requirements
- **Microsoft Excel** (or any compatible spreadsheet software).
- Basic knowledge of Excel to input and edit data as needed.

## Customization
This payroll calculator can be tailored for specific needs:
- Adjust formulas for overtime rates or bonus structures.
- Add columns for additional deductions or bonuses (e.g., taxes, health benefits).

## Acknowledgments
This project is created to assist HR professionals and small business owners in efficiently managing payroll processes. Suggestions for improvement or feature requests are welcome!

