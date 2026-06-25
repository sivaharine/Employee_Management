*This is a simple Java project used to manage employee details.
*The project creates full-time, part-time, and contract employees.
*Employee details are stored and managed using the EmployeeService class.
*The project can add employees, display employees, search an employee by ID, update an employee department, delete an employee, and calculate total salary.
*EmployeeMgtApp is the main class that runs the project and shows all operations with sample employee data.
*The project uses abstraction through the abstract Employee class.
*It uses inheritance through FullTimeEmployee, PartTimeEmployee, and ContractEmployee.
*It uses method overriding because each employee type has its own calcSalary() logic.
*It uses a sealed class to restrict which classes can extend Employee.
*It uses an enum called Department to store department names.
*It uses a record called Address to store address details.
*It uses ArrayList in the service layer to store and manage employees.
