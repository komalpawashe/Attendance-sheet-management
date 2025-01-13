# Attendance-sheet-management
This project demonstrates the management of an employee attendance sheet using Excel. It provides a structured and automated way to track employee attendance, calculate leave balances, late marks, half days, and total working days. The system simplifies attendance tracking while ensuring accuracy in leave and attendance calculations.
Features
Daily Attendance Tracking:

Supports various attendance statuses: Present (P), Absent (A), Half Day (HD), Holiday (H), and Late Marks (LM).
Automated Calculations:

Present Days: Total days an employee is marked as present.
Holidays: Automatically tracks official holidays.
Half Days: Differentiates between actual and penalty half days.
Late Marks Penalty: Deducts penalty half days based on the number of late marks.
Leave Balance: Tracks sick and personal leave balances for each employee.
Customizable Thresholds:

Define thresholds for penalties (e.g., 3 late marks = 1 penalty half day).
Summary Reports:

Generate detailed attendance summaries for each employee.
Calculate total leaves taken and remaining balances.
Dynamic Updates:

Uses Excel formulas and structured references for real-time calculations.
Compatible with pivot tables for detailed reporting.
How It Works
Data Input:

Input daily attendance statuses for employees in a structured table format.
Use predefined codes (e.g., "P", "A", "H", "HD", "LM") for consistency.
Automated Calculations:

Formulas automatically compute totals for present days, holidays, half days, late marks, and penalties.
Leave balances are updated dynamically based on attendance data.
Visual Representation:

Conditional formatting highlights different statuses for better visualization (e.g., "P" in green, "A" in red).
Customizable:

Easily adaptable for different organizations with varying leave policies and penalty thresholds.
Usage
Clone or download the repository.
Open the Excel file and input employee data and daily attendance records.
Customize the leave policies and penalty rules as needed.
Review the attendance summaries for each employee using the pre-built formulas and reports.
Technologies Used
Microsoft Excel:
Formulas: COUNTIF, COUNTIFS, SUM, IF, INT.
Data Validation: Ensures standardized input.
Conditional Formatting: Enhances data visualization.
Excel Tables: Dynamic data range management.
GitHub:
Version control and collaboration for sharing attendance templates and enhancements.
