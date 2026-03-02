# API Test Execution Report

| Test ID | Endpoint | Expected | Actual | Status |
|---------|----------|----------|--------|--------|
| AS-01 | GET /users | 200 | 200 | Pass |
| AS-02 | GET /users/1 | 200 | 200 | Pass |
| AS-03 | GET /users/999 | 404 | 404 | Pass |
| AS-05 | POST /users | 201 | 201 | Pass |
| AS-06 | POST /users (missing email) | 201 | 201 | Pass |

## Summary

Total Executed: 6  
Passed: 6  
Failed: 0  
