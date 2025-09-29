# Test Case – Password Transmission over HTTP

**ID:** SEC-002  
**Title:** Verify password is not transmitted in plain text  
**Preconditions:**  
- Application login page available.  

**Steps:**  
1. Open browser developer tools (Network tab).  
2. Attempt to log in with valid credentials.  
3. Inspect the request payload.  

**Expected Result:**  
- Password must not appear in plain text.  
- Connection must use HTTPS with secure encryption.  
