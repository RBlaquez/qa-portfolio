# Test Case – SQL Injection in Login Field

**ID:** SEC-003  
**Title:** Verify system rejects SQL Injection attempts  
**Preconditions:**  
- Application login page available.  

**Steps:**  
1. Enter `' OR '1'='1` as username.  
2. Enter any password.  
3. Click on "Login".  

**Expected Result:**  
- The system must reject the login attempt.  
- An error message must be displayed.  
- Database must not return all users.  
