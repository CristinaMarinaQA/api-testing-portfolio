# API Test Execution Report

| Test ID | Endpoint | Expected | Actual | Status |
|---------|----------|----------|--------|--------|
| AS-01 | GET /users | 200 | 200 | Pass |
| AS-02 | GET /users/1 | 200 | 200 | Pass |
| AS-03 | GET /users/999 | 404 | 404 | Pass |
| AS-05 | POST /users | 201 | 201 | Pass |
| AS-06 | POST /users (missing email) | 201 | 201 | Pass |
| AS-07 | PUT /users/1 | 200 | 200 | Pass |
| AS-08 | PUT /users/9999 | 200 | 500 | Fail |


## Defects Identified:
- PUT /users/9999 returns 500 Internal Server Error instead of the expected 200 mock response.

## Summary

Total Executed: 8  
Passed: 7  
Failed: 1  
