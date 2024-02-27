Description:

This SQL project focuses on designing a comprehensive database for salary management in a commercial bank with offices across the globe. The database encompasses five main tables: Seniority, Location, Department, Employee, and Salary.

Seniority Table:

Columns: Id, Name
Manually inserted 10 seniority levels.
Location Table:

Columns: Id, CountryName, Continent, Region
Importing data from Application.Countries table in WideWorldImporters database, resulting in 190 records.
Department Table:

Columns: Id, Name
Manually inserted 10 departments.
Employee Table:

Columns: Id, FirstName, LastName, Location, Seniority level, Department
Importing data from Application.People table in WideWorldImporters database, ensuring 1111 records.
Distributing employees across locations, seniority levels, and departments as specified.
Salary Table:

Columns: Id, EmployeeId, Month, Year, GrossAmount, NetAmount, RegularWorkAmount, BonusAmount, OvertimeAmount, VacationDays, SickLeaveDays
Generating salary data for the past 20 years (01.2001 to 12.2020).
Randomizing gross amounts between 30,000 and 60,000.
Calculating net amount as 90% of the gross amount.
Determining RegularWorkAmount, BonusAmount, and OvertimeAmount based on specified criteria.
Allocating 10 vacation days in July and 10 in December for all employees.
Introducing random vacation days and sick leave days.
This project aims to provide a robust database structure for managing employee information, including seniority, location, department, and detailed salary records over the past two decades. The design ensures diversity in seniority levels, departments, and global locations, making it a comprehensive solution for salary management in a multinational banking environment.
