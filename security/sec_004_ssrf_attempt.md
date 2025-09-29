# Test Case – Server-Side Request Forgery (SSRF) Attempt

**ID:** SEC-004  
**Title:** Verify the system prevents SSRF attacks  
**Preconditions:**  
- Application has a feature that fetches remote content (e.g., image upload with URL).  

**Steps:**  
1. Navigate to the URL upload feature.  
2. Enter a malicious internal URL (e.g., `http://127.0.0.1/admin`).  
3. Submit the request.  

**Expected Result:**  
- The system must reject the request.  
- Internal or sensitive endpoints must not be accessible.  
- An error message such as **“Invalid URL”** should be displayed.  
