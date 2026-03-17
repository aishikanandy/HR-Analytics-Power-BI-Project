##### **DAX Measures used in this Project:**



###### Active Employees = CALCULATE(\[Total Headcount],'HR Data'\[Employment Status]="Active")

###### Attrition Rate = DIVIDE(\[Inactive Employees],\[Total Headcount])

###### Average Salary = AVERAGE('HR Data'\[MonthlySalary])

###### AVG Absent Days = AVERAGE('HR Data'\[AbsenceDaysYTD])

###### AVG Performance Rating = AVERAGE('HR Data'\[PerformanceRating])

###### AVG Training Hours = AVERAGE('HR Data'\[TrainingHoursYTD])

###### Inactive Employees = CALCULATE(\[Total Headcount],'HR Data'\[Employment Status]="Inactive")

###### Total Headcount = COUNT('HR Data'\[EmployeeID])

###### Total Salary Cost = SUM('HR Data'\[MonthlySalary])

