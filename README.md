# Employee-Management-System

## Introduction

In this documentation, we will guide you through a series of tasks related to managing employee data in Microsoft Excel. The tasks involve creating, organizing, and analyzing employee information using various Excel functions and features. The goal is to help you efficiently handle employee data in a structured manner, while also applying conditional formatting and data validation to make the data more insightful.

## Project objectives and goals

- **Efficient Information Management**: Enable systematic storage of employee data, including unique Employee IDs, full names, departmental details, salaries, and job types.

- **Data Analysis and Visibility**: Facilitate easy access to employee data and the ability to analyze it based on various criteria, such as job type and salary ranges.

- **Enhanced User Experience**: Provide a user-friendly interface for seamless interaction, ensuring intuitive navigation and straightforward data manipulation.

- **Task-Specific Worksheets**: Utilize worksheets to filter and present specific employee information based on predefined criteria, enhancing data presentation and analysis.
The system is designed to improve administrative efficiency and decision-making by enabling organizations to effectively manage and visualize employee data.

## Project Structure and Organization
The Employee Management System is organized in a modular and well-structured manner to ensure clarity, maintainability, and scalability. The project consists of several key components:

## Core Functional Modules:
### Database Management:
- Handles the storage, retrieval, and management of employee data.

### Worksheets:
- Worksheet 1 (Employee Information): Contains a table with 20 rows of employee data with fields such as Employee ID, Employee Full Name, Department, Salary, and Job Type. It applies filters to  
  display freelancers with salaries above $10,000.
- Worksheet 2 (Employee Names Split and Duplicate Check): Processes employee names, splits them into first and last names, and highlights any duplicate names without deletion.
- Worksheet 3 (Employee Name and Salary Formatting): Highlights employees with names starting with 'E' and formats the Salary column with color coding to signify the highest and lowest salaries.

### GitHub Repository:
- The project is hosted on a GitHub repository, organized with clear folder structures and documentation to make it accessible and understandable to contributors and users.

## Data Source
The data provided in this project was created by me from scratch .

## Tool Used
- Microsoft Excel

##  Skills/Concept Demonstarted:
The following skills where used ;
- Table Creation
- Data Validation
- Copy and Paste
- Filtering
- Conditional Formatting
- Text to Columns
- Duplicate Removal

## Steps Implemented On Project

The following steps where used to acheive project result on thedifferent worksheets;

### **Worksheet 1:**
- Open Microsoft Excel and create a new workbook.
- In Worksheet 1, create a table with the following fields:
- Employee ID
- Employee Full Name
- Department (Communications, Sales, I.T)
- Salary (between $5000 to $25000)
Job type (Part-time, Freelance, Contract)
Populate the table with 20 rows of information for employees, ensuring that the Salary field falls within the specified range.
Copy the entire table from Worksheet 1.
Go to Worksheet 2 and paste the table.
Go to Worksheet 3 and paste the same table.
select the entire table.
Use the Filter feature to filter for employees whose Job Type is 'Freelance'.
Once the filter is applied, select the filtered results.
Use the Conditional Formatting feature to highlight the cells where the Salary is above $10,000.

### **Worksheet 2:**
- In Worksheet 2, select the column containing Employee Full Names.
- Use the Text to Columns feature to split the full names into first names and last names.
- Check for duplicate values in the first name or last name columns using the 'Remove Duplicates' tool.
- Highlight duplicates if found.

### **Worksheet 3:**
- In Worksheet 3, select the column containing Employee Full Names.
- Use Conditional Formatting to highlight cells where the name begins with the letter 'E' (use a yellow background).
To format the Salary column:
- Select the Salary column.
- Go to 'Conditional Formatting' and create two rules:
- For the highest salary, set a rule to highlight with a green background.
- For the lowest salary, set a rule to highlight with a red background.


