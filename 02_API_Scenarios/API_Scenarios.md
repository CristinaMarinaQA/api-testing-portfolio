# API Test Scenarios

## GET Requests

AS-01: Verify GET /users returns 200 status code  
AS-02: Verify GET /users?page=2 returns list of users  
AS-03: Verify GET /users/2 returns specific user data  
AS-04: Verify GET /users/999 returns 404  

## POST Requests

AS-05: Verify POST /users creates new user  
AS-06: Verify POST /users with missing fields returns error  

## PUT Requests

AS-07: Verify PUT /users/2 updates user  
AS-08: Verify PUT /users/999 returns error  

## DELETE Requests

AS-09: Verify DELETE /users/2 returns 204  
AS-10: Verify DELETE /users/999 handles gracefully


## Execution Status

## GET Requests
AS-01: Pass
AS-02: Pass
AS-03: Pass
AS-04: Pass
