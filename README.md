# Amazon DynamoDB – Query and Scan Operations

## Project Overview

This repository documents my hands-on implementation of Amazon DynamoDB Query and Scan operations using the AWS Management Console.

The practical demonstrates how employee information can be stored, retrieved, and filtered using DynamoDB.

## Technologies Used

- Amazon Web Services (AWS)
- Amazon DynamoDB
- AWS Management Console
- Git and GitHub

## Table Configuration

| Property | Value |
|---|---|
| Table Name | EmployeeDetails |
| Partition Key | Department |
| Sort Key | EmployeeId |
| Capacity Mode | On-demand |
| Region | Asia Pacific (Mumbai) |

## Operations Performed

### 1. Scan Operation
Retrieved employee records from the EmployeeDetails table.

### 2. Query Operation
Retrieved employee information using the partition key condition:

`Department = IT`

### 3. Filtered Scan Operation
Retrieved employee records using the salary condition:

`Salary > 50000`

## Results

| Operation | Condition | Records |
|---|---|---:|
| Initial Scan | Empty table | 0 |
| Scan | All records | 4 |
| Query | Department = IT | 1 |
| Filtered Scan | Salary > 50000 | 4 |

## Key Learnings

- DynamoDB table creation
- Partition and sort keys
- Employee data insertion
- Query and Scan operations
- Filter expressions
- NoSQL database fundamentals

## Conclusion

Successfully created an EmployeeDetails table and demonstrated Query, Scan, and Filtered Scan operations using Amazon DynamoDB.

This practical provided hands-on experience with NoSQL database management and data retrieval using AWS.

**Lab Number:** 47  
**Project Status:** Completed
