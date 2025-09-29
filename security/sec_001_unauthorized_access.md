# Test Case – Unauthorized Access to User Profile

**ID:** SEC-001  
**Title:** Verify user cannot access another user’s profile  
**Preconditions:**  
- Two users exist: UserA and UserB.  
- Both accounts are active.  

**Steps:**  
1. Login as UserA.  
2. Attempt to access UserB’s profile via direct URL.  

**Expected Result:**  
- The system must return **“Access Denied”**.  
- UserA must not see UserB’s data.  
