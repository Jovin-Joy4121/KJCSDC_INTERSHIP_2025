
**TASK DAY-5**

**Objective:**

**Build an Employee Management Portal using Java and MongoDB that provides 
functionality to:**

● Add employee records 

● Update and delete employee records 

● Filter and search employees by various fields 

● Perform aggregation-based queries (e.g., count per department) 

**Core Tasks** 

**1. Add Employee** 
● Insert a new document into the employees collection.

● Validate that the employee’s email is unique before insertion. 

**2. Update Employee**
   
● Update specific fields of an employee document (e.g., skills, department). 

● Ensure that only the specified fields are updated and the rest of the document 
remains unchanged. 

**3. Delete Employee**
   
● Delete an employee document using either: 

● Email, or

● Employee ID (_id field in MongoDB) 

**4. Search Employees**
   
Provide filtering and searching capabilities based on: 

● By Name: Use regex for partial match (e.g., find names containing “john”). 

● By Department: Filter employees belonging to a specific department. 

● By Skill: Match if any skill in the skill array matches the input. 

● By Joining Date Range: Filter employees who joined between specified dates 
(e.g., all who joined in the year 2023). 

**5. List with Pagination**
● Paginate the results to return a fixed number of employees per page (e.g., 5 
employees per page).

● Allow sorting by:

○ Name 

○ Joining Date 

**6. Department Statistics**
    
● Perform an aggregation query to group employees by department. 

● Count the number of employees in each department. 

● Return results like: 