# Employee Management System Linux

The provided code is a bash script for a basic employee management system. It allows users to perform various operations on employee records, such as inserting new records, displaying records, searching for specific employees, updating existing records, and deleting records. The script reads and writes data to a file named "Employee.txt."

The main features of the employee management system include:

1. Insert: Allows users to input details for a new employee and add them to the "Employee.txt" file. The Employee ID is automatically generated based on the existing records.

2. Delete: Enables users to delete an employee's record by providing their Employee ID. The script marks the record as deleted by setting the "tfval" field to "false."

3. Update: Allows users to modify the details of an existing employee by providing their Employee ID. The script updates the fields with the new values.

4. Display: Displays all the active or currently working employees records from the "Employee.txt" file in a tabular format.

5. Search: Enables users to search for a specific employee's details by providing their Employee ID.

6. Specific Operations: Provides a submenu with various specific operations that can be performed on the employee data, such as filtering employees by department, designation, joining year, gender, salary range, etc. The cases for each operation are implemented.

7. Exit: Allows users to exit the script and terminate the employee management system.

Remember that this script is just a simple example of an employee management system in bash and might not be suitable for complex or large-scale projects. You can utilize this code as a starting point and build upon it according to your needs. 
