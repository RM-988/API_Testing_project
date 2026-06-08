# API Testing Using Postman

## Project Overview

This project demonstrates API testing using Postman. The objective is to validate REST API functionality by verifying response status codes, response data, and handling of positive and negative test scenarios.

## Objectives

- Validate API responses
- Verify HTTP status codes
- Perform positive testing
- Perform negative testing
- Document test cases and test results

## Tools Used

- Postman
- Microsoft Excel
- GitHub

## APIs Tested

### Get All Users

Method: GET

Endpoint:

https://jsonplaceholder.typicode.com/users

Expected Result:
- Status Code: 200 OK
- List of users returned

### Get Single User

Method: GET

Endpoint:

https://jsonplaceholder.typicode.com/users/1

Expected Result:
- Status Code: 200 OK
- User details returned

### Invalid Endpoint Testing

Method: GET

Endpoint:

https://jsonplaceholder.typicode.com/userxyz

Expected Result:
- Status Code: 404 Not Found

## Test Scenarios Covered

- Response Validation
- Status Code Validation
- Positive Testing
- Negative Testing
- Data Verification

## Project Deliverables

- API_Test_Cases.xlsx
- Test_Execution_Report.xlsx
- Postman_Collection.json
- Screenshots
- README.md

## Sample Test Cases

| Test Case ID | Scenario | Expected Result |
|--------------|----------|----------------|
| API001 | Get All Users | 200 OK |
| API002 | Get Single User | User details returned |
| API003 | Invalid Endpoint | 404 Not Found |

## Outcome

Successfully executed API test cases using Postman, validated API responses, verified status codes, and documented test execution results.

## Skills Demonstrated

- API Testing
- Postman
- REST API Validation
- Test Case Design
- Test Documentation
- Defect Reporting
