# From-messy-data-to-Insightfull-analysis-using-powerBi

## Project Overview
I was provided with a dirty flat dataset from the education sector. The dataset contained
information about students, schools, teachers, subjects, locations, performance, payments, and 
other related records. 
The task was to work on this dataset from start to finish using Power BI. This project was meant to test ability to clean messy data, create a proper data model, write measures, and build a 
useful dashboard. I was therefore expected to apply the skills in Power Query, data modeling, 
relationships, DAX, and dashboard design. 

### Part 1: Data Cleaning 
I started by loading the dirty dataset into Power BI. Cleaned the dataset properly and ensure that the final data is ready for analysis. 
I Paid attention to issues such as: 
- Inconsistent category names 
- Mixed uppercase and lowercase values 
- Wrong spellings 
- Short forms and abbreviations 
- Null values 
- Error values 
- Incorrect data types 
- Invalid numeric values 
- Dates stored in the wrong format 
- Repeated records where necessary 
- Inconsistent location names 
- Inconsistent school, teacher, and student details 
- Incorrect or unclear values in revenue, performance, and payment-related fields
 
My goal was to make sure the cleaned data is consistent, reliable, and ready for modeling. 
I did not remove data blindly. I made reasonable cleaning decisions.

### Part 2: Data Modeling 
After cleaning the dataset, I created a proper model from the flat table. 
The dataset should not remain as one flat table. I was expected to normalize it into meaningful tables where necessary. I was required to think carefully about which columns belong together. 
For example, you may need to think about tables such as: 

1. Student-related table 
2. Teacher-related table 
3. School-related table 
4. Subject-related table 
5. Location-related table 
6. Performance or assessment table 
7. Payment or revenue-related table
   
Also thought about location hierarchy. For example: 
Country → Region → County → Sub-county 
The location table should be reusable where possible. For example, both students and teachers 
may belong to locations, so I was avoid unnecessary duplication if a shared location structure makes sense. My model should support analysis clearly and efficiently. 

In this case I used a star schema but also you can use snowflake schema. 
