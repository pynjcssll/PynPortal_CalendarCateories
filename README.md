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

•
UPDATE contractorCalendar
SET contractor = 'Contracts and Invoicing'
WHERE contractorCalendarID = 1;

•	
UPDATE contractorCalendar
SET contractor = 'Participant Payroll'
WHERE contractorCalendarID = 2;
•	
UPDATE contractorCalendar
SET contractor = 'WorkReady Summer Programmatic'
WHERE contractorCalendarID = 3;
•	
UPDATE contractorCalendar
SET contractor = 'E3 Power Center Programmatic'
WHERE contractorCalendarID = 4;

•	
UPDATE contractorCalendar
SET contractor = 'Out-of-School Time (OST) Programmatic'
WHERE contractorCalendarID = 5;
•	
UPDATE contractorCalendar
SET contractor = 'School-year Experiences'
WHERE contractorCalendarID = 6;

•
Contractor Code: 
Originally linked to contract codes

•
Updated contractCode to "Everyone" until further notice for all 6 new categories.


