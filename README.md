# Paylocity-manual-assignment
Manual test bugs

Scenario 1: Add Employee
GIVEN an Employer
AND I am on the Benefits Dashboard page WHEN I select Add Employee
THEN I should be able to enter employee details AND the employee should save
AND I should see the employee in the table AND the benefit cost calculations are correct

1. When I add first and last name and save the details, 
First name appears in "LAST NAME" and last name is on "FIRST NAME" column 
2. When adding new employee name, it accepts numbers and symbols as well. 

Scenario 2: Edit Employee
GIVEN an Employer
AND I am on the Benefits Dashboard page WHEN I select the Action Edit
THEN I can edit employee details
AND the data should change in the table

1. On the Benefits Dashboard page WHEN I select the Action Edit
it shows as "Add Employee" instead of "Edit"
2. When editing, I think ID number should be unique.
We should not be able to use, for example, Steve Rodger's id # and add first and last name of Bruce Benner.  

Scenario 3: Delete Employee
GIVEN an Employer
AND I am on the Benefits Dashboard page WHEN I click the Action X
THEN the employee should be deleted

API: 
1. Date is incorrect in Responce Header;
2. When adding new employee name information, it accepts numbers and symbols as well.
