# API Testing Portfolio Project

## Project Overview

This project demonstrates API testing skills using Postman and a public mock API.

Tested API:
https://jsonplaceholder.typicode.com

The project covers full CRUD operations:
- GET
- POST
- PUT
- DELETE

---

## Tools Used

- Postman
- GitHub
- Markdown documentation

---

## Project Structure

01_API_Test_Plan  
02_API_Scenarios  
03_Postman_Collections  
04_Test_Execution_Report  
05_API_Bug_Reports  

---

## What Was Tested

### GET
- Retrieve all users
- Retrieve single user
- Negative test (non-existing user)

### POST
- Create new user
- Create user with missing required field

### PUT
- Update existing user
- Update non-existing user (identified defect)

### DELETE
- Delete existing user
- Delete non-existing user

---

## Defects Identified

1. PUT /users/9999 returns 500 Internal Server Error instead of expected mock 200 response.

Bug report available in:
05_API_Bug_Reports

---

## Author

Cristina Marina  
Junior QA – API Testing Practice Project

## Skills Demonstrated

- REST API Testing
- HTTP Methods (GET, POST, PUT, DELETE)
- Status Code Validation
- Response Body Assertions
- Negative Testing
- Bug Reporting
- Test Documentation

Cristina Marina  
Junior QA – API Testing Practice Project
