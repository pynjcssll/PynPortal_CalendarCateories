# PynPortal_CalendarCateories
Calendar Color Keys updated for the calendar the categories on pynportal?

Prerequisites: 
- SQL Server > dbo contractorCalendar 
- pynportal > https://devportal.pyninc.org/resources/calendar 

 
Updated categories:
•	Contracts and Invoicing
•	Participant Payroll
•	WorkReady Summer Programmatic
•	E3 Power Center Programmatic 
•	Out-of-School Time (OST) Programmatic
•	School-year Experiences

Procedure: 
A) 
UPDATE contractorCalendar
SET contractor = 'Contracts and Invoicing'
WHERE contractorCalendarID = 1;
B) 
UPDATE contractorCalendar
SET contractor = 'Participant Payroll'
WHERE contractorCalendarID = 2;
C) 
UPDATE contractorCalendar
SET contractor = 'WorkReady Summer Programmatic'
WHERE contractorCalendarID = 3;
D) 
UPDATE contractorCalendar
SET contractor = 'E3 Power Center Programmatic'
WHERE contractorCalendarID = 4;
E) 
UPDATE contractorCalendar
SET contractor = 'Out-of-School Time (OST) Programmatic'
WHERE contractorCalendarID = 5;
F) 
UPDATE contractorCalendar
SET contractor = 'School-year Experiences'
WHERE contractorCalendarID = 6;
