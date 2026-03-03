# API Test Scenarios

## GET Requests

AS-01: Verify GET /users returns 200 status code  
AS-02: Verify GET /users?page=2 returns list of users  
AS-03: Verify GET /users/2 returns specific user data  
AS-04: Verify GET /users/999 returns 404  

## POST Requests

AS-05: Verify POST /users – Verify user creation (201)

AS-06: Verify POST /users – Verify behavior with missing fields

## PUT Requests

AS-07 – Verify PUT /users/1 updates existing user (Expected: 200 OK)

AS-08 – Verify PUT /users/9999 for non-existing user 
Expected: 200 OK (mock behavior)
Actual: 500 Internal Server Error 

## DELETE Requests

AS-09: Verify DELETE /users/2 returns 204  
AS-10: Verify DELETE /users/999 handles gracefully


## Execution Status

## GET Requests
AS-01: Pass
AS-02: Pass
AS-03: Pass
AS-04: Pass
