# Bug Report – BR-01

Title:
PUT /users/9999 returns 500 Internal Server Error instead of expected 200 OK

Environment:
API: https://jsonplaceholder.typicode.com
Method: PUT
Endpoint: /users/9999

Preconditions:
User with ID 9999 does not exist.

Steps to Reproduce:
1. Send PUT request to /users/9999
2. Include valid JSON body
3. Execute request

Expected Result:
API should return 200 OK (mock update behavior)

Actual Result:
API returns 500 Internal Server Error

Severity:
Medium

Priority:
Low (Test environment API)

Status:
Open
