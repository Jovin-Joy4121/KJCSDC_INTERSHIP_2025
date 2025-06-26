![sdcsi](https://github.com/user-attachments/assets/b0f238c1-4187-4e67-ba2d-9a52a8884c1f)

**🌞 Summer Internship - KJC SDC 2025**


This repository contains daily tasks and projects completed during the Summer Internship program at KJC SDC in 2025. Each day focused on developing real-world applications using Java and modern backend tools like MongoDB.



**📅 Day 2 - Java Fundamentals & OOP**


**✅ Tasks (Evening)**

**1️⃣ Create Maven Project**
Project Name: Day2<regno>

**Dependencies Added:**

Apache Log4j SLF4J Binding

Mongodb Sync

Apache Commons CLI


**2️⃣ Library Management System (OOP - Inheritance)**

Designed a Java application using inheritance:

Book (Base class)

FictionBook, NonFictionBook (Subclasses)

**3️⃣ Banking System Simulation**

Created a basic banking system supporting:

Account creation

Deposits and withdrawals

Balance inquiry

Exception Handling Implemented:

Overdrafts

Negative transactions

Invalid/non-existent accounts



**📅 Day 3 - MongoDB Integration**


**✅ Task: Student Enrollment System using MongoDB**

Java Application to:

Manage students, courses, and enrollments.

Demonstrate use of embedded vs referenced documents.

**📋 Requirements:**

**✅ MongoDB Collections:**

students — stores student details

courses — stores course details

enrollments — stores enrollment records



**✅ Document Structure:**

One enrollment embeds student and course details.

Another enrollment references student and course documents via ObjectId.


**🚀 To-Do:**

Insert sample student and course data.

Create enrollments:

One with embedded documents.

One with referenced ObjectIds.

Query and print both types with full details.

Update a student's name:

Observation: Updating embedded vs referenced documents shows how references remain consistent across documents, while embedded data must be updated in every instance.



**Create indexes on the students collection for efficient querying.**

Include screenshots of:

Students collection

Courses collection

Enrollments collection

**📸 Screenshots:**

![students(24mcaa34)](https://github.com/user-attachments/assets/6b179bef-ed3b-4794-9402-719b2264ba2a)
![enrollments(24mcaa34)](https://github.com/user-attachments/assets/31e21267-b523-421f-9c6e-a91d158ceb42)
![courses(24mcaa34)](https://github.com/user-attachments/assets/8568160a-873e-4893-b2e9-0b1a58e9f304)


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



**Task Day 9**

**1. Build an Order Tracking Feature for an E-commerce System**
   
**a. Functionalities:** 

**i. Place new orders** 

**ii. Update order status**

**iii. Retrieve order history by user**

**iv. Aggregate total sales for a given product or time period**

Perform the above task using the project structure shared earlier. 
